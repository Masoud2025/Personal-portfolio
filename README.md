به وب سایت مسعود جعفری خوش آمد<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css" />
    <!-- add font [google font] -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Silkscreen&display=swap"
      rel="stylesheet"
    />
    <link
      rel="shortcut icon"
      type="image/x-icon"
      href="/front-end/Masoud-portfilio/images/layout/bg.png"
    />
    <link rel="stylesheet" type="text/css" href="css/style.css" />
    <style>
        body {
  font-size: 13px;
  line-height: 18px;
  text-shadow: 0 1px 0 rgba(255, 255, 255, 0.5);
  color: #3e3d3b;
}
.leftside {
  margin-top: -74cm;
  margin-left: -4cm;
}
div#navi div.rightside {
  background: url("../images/layout/subnav_bg2.png") repeat-x;
}

/*------------------Map-----------------------*/
#infografik {
  width: 731px;

  margin: 0 auto;
  padding: 0 0 0 89px;
}

#infografik .leftside {
  width: 164px;
  float: left;
}
#infografik .leftside .gehirndesign,
#infografik .leftside .gehirncoding,
#infografik .leftside .gehirnspiele {
  width: 100%; /* 130px */
  padding: 7px 12px;
  margin: 0;

  background: url("../images/layout/gehirn_links_hover.png") no-repeat 0 500px;
}
#infografik .leftside .gehirndesign.aktivkat {
  background-position: 0 0;
}
#infografik .leftside .gehirncoding.aktivkat {
  background-position: 0 -191px;
}
#infografik .leftside .gehirnspiele.aktivkat {
  background-position: 0 -337px;
}
#infografik .leftside table {
  width: 100%;
}

#infografik .leftside table th {
  line-height: 22px;
  text-align: center;
  font-size: 16px;
  font-weight: bold;
  text-transform: uppercase;
  cursor: default;
}

#infografik .leftside table td {
  /*padding: 3px 0;*/
  line-height: 22px;
  text-align: center;
  cursor: default;
}

#infografik .leftside table td.aktivtd {
  font-weight: bolder;
  color: #3e3d3b;
}

#infografik .rightside {
  width: 502px;
  height: 401px;
  overflow: hidden;
  position: absolute;
  top: 158%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: url("../images/layout/gehirn_sprite.png") no-repeat;
}

/* Design */
#infografik .rightside.desi,
#infografik .rightside.ps,
#infografik .rightside.ai,
#infografik .rightside.ind,
#infografik .rightside.fla,
#infografik .rightside.fw,
#infografik .rightside.pp,
#infografik .rightside.ae {
  background-position: 0 -802px;
}
/* Coding */
#infografik .rightside.cod,
#infografik .rightside.ht,
#infografik .rightside.cs,
#infografik .rightside.jas,
#infografik .rightside.php,
#infografik .rightside.actsc {
  background-position: 0 -401px;
}

#maphover {
  position: absolute;
  top: 0;
  left: 0;

  background: url("../images/layout/gehirn_hover.png") no-repeat;
}
/* Design */
#maphover.ps {
  left: 86px;
  top: 0;
  width: 329px;
  height: 210px;
  background-position: 0 0;
}
#maphover.ai {
  left: 111px;
  top: 142px;
  width: 243px;
  height: 178px;
  background-position: 0 -210px;
}
#maphover.ind {
  left: 243px;
  top: 45px;
  width: 260px;
  height: 183px;
  background-position: 0 -388px;
}
#maphover.fla {
  left: 396px;
  top: 141px;
  width: 101px;
  height: 119px;
  background-position: 0 -571px;
}
#maphover.fw {
  left: 275px;
  top: 199px;
  width: 138px;
  height: 72px;
  background-position: -191px -571px;
}
#maphover.pp {
  left: 280px;
  top: 161px;
  width: 126px;
  height: 70px;
  background-position: 0 -690px;
}
#maphover.ae {
  left: 349px;
  top: 104px;
  width: 115px;
  height: 80px;
  background-position: -214px -690px;
}
/* Coding */
#maphover.ht {
  left: 44px;
  top: 55px;
  width: 124px;
  height: 182px;
  background-position: 0 -906px;
}
#maphover.cs {
  left: 28px;
  top: 130px;
  width: 103px;
  height: 120px;
  background-position: -226px -906px;
}
#maphover.jas {
  left: 1px;
  top: 123px;
  width: 119px;
  height: 140px;
  background-position: 0 -1088px;
}
#maphover.php {
  left: 11px;
  top: 45px;
  width: 114px;
  height: 125px;
  background-position: -214px -1088px;
}
#maphover.actsc {
  left: 8px;
  top: 45px;
  width: 85px;
  height: 86px;
  background-position: -131px -906px;
}
/* Spiele */
#maphover.snes {
  left: 271px;
  top: 245px;
  width: 182px;
  height: 70px;
  background-position: 0 -770px;
}
#maphover.wii {
  left: 324px;
  top: 256px;
  width: 132px;
  height: 77px;
  background-position: -197px -770px;
}
#maphover.nds {
  left: 317px;
  top: 311px;
  width: 122px;
  height: 45px;
  background-position: 0 -847px;
}
#maphover.playst {
  left: 301px;
  top: 311px;
  width: 115px;
  height: 53px;
  background-position: -214px -847px;
}
#maphover.sonst {
  left: 276px;
  top: 303px;
  width: 69px;
  height: 59px;
  background-position: -133px -847px;
}

#infografik .rightside .map {
  position: absolute;
  top: 0;
  left: 0;

  width: 502px;
  height: 401px;
}

.tooltip {
  position: absolute;

  padding: 0 10px;

  min-width: 80px;

  -webkit-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.4);
  -moz-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.4);
  -o-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.4);
  -ie-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.4);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.4);

  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  -o-border-radius: 3px;
  -ie-border-radius: 3px;
  border-radius: 3px;

  line-height: 26px;
  text-align: center;

  background: #fff;
  background-image: -webkit-gradient(
    linear,
    left bottom,
    left top,
    color-stop(0, rgb(230, 230, 230)),
    color-stop(1, rgb(255, 255, 255))
  );
  background-image: -moz-linear-gradient(
    center bottom,
    rgb(230, 230, 230) 0%,
    rgb(255, 255, 255) 100%
  );
}
.tooltip:before {
  content: "";
  position: absolute;
  top: -6px;
  left: 50%;

  margin: 0 0 0 -5px;

  width: 10px;
  height: 6px;

  background: url("../images/layout/tooltip_spitze.png") no-repeat;
}
      html {
  scroll-behavior: smooth !important;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background: url("Capture.PNG");
  font-family: "Silkscreen", sans-serif;
  color: #eee;
  height: 100vh;
  overflow-x: hidden;
}
.topnav {
  overflow: hidden;
}

.topnav a {
  float: right;
  color: #e6db74;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  margin: 1em;
}

.topnav a:hover {
  color: #7e2eff;
}

/* Create a right-aligned (split) link inside the navigation bar */
.topnav a.split {
  float: left;
  color: white;
  margin-left: 4em;
}
/* names should be better  */
.subname {
  font-size: 14px;
}
.about-me {
  text-align: center;
  margin-top: 4em;
  color: whitesmoke;
  font-size: 3em;
}
/*  */
/* typing animation  */

.wrapper {
  height: 100vh;
  /*This part is important for centering*/
  display: grid;
  place-items: center;
  margin-top: -20em;
}

.typing-demo {
  width: 21ch;
  animation: typing 2s steps(22), blink 0.5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-size: 4em;
  color: #e6db74;
  text-transform: uppercase;
  height: 1em;
}

@keyframes typing {
  from {
    width: 0;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}

/*  */
.vl {
  border-left: 1px solid rgb(99, 100, 99);
  height: 10000px;
  margin-left: 4em;
  margin-top: -90em;
  width: 0.1cm;
}
/*  */
.te {
  color: whitesmoke;
  display: grid;
  place-content: center;
  margin-top: -12em;
  font-size: 2em;
}
/*  */
/* about me  */
.about__me h1 {
  text-align: center;
  margin-top: -5em;
}
/*  */
/* grid container  */
.container {
  margin-top: 50em;
  width: 100%;
  height: 100vh;
  text-align: center;
}
[class*="sec-"] {
  color: black;
  border: solid yellow;
  width: 100%;
  margin-top: 10em;
}

/*  */
/* Table */
.tg {
  border-collapse: collapse;
  border-spacing: 0;
  margin: 0px auto;
}
.tg td {
  border-color: black;
  border-style: solid;
  border-width: 1px;
  font-family: Arial, sans-serif;
  font-size: 14px;
  overflow: hidden;
  padding: 20px 20px;
  word-break: normal;
}
.tg th {
  border-color: black;
  border-style: solid;
  border-width: 1px;
  font-family: Arial, sans-serif;
  font-size: 14px;
  font-weight: normal;
  overflow: hidden;
  padding: 20px 20px;
  word-break: normal;
}
.tg .tg-6t95 {
  font-weight: bold;
  position: sticky;
  text-align: center;
  top: -1px;
  vertical-align: top;
  will-change: transform;
}
.tg .tg-amwm {
  font-weight: bold;
  text-align: center;
  vertical-align: top;
}
@media screen and (max-width: 767px) {
  .tg {
    width: auto !important;
  }
  .tg col {
    width: auto !important;
  }
  .tg-wrap {
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    margin: auto 0px;
  }
}
/*  */
/* Footer */

ul {
  position: absolute;
  top: 75%;
  left: 49%;
  transform: translate(-50%, -50%);
  display: flex;
  margin: 0;
  padding: 0;
  height: 1em;
}

ul li {
  list-style: none;
  margin: 0 5px;
}

ul li a .fa {
  font-size: 40px;
  color: #262626;
  line-height: 80px;
  transition: 0.5s;
  padding-right: 14px;
}

ul li a span {
  padding: 0;
  margin: 0;
  position: absolute;
  top: 30px;
  color: #262626;
  letter-spacing: 4px;
  transition: 0.5s;
}

ul li a {
  text-decoration: none;
  display: absolute;
  display: block;
  width: 210px;
  height: 80px;
  background: #fff;
  text-align: left;
  padding-left: 20px;
  transform: rotate(-30deg) skew(25deg) translate(0, 0);
  transition: 0.5s;
  box-shadow: -20px 20px 10px rgba(0, 0, 0, 0.5);
}
ul li a:before {
  content: "";
  position: absolute;
  top: 10px;
  left: -20px;
  height: 100%;
  width: 20px;
  background: #b1b1b1;
  transform: 0.5s;
  transform: rotate(0deg) skewY(-45deg);
}
ul li a:after {
  content: "";
  position: absolute;
  bottom: -20px;
  left: -10px;
  height: 20px;
  width: 100%;
  background: #b1b1b1;
  transform: 0.5s;
  transform: rotate(0deg) skewX(-45deg);
}

ul li a:hover {
  transform: rotate(-30deg) skew(25deg) translate(20px, -15px);
  box-shadow: -50px 50px 50px rgba(0, 0, 0, 0.5);
}

ul li:hover .fa {
  color: #fff;
}

ul li:hover span {
  color: #fff;
}

ul li:hover:nth-child(1) a {
  background: #3b5998;
}
ul li:hover:nth-child(1) a:before {
  background: #365492;
}
ul li:hover:nth-child(1) a:after {
  background: #4a69ad;
}

ul li:hover:nth-child(2) a {
  background: #00aced;
}
ul li:hover:nth-child(2) a:before {
  background: #097aa5;
}
ul li:hover:nth-child(2) a:after {
  background: #53b9e0;
}

ul li:hover:nth-child(3) a {
  background: #dd4b39;
}
ul li:hover:nth-child(3) a:before {
  background: #b33a2b;
}
ul li:hover:nth-child(3) a:after {
  background: #e66a5a;
}

ul li:hover:nth-child(4) a {
  background: #e4405f;
}
ul li:hover:nth-child(4) a:before {
  background: #d81c3f;
}
ul li:hover:nth-child(4) a:after {
  background: #e46880;
}
/*  */

/* contact me */
.card {
  width: 70%;
  padding: 30px 90px 90px 90px;
  border: 6px solid rgba(0, 0, 0, 0.3);
  box-shadow: 20px 20px 0 rgba(0, 0, 0, 0.3);
  border-radius: 50px;
  position: relative;
  margin-left: 20em;
  margin-top: -1em;
}

.card h2 {
  color: rgba(0, 0, 0, 0.3);
  font-size: 60px;
  text-transform: uppercase;
}

.card .row {
  position: relative;
  width: 100%;
  display: grid;
  grid: auto / auto auto;
  grid-template-columns: repeat(auto-fit, minmax(40%, 1fr));
  grid-gap: 30px;
}

.card .row .col {
  position: relative;
  width: 100%;
  margin: 30px 20px 40px 0;
  transition: 0.5s;
}

.card .row .form-group {
  position: relative;
  width: 100%;
  height: 40px;
  color: #ffffff;
}

.card .row .form-group input,
.card .row .form-group textarea {
  position: absolute;
  width: 90%;
  height: 100%;
  background: transparent;
  outline: none;
  font-size: 24px;
  padding: 10px 0 10px 20px;
  border: 5px solid rgba(0, 0, 0, 0.3);
  box-shadow: 10px 10px 0 rgba(0, 0, 0, 0.3);
  color: #ffffff;
  border-radius: 50px;
}

.card .row .form-group label {
  line-height: 40px;
  color: #ffffff;
  font-size: 24px;
  margin: 0 0 0 30px;
  display: block;
  pointer-events: none;
}

.row .col:nth-child(6) {
  margin-top: 64px;
}

.card .row .form-group input:focus,
.card .row .form-group textarea:focus {
  border: 5px solid #ffffff;
  transition: all 0.5s;
}

.card .row input[type="submit"] {
  border: 5px solid rgba(0, 0, 0, 0.3);
  box-shadow: 10px 10px 0 rgba(0, 0, 0, 0.3);
  padding: 10px;
  height: 100%;
  width: 50%;
  cursor: pointer;
  outline: none;
  background: transparent;
  text-transform: uppercase;
  color: #ffffff;
  line-height: 40px;
  font-size: 24px;
  font-weight: 700;
  border-radius: 45px;
  transition: all 0.4s;
}

.card .row input[type="submit"]:hover {
  border: 5px solid rgba(255, 255, 255, 1);
  color: #ffffff;
  transition: all 0.4s;
}

@media screen and (max-width: 900px) {
  .card .row {
    grid-template-columns: repeat(auto-fit, minmax(70%, 1fr));
  }

  .card {
    padding: 20px;
  }

  .card h2 {
    font-size: 34px;
  }

  .card .row input[type="submit"] {
    width: 100%;
  }
}
/*  */
/* maping image */
.skills {
  margin-left: 57em;
  text-align: center;
  margin-top: -490em;
  padding-bottom: 4em;
}
.skills img {
  width: 50em;
}
#yu {
  background-color: red;
}
.item1:hover {
  background-color: #d81c3f;
}
.item2:hover {
  background-color: #3821ff;
}
.item3:hover {
  background-color: #ffee07;
}
.item4:hover {
  background-color: #42d81c;
}
.item5:hover {
  background-color: #975bf7;
}
.item6:hover {
  background-color: #ec17ff;
}
.item7:hover {
  background-color: #e5ff00;
}
.item8:hover {
  background-color: #00ffea;
}

/*  */

.parent {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(2, 1fr);
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  border: solid black;
  width: 100%;
  height: 100vh;
  font-size: 2em;
}

.div1 {
  border: solid yellowgreen;
  grid-area: 1 / 2 / 2 / 3;
}
.div2 {
  border: solid yellowgreen;
  grid-area: 1 / 1 / 2 / 2;
}
.div3 {
  border: solid yellowgreen;
  grid-area: 2 / 1 / 3 / 2;
}
.div4 {
  border: solid yellowgreen;
  grid-area: 2 / 2 / 3 / 3;
}

/*  */
#gl {
  color: white;
  clip-path: polygon(25% 0%, 54% 29%, 100% 50%, 65% 55%, 29% 52%, 17% 25%);
  /* background-color: whitesmoke; */
  height: 50em;
  position: relative;
  top: -35em;
  left: -2em;
  opacity: 0.1;
}
#gl:hover {
  /* background-color: #3821ff; */
  cursor: pointer;
  transition: 0.5s;
  opacity: 0.5;
}
#a1 {
  background-color: red;
  overflow: hidden;
  font-size: 4em;
  border-radius: 16px;
  position: relative;
  top: -35cm;
  left: -18cm;
  display: none;
  transition: 3s;
}

.dark-mode {
  background: url(gray.PNG);
  color: black;
}
#toggle-dali {
  position: relative;
  top: -12.5cm;
  left: 14cm;
  border-radius: 2em;
}
#gl:hover + #a1 {
  display: block;
}
.gl1 {
  clip-path: polygon(21% 16%, 51% 43%, 28% 60%, 0% 50%);
  position: relative;
  top: -98em;
  left: 20em;
  opacity: 0.1;
  height: 40em;
}
.gl1:hover {
  /* background-color: gold; */
  cursor: pointer;
  transition: 0.5s;
  opacity: 0.5;
}
.gl1:hover + #a2 {
  display: block;
}
#a2 {
  background-color: blue;
  overflow: hidden;
  font-size: 4em;
  border-radius: 16px;
  position: relative;
  top: -50cm;
  left: -18cm;
  top: 12em;

  display: none;
  transition: 3s;
}
.skl {
  color: whitesmoke;
  margin-top: 100em;
  position: relative;
  top: 12em;

  left: 14em;
  font-size: 3em;
}
.about__section {
  position: relative;
  top: -42cm;
  left: 14cm;
  width: 25cm;
  height: 14cm;
  border: solid red;
  border-radius: 80px;
  color: white;
  text-align: left;
}
.about__section img {
  position: relative;
  left: -2.5cm;
  top: -1cm;
}
.about__section p {
  position: relative;
  top: -10cm;
  left: 11cm;
  width: 10cm;
  font-style: oblique;
  font-weight: bolder;
}
.about__section h1 {
  position: relative;
  left: 11cm;
  top: 2cm;
}
.contact__me {
  position: relative;
  left: 17cm;
  top: 2cm;
  width: 20%;
  display: flex;
  clear: both;
}
h4 {
  color: whitesmoke;
}
.icons {
  width: 40px;
  height: 40px;
}
#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: red;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #555;
}
/* card layout */
#projects {
  position: relative;
  left: 13cm;
  top: -37cm;
  color: whitesmoke;
  font-size: 3em;
}
.angry-grid {
  display: grid;
  grid-template: 5fr 5fr 5fr / 16fr 16fr 16fr;
  gap: 0px;
  height: 100%;
  position: relative;
  left: 0cm;
  top: -37cm;
  width: 43cm;
  height: 36cm;
}
.angry-grid:hover {
  cursor: pointer;
}
#item-0 {
  background-color: #c68fe9;
  grid-row: 1 / 2;
  grid-column: 3 / 4;
}
#item-1 {
  background-color: #5bbb7b;
  grid-row: 1 / 2;
  grid-column: 2 / 3;
}
#item-2 {
  background-color: #d85578;
  grid-row: 1 / 2;
  grid-column: 1 / 2;
}
#item-3 {
  background-color: #6bebbd;
  grid-row: 2 / 3;
  grid-column: 2 / 3;
}
#item-4 {
  background-color: #979695;
  grid-row: 2 / 3;
  grid-column: 1 / 2;
}
#item-5 {
  background-color: #ade9a6;
  grid-row: 2 / 3;
  grid-column: 3 / 4;
}
#item-6 {
  background-color: #7cebd7;
  grid-row: 3 / 4;
  grid-column: 2 / 3;
}
#item-7 {
  background-color: #99c656;
  grid-row: 3 / 4;
  grid-column: 1 / 2;
}
#item-8 {
  background-color: #c5c88c;
  grid-row: 3 / 4;
  grid-column: 3 / 4;
}

/* card layout end */
@media only screen and (max-width: 500px) {
  ul {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .topnav {
    display: none;
  }
}
@media only screen and (max-width: 767px) {
}
@media only screen and (max-width: 767px) {
}
    </style>
   
  </head>
  <body>
    <div class="topnav">
      <a href="#contact">-contact</a>
      <a href="#about" class="split"
        >//Masoud <br />
        <span class="subname">web-dev</span></a
      >
      <a href="#about">-about</a>
      <a class="active" href="#home">-home</a>
    </div>
    <p class="about-me">//HI my name is Masoud Jafari a...</p>
    <div class="wrapper">
      <div class="typing-demo">{"Front-end developer"}</div>
    </div>
    <span class="te"> &lt;&gt; what drives my work &lt;/&gt; </span>
    <span class="skl">What's in my head ?</span>
    <!-- dark mode light mode -->
    <button id="toggle-dali" onclick="changeThem()">Toggle dark mode</button>
    <div class="vl"></div>
    <div class="skills">
      <div id="infografik">
        <!-- <h1>What's in my head</h1> -->
        <div class="leftside"></div>
        <!-- / leftside -->
        <div class="rightside">
          <div id="maphover"></div>
          <img
            src="images/layout/gehirn_map.gif"
            class="map"
            alt="What's in my head"
            usemap="#gehirn"
            width="502"
            height="401"
          />
        </div>
        <!-- / rightside -->
        <div class="clear"></div>
        <!-- <p class="copytext">* The above shown graphic does not claim correctness in any kind of way.</p> -->
      </div>
      <map name="gehirn">
        <!-- Design -->
        <area
          shape="poly"
          coords="86,56,109,35,126,34,143,22,166,18,179,10,203,7,214,3,232,5,246,0,266,6,285,0,365,20,382,25,400,41,414,54,416,63,403,59,392,58,379,50,355,72,317,65,303,45,274,51,258,80,245,96,240,121,244,141,249,162,225,212,226,180,198,174,179,184,150,203,144,190,146,167,154,137,156,98,167,89,156,70,140,66,124,54,119,55,109,46"
          title="Next js"
          alt="ps"
        />
        <area
          shape="poly"
          coords="111,262,120,250,123,235,152,205,202,174,227,180,225,205,248,163,276,139,289,151,300,141,324,152,355,151,336,172,323,198,301,195,279,200,273,219,289,239,291,245,300,248,322,268,302,278,276,275,234,292,218,303,191,319,155,303,134,301,119,287"
          title="Angular"
          alt="ai"
        />
        <area
          shape="poly"
          coords="250,161,246,151,246,140,242,105,249,84,259,79,275,51,305,46,318,64,354,71,375,54,392,55,398,65,397,79,403,86,404,60,432,77,460,104,459,121,469,124,491,171,490,184,500,193,497,225,487,202,474,187,462,184,465,163,442,123,420,118,409,104,370,129,354,157,350,149,322,153,299,142,290,152,274,142"
          title="RestAPI"
          alt="ind"
        />
        <area
          shape="poly"
          coords="404,248,413,231,394,221,408,159,420,153,432,141,443,160,464,169,463,183,480,188,497,223,469,260,434,245,424,249"
          title="typescript"
          alt="fla"
        />
        <area
          shape="poly"
          coords="322,268,303,251,293,246,291,238,274,224,282,203,304,210,324,230,395,221,415,234,403,246,391,243,377,249,366,259,351,261"
          title="SSR"
          alt="fw"
        />
        <area
          shape="poly"
          coords="284,200,303,195,327,195,332,179,351,159,355,174,374,183,406,174,396,224,370,223,320,229"
          title="Responsive design"
          alt="pp"
        />
        <area
          shape="poly"
          coords="349,162,372,128,411,102,420,119,448,123,465,164,464,172,456,165,443,162,441,148,430,140,406,160,395,179,376,184,354,176"
          title="PWA"
          alt="ae"
        />
        <!-- Coding -->
        <area
          shape="poly"
          coords="121,52,140,63,158,72,168,90,157,97,153,142,141,180,151,204,121,239,112,228,130,209,126,200,93,185,96,167,82,165,72,144,53,132,41,130,45,114,60,104,74,104,68,90,77,76,98,68"
          title="(X)HTML"
          alt="ht"
        />
        <area
          shape="poly"
          coords="122,238,115,230,109,230,131,208,127,198,110,192,95,182,93,166,82,165,74,142,55,128,40,131,38,140,52,152,35,151,28,168,44,190,43,201,63,229,83,230,94,226,100,245,120,250"
          title="CSS"
          alt="cs"
        />
        <area
          shape="poly"
          coords="118,251,97,241,92,228,73,230,60,225,56,213,42,205,42,191,27,169,14,163,10,156,10,151,16,129,8,121,4,132,5,147,0,175,12,185,11,196,37,239,52,247,82,263,113,259"
          title="JavaScript"
          alt="jas"
        />
        <area
          shape="poly"
          coords="30,171,14,164,9,152,16,131,17,119,23,108,26,102,37,98,49,85,54,74,110,44,116,54,96,69,75,78,70,94,74,104,60,102,44,118,44,128,38,137,53,151,36,151,28,159"
          title="React js"
          alt="php"
        />
        <area
          shape="poly"
          coords="18,129,9,123,10,115,24,95,35,78,59,54,70,53,80,43,91,44,84,58,58,73,49,78,52,88,46,87,38,99,24,104,28,120"
          title="ActionScript"
          alt="actsc"
        />
        <!-- Spiel -->
        <area
          shape="poly"
          coords="272,276,274,286,291,318,302,322,316,313,325,314,331,301,345,294,375,279,423,266,442,261,452,258,450,252,433,244,424,249,407,246,387,242,377,250,364,259,352,261,337,268,321,267,300,279"
          title="Super Nintendo"
          alt="snes"
        />
        <area
          shape="poly"
          coords="325,314,330,303,345,288,379,277,453,254,455,277,440,314,424,312,412,311,364,334,333,328"
          title="Wii"
          alt="wii"
        />
        <area
          shape="poly"
          coords="440,315,421,310,411,312,362,333,334,327,323,314,315,318,322,331,356,355,401,343,414,343"
          title="Nintendo DS"
          alt="nds"
        />
        <area
          shape="poly"
          coords="314,312,314,322,349,354,378,350,398,345,381,359,350,364,326,349,304,325,299,312"
          title="PlayStation 2"
          alt="playst"
        />
        <area
          shape="poly"
          coords="287,304,272,310,286,321,295,336,314,351,343,361,313,338,300,323,304,310"
          title="Other"
          alt="sonst"
        />
      </map>
    </div>
    <!--  -->
    <ul>
      <li>
        <a href="">
          <i class="fa fa-facebook" aria-hidden="true"></i>
          <span> - team work</span>
        </a>
      </li>
      <li>
        <a href="">
          <i class="fa fa-twitter" aria-hidden="true"></i>
          <span> - hard work</span>
        </a>
      </li>
      <li>
        <a href="">
          <i class="fa fa-google-plus" aria-hidden="true"></i>
          <span> - innovation</span>
        </a>
      </li>
      <li>
        <a href="">
          <i class="fa fa-instagram" aria-hidden="true"></i>
          <span> - excellence</span>
        </a>
      </li>
    </ul>
    <!--  -->
    <!-- about section -->
    <div class="about__section" id="about">
      <h1>&lt;h1&gt; About me &lt;h1/&gt;</h1>
      <img
        src="../Minimalist-portfilio/photo_2023-12-28_07-29-09-removebg-preview.png"
        alt=""
        srcset=""
      />
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi fugiat
        qui praesentium, obcaecati ratione non dolore rem accusamus ad quaerat!
        Aliquid eaque vero omnis sed facilis aliquam cum maxime atque
        architecto! Amet corrupti sunt rerum sequi nesciunt! Et est itaque in
        necessitatibus rem at. Saepe vel exercitationem porro, ut, dolores quo
        labore sunt, natus modi reprehenderit obcaecati ab? Minima nisi alias
        maiores, fuga provident in. Officiis neque porro error eligendi sit
        repellendus a sunt quaerat libero repudiandae, adipisci iste ut qui
        nemo, aliquid vel eaque asperiores rem molestias? A, eaque?
      </p>
    </div>
    <div class="contact__me" id="contact">
      <a href="https://github.com/Masoud2025" target="_blank">
        <img
          class="icons"
          src="../Minimalist-portfilio/github_919847.png"
          alt="github"
          srcset=""
        />
      </a>
      <a
        href="https://www.linkedin.com/in/masoud-jafari-261ba7213/"
        target="_blank"
      >
        <img
          class="icons"
          src="../Minimalist-portfilio/linkedin_3536569.png"
          alt="linkdin"
          srcset=""
        />
      </a>
      <a
        href="https://stackoverflow.com/users/15087089/masoud "
        target="_blank"
      >
        <img
          class="icons"
          src="../Minimalist-portfilio/stack-overflow_2111806.png"
          alt="stackoverflow"
          srcset=""
        />
      </a>
      <h4>+phone number : 09301561067</h4>
    </div>
    <div class="go__top">
      <button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>
    </div>
    <!--  grid card  layout  -->
    <div class="angry-grid">
      <h2 id="projects">&lt;h1&gt; Projects &lt;h1/&gt;</h2>
      <div id="item-0">&nbsp;</div>
      <div id="item-1">&nbsp;</div>
      <div id="item-2">&nbsp;</div>
      <div id="item-3">&nbsp;</div>
      <div id="item-4">&nbsp;</div>
      <div id="item-5">&nbsp;</div>
      <div id="item-6">&nbsp;</div>
      <div id="item-7">&nbsp;</div>
      <div id="item-8">&nbsp;</div>
    </div>
    <!--  -->
    <script src="logic.js"></script>
    <script
      type="text/javascript"
      src="http://ajax.googleapis.com/ajax/libs/jquery/1.5/jquery.min.js"
    ></script>
    <script type="text/javascript" src="js/jquery.scrollTo.min.js"></script>
    <script type="text/javascript" src="js/jquery.localscroll.min.js"></script>
    <script type="text/javascript">
      function changeThem() {
        var element = document.body;
        element.classList.toggle("dark-mode");
      }
      let mybutton = document.getElementById("myBtn");

      // When the user scrolls down 20px from the top of the document, show the button
      window.onscroll = function () {
        scrollFunction();
      };

      function scrollFunction() {
        if (
          document.body.scrollTop > 20 ||
          document.documentElement.scrollTop > 20
        ) {
          mybutton.style.display = "block";
        } else {
          mybutton.style.display = "none";
        }
      }

      // When the user clicks on the button, scroll to the top of the document
      function topFunction() {
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
      }
    </script>
    <script type="text/javascript" src="js/jquery.hoverintent.min.js"></script>
    <script type="text/javascript">
      $(document).ready(function () {
        var speed = 400;
        $("#gpoy").hoverIntent(
          function () {
            $("#gpoy .hover").animate(
              {
                opacity: 1,
              },
              { queue: false, duration: speed }
            );
            $("#gpoy .normal").animate(
              {
                opacity: 0,
              },
              { queue: false, duration: speed }
            );
          },
          function () {
            $("#gpoy .hover").animate(
              {
                opacity: 0,
              },
              { queue: false, duration: speed }
            );
            $("#gpoy .normal").animate(
              {
                opacity: 1,
              },
              { queue: false, duration: speed }
            );
          }
        );

        var tooltip = $('<div class="tooltip"></div>');
        $("body").append(tooltip);

        $("area")
          .hover(
            function (e) {
              $("#maphover").addClass($(this).attr("alt"));
              $("#infografik .rightside").addClass($(this).attr("alt"));
              $("table ." + $(this).attr("alt")).addClass("aktivtd");
              $("table ." + $(this).attr("alt"))
                .closest("div")
                .addClass("aktivkat");

              /* Tooltip */
              var toolcon = $(this).attr("title");
              $(this).attr("title", "");
              tooltip.html(toolcon);
              $(this).data("titleCon", toolcon);

              var positX = e.pageX;
              var positY = e.pageY;

              positX = positX - tooltip.width / 2 - 4;
              positY += 30;

              tooltip.css({ top: positY, left: positX }).show();
            },
            function () {
              $("#maphover").removeClass($(this).attr("alt"));
              $("#infografik .rightside").removeClass($(this).attr("alt"));
              $("table ." + $(this).attr("alt")).removeClass("aktivtd");
              $("table ." + $(this).attr("alt"))
                .closest("div")
                .removeClass("aktivkat");

              /* Tooltip */
              tooltip.hide();
              $(this).attr("title", $(this).data("titleCon"));
            }
          )
          .mousemove(function (e) {
            var positX = e.pageX;
            var positY = e.pageY;

            positX = positX - tooltip.width() / 2 - 4;
            positY += 30;

            tooltip.css({ top: positY, left: positX });
          });
        $("tr").hover(
          function () {
            var cur = $(this).find("td").attr("class");
            $("#maphover").addClass(cur);
            $("#infografik .rightside").addClass(cur);
            $("table ." + cur).addClass("aktivtd");
            $("table ." + cur)
              .closest("div")
              .addClass("aktivkat");
          },
          function () {
            var cur = $(this).find("td").attr("class").split(" ", 1);
            cur = String(cur);
            $("#maphover").removeClass(cur);
            $("#infografik .rightside").removeClass(cur);
            $("table ." + cur).removeClass("aktivtd");
            $("table ." + cur)
              .closest("div")
              .removeClass("aktivkat");
          }
        );
        $(".gehirndesign, .gehirncoding, .gehirnspiele").hover(
          function () {
            var cur = $(this).find("th").attr("class");
            $("#maphover").addClass(cur);
            $("#infografik .rightside").addClass(cur);
            $("table ." + cur).addClass("aktivtd");
            $("table ." + cur)
              .closest("div")
              .addClass("aktivkat");
          },
          function () {
            var cur = $(this).find("th").attr("class").split(" ", 1);
            cur = String(cur);
            $("#maphover").removeClass(cur);
            $("#infografik .rightside").removeClass(cur);
            $("table ." + cur).removeClass("aktivtd");
            $("table ." + cur)
              .closest("div")
              .removeClass("aktivkat");
          }
        );
      });
    </script>
  </body>
</html>
