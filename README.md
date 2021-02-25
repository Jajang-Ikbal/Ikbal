
*{
	padding: 0;
	margin: 0;
}
html{
	scroll-behavior: smooth;
}
nav{
	position: fixed;
	left: 0;
	top: 0;
	right: 0;
	padding: 15px;
	display: flex;
	justify-content: space-around;
	background-color:rgba(255,0,0,0);
	/background-image: linear-gradient(to right, #00e600 ,  #4dff4d);/
}
nav .logo{
	/width: 50%;/
	color:  #3EBB86;
}
nav ul{
	list-style: none;
	width: 40%;
	display: flex;
	justify-content: space-between;
	
}
nav ul li a{
	text-decoration: none;
	padding: 5px;
	color: black;
	/font-family: arial, sans-serif;/

}
nav ul li a:hover{
	background-color:  #3EBB86;
	border-radius: 10px;
	color: black;
}
nav ul li button{
	padding: 5px;
	border-radius: 10px;
	border: 0;
	cursor: pointer;
	background-color:  #3EBB86;
	color: white;
	font-weight: bold;
}
.container-satu{
	padding: 50px 0;
	width: 100%;
	display: flex;
	justify-content: center;
	/background-color: yellow;/
	/*background-image: url(https://lh3.googleusercontent.com/proxy/M1dfwdsoz7Fwb72t7gmrZlN3u8Up0q7kVfyjbvom31NDdHOupbGL7_eOeS4O3wrS-hCtfJ7fzN1OcogBkscSdUv7qoQzREAdYplVh1d2EhHXRPZ_0YxFJReEcew8s_CcrVAxovO37jJ7SKWvpgzs5FcUau-G7g);*/
}
.container-satu .teks-satu{
	width: 35%;
	padding: 20px;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	box-sizing: border-box;
	/*/background-color: salmon;/*/
}
.teks-satu input{
	width: 250px;
	height: 35px;
	border-radius: 15px;
	border: 0;
	box-shadow: 0 0 5px #888888;
}
.teks-satu button{
	padding: 10px;
	border-radius: 15px;
	border: 0;
	background-color:  #3EBB86;
	margin-left: -60px;
	box-shadow: 5px 0 4px #888888;
	cursor: pointer;
}
.container-satu .foto-satu{
	width: 52%;
	/*background-color: red;*/
}
.foto-satu img{
	margin: 0 100px;
}
.container-dua .teks-dua{
	text-align: center;
	padding: 50px 0 0 0;
}
.teks-dua p{
	padding: 10px;
}
.container-dua .foto-dua{
	padding: 50px 0;
	margin: auto;
	width: 90%;
	display: flex;
	justify-content: space-around;
	/*background-color: yellow;/*/
}
.foto-dua .ft1{
	width: 16%;
	text-align: center;
	/*/background-color: red;/*/
}
.foto-dua .ft2{
	width: 16%;
	text-align: center;
	/*/background-color: red;/*/
}
.foto-dua .ft3{
	width: 16%;
	text-align: center;
	/*/background-color: red;/*/
}
.container-tiga{
	padding: 20px;
	width: 100%;
	display: flex;
	justify-content: center;
	/*/background-color: yellow;/*/
}
.container-tiga .teks{
	width: 44%;
	display: flex;
	justify-content: center;
	align-items: left;
	flex-direction: column;
	/*/background-color: salmon;/*/
}
.container-tiga .btn{
	width: 38%;
	height: 40px;
	display: flex;
	justify-content: flex-end;
	/*/background-color: red;/*/
}
.btn button{
	padding: 0 10px;
	border-radius: 50%;
	font-size: 20px;
	border: 0;
	cursor: pointer;
	background-color: #1aff1a;
	margin-left: 10px;
}
.container-empat{
	margin: auto;
	padding: 30px 0;
	width: 95%;
	display: flex;
	justify-content: space-between;
	/*/background-color: yellow;/*/
}
.container-empat a{
	width: 20%;
	height: 250px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	box-shadow: 0 0 5px black;
	border-radius: 10px;
	text-decoration: none;
	color: black;
	/*/background-color: blue;/*/
}
.card-satu p{
	text-align: center;
}
.container-empat a{
	width: 20%;
	height: 250px;
	text-align: center;
	box-shadow: 0 0 5px black;
	border-radius: 10px;
	text-decoration: none;
	color: black;
	/*/background-color: blue;/*/
}
.container-empat a{
	width: 20%;
	height: 250px;
	text-align: center;
	box-shadow: 0 0 5px black;
	border-radius: 10px;
	text-decoration: none;
	color: black;
	/*/background-color: blue;/*/
}
.container-empat a{
	width: 20%;
	height: 250px;
	text-align: center;
	box-shadow: 0 0 5px black;
	border-radius: 10px;
	text-decoration: none;
	color: black;
	/*/background-color: blue;/*/
}
.container-lima{
	width: 100%;
	display: flex;
	justify-content: space-between;
	margin: 50px 0;
	/*/background-color: yellow;/*/
}
.container-lima .foto-satu{
	width: 55%;
	/*/background-color: salmon;/*/
}
.container-lima .foto-satu img{
	width: 100%;
}
.container-lima .teksSatu{
	width: 40%;
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	/*/background-color: red;/*/

}
.container-enam{
	width: 100%;
	height: 280px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
	align-items: center;
	/*/background-color: yellow;/*/
}
.container-enam .judul{
	width: 75%;
	/*/background-color: red;/*/
}
.container-enam .testy{
	/*/background-color: salmon;/*/
	width: 90%;
	display: flex;
	justify-content: space-between;
	flex-direction: row;
}
.testy .testimoni-satu{
	width: 250px;
	height: 200px;
	display: flex;
	flex-direction: column;
	/*/background-color: red;/*/
	border-radius: 20px;
	box-shadow: 0 0 5px black;
	padding: 10px;
	box-sizing: border-box;
	justify-content: space-around;
}

.testy .testimoni-dua{
	width: 250px;
	height: 200px;
	display: flex;
	flex-direction: column;
	/*/background-color: red;/*/
	border-radius: 20px;
	box-shadow: 0 0 5px black;
	padding: 10px;
	box-sizing: border-box;
	justify-content: space-around;
}

.testy .testimoni-tiga{
	width: 250px;
	height: 200px;
	display: flex;
	flex-direction: column;
	/*/background-color: red;/*/
	border-radius: 20px;
	box-shadow: 0 0 5px black;
	padding: 10px;
	box-sizing: border-box;
	justify-content: space-around;
}
.profil{
	display: flex;
	width: 100%;
	/*/background-color: yellow;/*/
	justify-content: space-between;
}
.profil .circle{
	border-radius: 50%;
	width: 70px;
	height: 70px; 
	overflow: hidden;
	box-shadow: 0 0 2px black;
	/*/background-color: blue;/*/

}
.profil p{
	width: 65%;
	padding: 7px 0 0 0;
	/*/background-color: salmon;/*/
}
.circle.satu img{
	margin-left: -85px;
}
.circle.dua img{
	margin-left: -20px;
}
.container-tujuh{
	width: 100%;
	display: flex;
	flex-direction: column;
	align-items: center;
}

/* Contact section */
 a:hover {
  color: #4A4C4D;
}

.contact-section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 100%;
  height: 80vh;
  padding: 0 2rem;
  background: var(--main-gray);
}

.contact-section-header > h2 {
  font-size: 3rem;
}

@media (max-width: 28.75em) {
  .contact-section-header > h2 {
    font-size: 2rem;
  }
}

.contact-section-header > p {
  font-style: italic;
}

.contact-links {
  display: flex;
  justify-content: center;
  width: 100%;
  max-width: 980px;
  margin-top: 4rem;
  flex-wrap: wrap;
}

.contact-details {
  font-size: 20px;
  text-shadow: 2px 2px 1px #1f1f1f;
  transition: transform 0.3s ease-out;
}

.contact-details:hover {
  transform: translateY(8px);
}
  
  .container-tujuh{
	width: 100%;
	display: flex;
	flex-direction: column;
	align-items: center;
}
.container-tujuh{
	padding: 50px 0;
	box-sizing: content-box;
	width: 100%;
	height: 200px;
	/background-color: yellow;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: space-between;
}
.container-tujuh h2{
	font-size: 30px;
}
.container-tujuh .partner{
	width: 100%;
	display: flex;
	align-items: center;
	/background-color: salmon;
	justify-content: center;
} 
.container-tujuh .partner ul{
	width: 80%;
	display: flex;
	flex-direction: row;
	justify-content: space-between;
	/background-color: red;
	align-items: center;
	list-style: none;
}
.partner ul a{
	width: 25%;
	/background-color: royalblue;

}
.container-delapan{
	padding: 30px 0 40px 0;
	width: 80%;
	margin: auto;
	/background-color: yellow;
	display: flex;
	justify-content: space-around;
}
.word-satu .mainn h2{
	font-size: 30px;
	padding: 0 0 20px 0;
}
.word-satu .mainn p{
	padding: 10px 0;
} 
.word-satu .input input{
	width: 90%;
	height: 30px;
	border-radius: 15px;
	border: 0;
	box-shadow: 0 0 3px black;
}
.word-satu .input button{
	padding: 8px;
	background-color:  #3EBB86;
	color: white;
	border: 0;
	border-radius: 15px;
	box-shadow: 0 0 3px black;
	margin-left: -40px;
}  
.container-delapan .word-satu{
	width: 25%;
	/background-color: red;/
}
.container-delapan .word{
	width: 15%;
	/background-color: red;/
	text-align: center;
	height: 170px;
}
.container-delapan .word a{
	text-decoration: none;
	color: black;
}
.container-delapan .word p{

	padding: 5px 0
}
.container-lima .teksSatu{
	display: flex;
	flex-direction: column;
}
.teksSatu .hero-satu{
	width: 100%;
	/*/background-color: red;/*/
	display: flex;
	justify-content: space-between;
}
.hero-satu .hero{
	height: 100px;
	width: 50%;
}
.hero i{
	padding: 10px;
}
/* Footer */

footer {
  font-weight: 300;
  display: flex;
  justify-content: space-evenly;
  padding: 2rem;
  background: var(--main-gray);
  border-top: 4px solid var(--main-red);
}

footer > p {
  margin: 2rem;
}

footer i {
  vertical-align: middle;
}

@media (max-width: 28.75em) {
  footer {
    flex-direction: column;
    text-align: center;
  }
}

