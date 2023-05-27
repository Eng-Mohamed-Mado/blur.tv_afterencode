/*----------------------------------------
Project:	Blur.TV HTML Template

Devloper:	Hady Rabie - Mohamed Salah
----------------------------------------*/
/*----------------------------------------
[Table of contents]

1. Fonts
2. Common styles
3. Theme Dark & light
4. Navbar
5. Aside
6. Footer
7. Loading



/*============== Fonts ==============*/
@import url(//db.onlinewebfonts.com/c/153445a28aa0ff5caa797611f4d019fa?family=strangferfixcs);
@import url(//db.onlinewebfonts.com/c/7712e50ecac759e968ac145c0c4a6d33?family=Droid+Arabic+Kufi);
/*================================== */


/*==============================
	Common styles
==============================*/

*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
svg{cursor:pointer !important;}
a {text-decoration: none;}
audio{display: none}
ul{
	margin: 0 !important;
	list-style: none!important;
}
/* Custom Scroll */
::-webkit-scrollbar {
	width: 5px;
	z-index:2000000
  }
::-webkit-scrollbar-track {
	background: #f1f1f15c;
	z-index:2000000
}
::-webkit-scrollbar-thumb {
	background: #130e43d8;
	border-radius: 50px;
	min-height:350px;
	z-index:2000000
}
/*==============================
Theme Dark & light
==============================*/
:root{
	--lightMode: #EEE;
	--darkMode: rgba(9,18,32,1);
	--yellow: orange;
	--red: #0051ff;
	--blue-red: #FF0000;
	--red-blue: #0051ff;
	--blue-white: #eeeeee;
	--mov: #4b4b4f;
	--blue: #eeeeee;
	--blue2: #EEE;
	--blue3: #0051ff;
	--aside: #ffffff;
	--head: #091226;
	--yellow-blue: #0f1a32;
	--gray-blue: #3C4B57;
	--underline: #00000042;
	--opacity: rgba(233, 233, 233, 0.544);
	--opacity1:#eeeeee;
	--opacity2:#ffd4d645;
	--opacity3:#f0edff00;
	--blue-gray-blue: #3C4B57;
	--bg-gradient:rgba(0, 45, 107, 0);
	--btn-blur2: #eeeeeeb6;
	--btn-blur:#eeeeeeb4;
}

html[data-theme="lightMode"]{
	--darkMode: #EEE;
	--lightMode: rgba(9,18,32,1);
	--yellow: #f9ab00;
	--red-blue: #FF0000;
	--blue-red: #0051ff;
	--red: #FF0000;
	--blue-white: #0B1538;
	--head: #09122600;
	--yellow-blue: #f9ab00;
	--mov: #111C5F;
	--blue: #0B1538;
	--blue2: rgba(9,18,32,1);
	--blue3: #091226;
	--aside: #0b1538d1;
	--gray-blue: #091226;
	--gray: #35363a00;
	--underline: #eeeeee42;
	--opacity:rgba(9, 18, 32, 0.895);
	--opacity1: rgba(9,18,32,1);
	--opacity2: rgba(0,0,0,0.6980042016806722);
	--blue-gray-blue: #091226;
	--opacity3: rgba(0,0,0,0);
	--bg-gradient:rgba(0, 44, 107, 0.62);
	--btn-blur:rgba(9,18,32,1);
	--btn-blur2:rgba(9,18,32,1);
}
html,body{
	background: var(--lightMode);
	color: var(--darkMode);
	font-family: 'Source Sans Pro', 'Droid Arabic Kufi', sans-serif;
	overflow-x: hidden;
	font-weight: 400;		
	transition: all .5s ease;
	font-weight: normal;	
}


/*==============================
Navbar
==============================*/
nav {
	width: 100%;
	height: 70px;
	position: fixed;
	background: var(--blue2);
	padding-top: 10px;
	transition: all 1s;
	z-index: 200;
}
nav .container-custom{
	display: flex;
	justify-content: space-between;
	align-items: center;
}
/*...... logo .......*/
.logo{
	width: 150px;
	font-family: sans-serif;
	font-size: 30px;
	font-weight: bolder;
	color: var(--darkMode)!important;
}
.logo span{
	color: var(--yellow)!important;
}
/*...... End logo .......*/

/*......  tools nsv .......*/
nav .toolsNav{
	width: 70%;
	max-width: 500px;
	z-index: 9;
}
nav .toolsNav .item-nav{
	color: var(--darkMode);
	display: flex;
	justify-content: space-around;
}
nav .item-nav li a{
	transition: all .2s ease-in;
	color: var(--darkMode);
}
nav .item-nav li:hover .hvr {
	border-bottom: 3px solid var(--yellow);
	color: var(--darkMode);
}
.activeNavBar{
	border-bottom: 3px solid #94ff52;
	color: #c6c0c0;
}
nav .item-nav li:hover a {
	color: var(--darkMode);
}
nav .item-nav li:hover .dropdownList {
	display: block;
}
.item-nav li .dropdownList {
	transition: all 2s ease-in-out;
	position: absolute;
	top: 25px;
	right: -55px;
	width: 160px;
	border-bottom-left-radius: 10px;
	border-bottom-right-radius: 10px;
	background: var(--blue-white);
	color: var(--darkMode)!important;
	display: none;
	overflow: hidden;
}
.item-nav li .dropdownList a{
	display: block;
    padding: 15px 0px 15px 10px;
    transition: all .3s ease;
}
.item-nav li .dropdownList a:hover{
	color: var(--darkMode)!important;
    background: #cfcfcf68;
}
/* icons navbar */
nav .iconsnav{
	width: 213px;
	display: inline-flex;
	align-items: center;
	justify-content: flex-end;
}
nav .iconsnav .icon{
	list-style: none;
	color: var(--darkMode);
	display: flex;
	justify-content: space-around;
	margin: auto;
}
button{
	background: none;
	color: var(--darkMode);
	border: none;
}
.icon svg{
	text-shadow: 1px 1px 12px #d1c3fb;
	font-size: #f00;
}
.icon svg:hover{
	color: var(--btn-yellow);
}
/* User */
.nav-user{
	height: 30px;
	width: 30px;
	overflow: hidden;
    border-radius: 50px;
}
.nav-user img{
	height: 100%;
	width: 100%;
    border-radius: 50px;
}
/* Search */
#sectionSearch {
	display: none;
	width: 100%;
	height: 100%;
	backdrop-filter: blur(10px);
	background: var(--opacity);
	color: var(--darkMode);
	position: fixed;
	top: 0;
	right: 0;
	padding-top: 5%;
	z-index: 100000;
}
.sectionSearch {
	display: flex;
	justify-content: center;
	align-items: flex-start;
}
#sectionSearch form{
	width: auto;
	height: 40px;
	display: inline-flex;
	justify-content: flex-start;
	align-items: center;
	background: var(--blue);
	border-radius: 5px;
	box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
	transition: all .5s ease;
}
#sectionSearch form input{
	min-width: 340px;
	max-width: 500px;
	padding-left: 15px;
	padding-right: 15px;
	color: var(--darkMode)!important;
	background: none;
	outline: none;
	border: none;
}
#sectionSearch form:hover{
	border:1px solid #fbff0032;
	box-shadow:  2px 2px 22px rgba(83, 47, 114, 0.593);    
	background: var(--mov);
}
#sectionSearch form svg{
	transition: all .5s ease;
	padding: 10px 15px;
	font-size: 22px;
	border-radius: 5px;
	color: var(--darkMode) !important;
}
#sectionSearch form:hover svg{
	color: #eeeeee !important;
}
#sectionSearch form svg:hover{
	color: #0b1537 !important;
	background: #909090;
}
#sectionSearch form svg:active{
	background: #83d80b;
}	
/*==============================
	End Navbar
==============================*/


/*==============================
	aside
==============================*/
aside{
	position: fixed;
	top: 0;
	right: 0;
	width: 0px;
	max-width: 100%;
	height: 100%;
	overflow-y: auto !important;
	backdrop-filter: blur(10px);
	background: var(--aside);
	z-index: 300;
	transition: width 1s ease;
}
/* Custom Scroll */
aside::-webkit-scrollbar {
	width: 0px;
  }
aside::-webkit-scrollbar-track {
	background: #f1f1f15c;
}
aside::-webkit-scrollbar-thumb {
	height:0px;
}
aside .head{
	padding: 20px;
}
.btnfixed{
	height: 160px;
    position: absolute;
    right: 30px;
    top: 110px;
    display: flex !important;
    flex-direction: column;
    align-items: center;
}
aside .userAside{ 
	font-size: 20px!important;
    color: var(--darkMode);
}
aside .userAside span{ 
	font-size: 20px!important;
    color: var(--darkMode);
    background: var(--lightMode);
    border-radius: 10px;
    padding: 10px;
	margin-right: 10px;
}
aside ul{
	padding: 0px;
}
aside .listItem, #btn-movies{
	padding: 20px 40px;
    color: var(--darkMode);
    font-size: 16px;
}
aside .listItem:hover{
	background: linear-gradient(90deg, rgb(0, 213, 255) 1%, rgba(0,154,255,0) 1%, rgba(0, 255, 242, 0.075) 1%);
}
aside .active{
    border-left: 4px solid #009aff !important;
}
/* dropdown Aside */
aside .dropMovie, .dropSeries{
	padding: 20px 0px 10px 50px !important;
	font-size: 17px!important;
	transition: all .5s ease;
	display: none;
}
aside a{color: var(--darkMode);}
/*==============================
	End aside
==============================*/

/*==============================
	section View Trailer
==============================*/
#bubbleTrailer {
	position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    margin: 0;
    display: none;
    background: hsl(0deg 0% 0% / 64%);
    z-index: 10000000;
    justify-content: center;
    align-items: center;

}
.sectionTrailer{
	border-top: 2px solid #eeeeee2b;
    border-radius: 10px;
    height: auto;
    width: 70%;
    min-width: 300px;
    padding: 10px 10px 40px;
}
iframe{
	width: 100%;
	border-radius:15px 15px 0  0 ;
}
/*==============================
	End
==============================*/


/*==============================
	Footer
==============================*/
.footer {
	margin-top:30px;
	background-color:  var(--blue);
}
.footer__content {
display: flex;
flex-direction: column;
justify-content: flex-start;
align-items: flex-start;
padding: 50px 0 30px;
position: relative;
}
.footer__logo {
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
width: 120px;
order: 1;
}
.footer__logo img {
width: 100%;
display: block;
}
.footer__nav {
background:  var(--blue);
order: 2;
display: flex;
flex-direction: flex-start;
margin-top: 30px;
align-items: center;
justify-content: flex-start;
}
.footer__nav a {
font-size: 14px;
color: var(--darkMode);
margin-right: 20px;
}
.footer__nav a:last-child {
margin-right: 0;
}
.footer__nav a:hover {
color: #f9ab00;
}
.footer__copyright {
display: inline-block;
order: 3;
width: 330px;
margin-top: 50px;
font-size: 12px;
line-height: 16px;
color: var(--darkMode);
letter-spacing: 0.4px;
}
.footer__copyright a {
color: #f9ab00;
}
.footer__copyright a:hover {
color: #f9ab00;
text-decoration: underline;
}
.footer__back {
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
width: 40px;
height: 40px;
border: 2px solid #8900f9;
color: var(--darkMode);
position: absolute;
right: 0;
bottom: 30px;
border-radius: 6px;
font-size: 26px;
}
.footer__back:hover {
color: #8900f9;
}
  @media (min-width: 768px) {
	.footer__content {
	  flex-direction: row;
	  justify-content: flex-start;
	  align-items: center;
	  padding: 0;
	  height: 80px;
	}
	.footer__nav {
	  order: 3;
	  margin-top: 0;
	  margin-left: auto;
	  margin-right: 80px;
	  justify-content: flex-end;
	}
	.footer__nav a {
	  margin-right: 30px;
	}
	.footer__nav a:last-child {
	  margin-right: 0;
	}
	.footer__copyright {
	  order: 2;
	  margin-top: 0;
	  margin-left: 30px;
	}
	.footer__back {
	  position: absolute;
	  bottom: 50%;
	  margin-bottom: -20px;
	}
  }
  @media (min-width: 1200px) {
	.footer__copyright {
	  margin-left: 40px;
	}
	.footer__nav a {
	  margin-right: 40px;
	}
	.footer__nav a:last-child {
	  margin-right: 0;
	}
  }
  @media (min-width: 1440px) {
	.footer__copyright {
	  margin-left: 50px;
	}
	.footer__nav {
	  margin-right: 95px;
	}
	.footer__nav a {
	  margin-right: 50px;
	}
	.footer__nav a:last-child {
	  margin-right: 0;
	}
  }
/*==============================
	End Footer
==============================*/


/*==============================
	Start Loading
==============================*/
.load{
	background-image: radial-gradient(circle farthest-corner at center, var(--blue-gray-blue) 0%, #1C262B 100%);
	position: fixed;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	display: -webkit-box;
	display: flex;
	align-items: center;
	justify-content: center;
	opacity: 1;
	visibility: visible;
	z-index: 9999;
	-webkit-transition: opacity 0.25s ease;
	transition: opacity 0.25s ease;
}
.load .logo{
	text-shadow: 1px 1px 12px #d1c3fb;
    font-size: 38px;
	-webkit-box-reflect: below -20px linear-gradient(transparent, transparent, #0005);
}
.loader {
	display: flex;
    width: 300px;
    height: 300px;
    border-radius: 50%;
    perspective: 800px;
    align-items: center;
    justify-content: center;
}
@media (max-width: 380px) {
	.loader {
	display: flex;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    perspective: 800px;
    align-items: center;
    justify-content: center;
}
}
.loaded {
	display: none;
    opacity: 0;
    visibility: hidden;
    pointer-events: none;
}
.inner {
position: absolute;
box-sizing: border-box;
width: 100%;
height: 100%;
border-radius: 50%;    
}
.inner.one {
left: 0%;
top: 0%;
animation: rotate-one 1.2s linear infinite;
border-bottom: 3px solid #fcfaff;

}
.inner.two {
right: 0%;
top: 0%;
animation: rotate-two 1.2s linear infinite;
border-right: 3px solid #fcfaff;

}
.inner.three {
right: 0%;
bottom: 0%;
animation: rotate-three 1.2s linear infinite;
border-top: 3px solid #fcfaff;
}
@keyframes rotate-one {
0% {
	transform: rotateX(35deg) rotateY(-45deg) rotateZ(0deg);
}
100% {
	transform: rotateX(35deg) rotateY(-45deg) rotateZ(360deg);
}
}
@keyframes rotate-two {
0% {
	transform: rotateX(50deg) rotateY(10deg) rotateZ(0deg);
}
100% {
	transform: rotateX(50deg) rotateY(10deg) rotateZ(360deg);
}
}
@keyframes rotate-three {
0% {
	transform: rotateX(35deg) rotateY(55deg) rotateZ(0deg);
}
100% {
	transform: rotateX(35deg) rotateY(55deg) rotateZ(360deg);
}
}
/*==============================
	End Loading
==============================*/
@media (max-width: 450px) {
	/* search */
	#sectionSearch form input{
		min-width: auto;
		max-width: auto;
		width: 90%;
	}
	#sectionSearch form{
		margin: auto 20px;
	}
}