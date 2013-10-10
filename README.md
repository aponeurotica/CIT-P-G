CIT-P-G
=======

CIT payment gateway
@import url(http://fonts.googleapis.com/css?family=Source+Sans+Pro:200,400,700,400italic|Fjalla+One);

/* =Global Elements
-------------------------------------------------------------- */
body { 
	font-family: 'Source Sans Pro', sans-serif;
	font-weight: 400;
	font-size: 12px; 
	color:#414141;
	height:100%;
	}
h1 {
	color:#71a81a;
	font-size: 28px;
	letter-spacing: 1px;
	font-weight: normal;
	}
h2 {
	font-family: 'Fjalla One', sans-serif;
	color:#71a81a;
	letter-spacing: 1px;
	font-weight: 400;
	}
h3 {
	font-family: 'Source Sans Pro', sans-serif;
	}
h4, h5 {
	}
a {
	color:#71a81a; 
	outline:none;
	}
a:hover{
	text-decoration:none;
	}
#wrapper {
	margin: 0 auto;
	width: 960px;
	}

/* Header */

#header {
	width: 960px;
	clear: both;
	height: 100px;
	}
h1 {
	display: block;
	float: left;
	width: 129px;
	height: 70px;
	margin: 24px 20px 0 0;
	background:url(../images/cast-it-talent-logo.gif) no-repeat;
	text-indent: -9000px;
	}
h1 a {
	display: block;
	float: left;
	width: 129px;
	height: 70px;
	}
#navigation {
	width: 810px;
	margin-left: 150px;
	border-bottom: 1px solid #ccc;
	height: 60px;
	}
#navigation ul {
	float:right;
	height: 45px;
	padding-top: 30px;
	}
#navigation ul li {
	display: inline;
	font-size:14px;
	margin-left: 28px;
	text-transform: lowercase;
	letter-spacing: 1px;
	font-weight: 700;
	}
#navigation ul li a {
	color:#71a81a;
	text-decoration: none;
	}
#navigation ul li a:hover {
	color:#666;
	}
a.login, button.login {
	display: inline-block;
	text-indent: -9000px;
	background: url(../images/btn-login.jpg) no-repeat;
	width: 95px;
	height: 41px;
	position: relative;
	border:0;
	}
a.login {top: -14px;}
button.login {float: right;cursor: pointer;margin-top: 14px;}

/* modal */

.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #fff;
	}
.modal-backdrop.fade {
  opacity: 0;
}
.modal-backdrop,
.modal-backdrop.fade.in {
  opacity: 0.8;
  filter: alpha(opacity=80);
}
.login-modal {
  position: fixed;
  top: 10%;
  left: 50%;
  z-index: 1050;
  width: 240px;
  margin-left: -120px;
  background-color: #ffffff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.3);
  *border: 1px solid #999;
  -webkit-border-radius: 6px;
     -moz-border-radius: 6px;
          border-radius: 6px;
  outline: none;
  -webkit-box-shadow: 0 3px 7px rgba(0, 0, 0, 0.3);
     -moz-box-shadow: 0 3px 7px rgba(0, 0, 0, 0.3);
          box-shadow: 0 3px 7px rgba(0, 0, 0, 0.3);
  -webkit-background-clip: padding-box;
     -moz-background-clip: padding-box;
          background-clip: padding-box;
	}
.modal.fade {
  top: -25%;
  -webkit-transition: opacity 0.3s linear, top 0.3s ease-out;
     -moz-transition: opacity 0.3s linear, top 0.3s ease-out;
       -o-transition: opacity 0.3s linear, top 0.3s ease-out;
          transition: opacity 0.3s linear, top 0.3s ease-out;
}
.modal.fade.in {
  top: 10%;
}
.modal-header .close {
  margin-top: 2px;
}
.modal-body {
	position: relative;
	max-height: 400px;
	padding: 20px;
	overflow-y: auto;
	}

.modal-form {
  margin-bottom: 0;
}

.close {
  float: right;
  font-size: 20px;
  font-weight: bold;
  line-height: 20px;
  color: #000000;
  text-shadow: 0 1px 0 #ffffff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.4;
  filter: alpha(opacity=40);
}	
.form-signin {
	max-width: 300px;
	padding: 0;
	margin: 0 auto 20px;
	}
.form-signin .form-signin-heading,
.form-signin .checkbox {
	margin-bottom: 10px;
}
.form-signin input[type="text"],
.form-signin input[type="password"] {
	font-size: 16px;
	height: auto;
	margin-bottom: 15px;
	padding: 7px 9px;
}
.input-block-level {
	display: block;
	width: 100%;
	min-height: 30px;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
	font-size: 14px;
	line-height: 20px;
	color: #555555;
	vertical-align: middle;
	-webkit-border-radius: 4px;
	-moz-border-radius: 4px;
	border-radius: 4px;
	}
div.fb-login {
	text-align: center;
	clear: both;
	margin-top: 22px;
	}
p.fb-or-form {
	text-align: center;
	font-size: 1.5em;
	font-weight: 400;
	margin: 14px;
	}
p.align-right {
	text-align: right;
	}

/* News */
		
#left-column {
	float: left;
	width: 230px;
	margin: 0 -50px 50px 0;
	}
div.castitsystems {
	color: #999;
	text-align: center;
	width: 130px;
	letter-spacing: 1px;
	line-height: 22px;
	font-weight: 200;
	text-transform: lowercase;
	margin-bottom: 50px;
	}
div.castitsystems a {
	padding: 4px 8px;
	color: #fff;
	background-color: #999;
	text-decoration: none;
	}
div.castitsystems a:hover {
	text-decoration: underline;
	}
#news {
	border-top: 2px #414141 solid;
	border-bottom: 2px #414141 solid;}
#news h2 {
	background-color: #414141;
	padding: 8px;
	font-size: 29px;
	text-align: center;
	text-transform: uppercase;
	margin-top: 2px;
	}
span.news-subtitle {
	color: #fff; 
	font-family: 'Source Sans Pro', sans-serif;
	font-weight: 200;
	font-size: 14px;
	}
li.news-item {
	padding: 12px 0;
	border-top: 1px dotted #414141;
	font-size: 10px;
	}
li.news-item:first-child {
	border-top: none;
	}
#news h3 {
	font-size: 16px;
	font-weight: 400;
	margin: 4px 0;
	}
img.news-image {
	padding: 6px;
	border: 1px solid #414141;
	}
p.news-excerpt {
	font-size: 11px;
	color: #595959;
	margin-top: 6px;
	}

/* Available Roles */

#available {
	float: left;
	width: 460px;
	margin: 20px 20px 50px 0;
	padding-left: 70px;
	background:url(../images/h2-available-bkgd.jpg) no-repeat;
	}
img.available-clapper {
	position: absolute;
	left: 332px;
	top: 108px;
	}
#available h2 {
	font-size: 39px;
	text-transform: uppercase;
	margin-bottom: 10px;
	}
div.film-post-jobs {
	width: 460px;
	height: 42px;
	}
p.date {
	font-size: 10px;
	font-weight: 400;
	letter-spacing: 0.12em;
	margin-bottom: 8px;
	}
ul.available-role-list {
	list-style: none;
	margin-bottom: 20px;
	}
.available-role-list li {
	background-color: #f1f1f1;
	padding: 10px;
	margin-bottom: 10px;
	}
div.available-role-project {
	width: 100px;
	float: left;
	margin-right: 16px;
	overflow: visible;
	font-size: 13px;
	}
p.role-name {
	width: 100px;
	padding: 3px 3px 3px 6px;
	background-color: #414141;
	color: #fff;
	margin-bottom: 8px;
	}
span.caps {
	text-transform: uppercase;
	font-size: 9px;
	top: 3px;
	position: relative;
	letter-spacing: 0.2em;
	}
p.available-description {
	width: 305px;
	margin:0 0 0 130px;
	}
p.available-submit {
	width: 305px;
	text-align: right;
	margin:0 0 0 130px;
	}
p.available-roles {
	font-size: 24px;
	font-weight: 200;
	text-align: center;
	margin-top: 20px;
	}
	
/* Widget Area */

#widgets {
	float: left;
	width: 230px;
	margin: 20px 0px 50px 0;
	}
div.CIT-promo {
	text-align: center;
	margin-bottom: 30px;
	}
div.CIT-promo img {
	margin-bottom: 16px;
	}
span.promo-text {
	font-size: 1.7em;
	line-height: 1.6;
	font-weight: 200;
	}
div.online-open-calls {
	background-color: #414141;
	-webkit-border-radius: 10px;
	-moz-border-radius: 10px;
	border-radius: 10px;
	-webkit-box-shadow: -2px 2px 10px 2px rgba(102, 102, 102, .7);
	box-shadow: -2px 2px 10px 2px rgba(102, 102, 102, .7);
	padding: 14px;
	color: #fff;
	font-weight: 200;
	margin-bottom: 50px;
	}
div.online-open-calls h2 a {
	display: block;
	text-indent: -9000px;
	background: url(../images/btn-onlineopencall.png) no-repeat;
	width: 202px;
	height: 44px;
	border:0;
	}
div.online-open-calls h3 {
	font-size: 20px;
	font-weight: 400;
	}
div.online-open-calls ul {
	margin-left: 6px;
	width: 190px;
	}
div.online-open-calls li {
	border-bottom: 1px solid #808080;
	padding: 8px 0;
	}
div.online-open-calls li:last-child {
	border-bottom: none;
	}

/* Footer */
	
#footer {
	width: 960px;
	margin: 30px auto;
	clear: both;
	}
#footer-info {
	width: 880px;
	padding-top: 10px;
	border-top: 1px #ccc solid;
	}
#footer ul {
	padding: 22px 0px 0px 0px;
	height: 32px;
	}
#footer ul li {
	display: inline;
	font-size:12px;
	text-transform: lowercase;
	}
#footer ul li a {
	color:#808080;
	text-decoration: none;
	margin-right: 28px;
	}
#footer ul li a:hover {
	color:#71a81a;
	}
a.privacy {
	display: inline-block;
	text-indent: -9000px;
	background: url(../images/btn-privacy.jpg) no-repeat;
	width: 181px;
	height: 51px;
	top: -20px;
	position: relative;
	border:0;
	}
#footer p {
	font-size: 10px;
	color:#999;
	}
#powered-by {
	float:right;
	width: 62px;
	margin-left: 20px;
	text-align: left;
	color: #999;
	font-size: 9px;
	text-transform: lowercase;
	}
#powered-by p {
	margin-bottom: 0px;
	}
p.all-rights-reserved {
	width: 300px;
	float: right;
	text-align: right;
	}

/* image alignment */
img.floatleft { float:left;margin: 0 16px 10px 0;}
img.floatright { float:right;margin: 0 0 10px 16px;}
img.clear { clear:both;margin: 16px 0;}

div.spacer {clear: both; height: 20px;}


/* more */

a.arrow-link {
	text-transform: uppercase;
	font-weight: 700;
	padding-right: 20px;
	font-size: 12px;
	background:url(../images/submit-arrow.gif) no-repeat right;
	}

/* =Payment Gateway
-------------------------------------------------------------- */
#posters p {font-size: 20px; font-weight: 200; margin-bottom: 12px;}
#choosemembership {
	float: left;
	width: 460px;
	margin: 20px 20px 50px 0;
	padding-left: 70px;
	}
#choosemembership h2 {font-family: 'Source Sans Pro', sans-serif;font-size: 38px;font-weight: 200;color: #414141;}
#choosemembership h4 {
	font-family: 'Source Sans Pro', sans-serif;
	font-size: 22px;
	font-weight: 200;
	color: #fff;
	text-transform: uppercase;
	padding: 3px 10px;
	background-color: #414141;
	letter-spacing: 1px;
	text-align: center;
	}
#whitebox {
	width: 400px;
	padding: 30px;
	margin: 20px 0 50px 0;
	-webkit-box-shadow:  -4px 5px 15px 3px rgba(71, 71, 71, .6);
	box-shadow:  -4px 5px 15px 3px rgba(71, 71, 71, .6);
	-webkit-border-radius: 12px;
	-moz-border-radius: 12px;
	border-radius: 12px;
	}
#whitebox h3 {font-size: 25px;text-transform: uppercase; letter-spacing: 0;font-family: 'Fjalla One', sans-serif;color:#71a81a;font-weight:400;}
#whitebox p {font-size: 20px; margin-left: 135px;line-height: 30px;}
span.smallgrey {font-size: 11px; color: #999;}

/* membership table */
table.membership {margin-top: 6px;width: 460px;border-bottom: 1px solid #b2b2b2;}
tr.alternate:nth-child(even) {background: #f1f1f2;}
table.membership td {margin: 0;padding: 18px 14px; font-size: 16px;font-weight:200;}
table.membership td::first-line {font-weight:400;}
span.greenupper {text-transform: uppercase;color: #71a81a; padding-right: 4px;font-weight: 700;}
.check {width: 90px;background: url(../images/check-mark.png) no-repeat center;}

span.widgettextlink {font-size: 17px;font-weight: 200;}
h2.memlevel {font-size: 25px;text-transform: uppercase; letter-spacing: 0;font-family: 'Fjalla One', sans-serif;color:#71a81a;}
h3.basicmem {font-size: 17px;text-transform: uppercase; text-align: left; font-weight: 400; margin-bottom: 12px;}
p.basicmem {margin-bottom: 24px; font-size: 23px; line-height: 32px; font-weight: 200;}
ul.basicmem  li { text-align: left; font-size: 14px; margin: 0 0 8px 22px; font-weight: 200; list-style: disc;}
	
/* revised items from homepage html */
