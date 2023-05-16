# AIandDS_SECTION1_406B_29
#index#
<!DOCTYPE html>
<html>
<head>
    <title>Corporate Recruitment Management</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to Corporate Recruitment Management</h1>
    <nav>
        <ul>
            <li><a href="/post_job">Post a Job</a></li>
            <li><a href="/apply">Apply for a Job</a></li>
        </ul>
    </nav>
</body>
</html>


css styling
#post-job#
<!DOCTYPE html>
<html>
<head>
    <title>Post a Job</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Post a Job</h1>
    <form method="POST" action="/post_job">
        <label for="title">Job Title</label>
        <input type="text" id="title" name="title" required>

        <label for="description">Job Description</label>
        <textarea id="description" name="description" required></textarea>

        <label for="requirements">Job Requirements</label>
        <textarea id="requirements" name="requirements" required></textarea>

        <button type="submit">Post Job</button>
    </form>
</body>
</html>

#apply-hthml#
<!DOCTYPE html>
<html>
<head>
    <title>Apply for a Job</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Apply for a Job</h1>
    <form method="POST" action="/apply">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>

        <label for="resume">Resume</label>
        <textarea id="resume" name="resume" required></textarea>

        <button type="submit">Apply</button>
    </form>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

h1 {
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
}



<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<html lang="en">
<head>
    <style>
    body{

    margin: 0;
    padding: 0;
    background: url(pic.jpg);
    background-size: cover;
    background-position: cover;
    font-family:'Arial Narrow Bold', sans-serif;

}

.login-box{
width: 320px;
height: 420px;
background: rgba(0, 0, 0, 0.5);
color: #fff;
top: 50%;
left: 50%;
position: absolute;
transform: translate(-50%,-50%);
box-sizing: border-box;
padding: 70px 30px;

}

.avatar
{

    width: 100px;
    height: 100px;
    border-radius: 50%;
    position: absolute;
    top: -50px;
    left: calc(50% - 50px);
}

h1{

    margin: 0;
    padding: 0 0 20px;
    text-align: center;
    font-size: 18px;

}
.login-box p{
    margin: 0;
    padding: 0;
    font-weight: bold;



}

.login-box input{

    width: 100%;
    margin-bottom: 20px ;


}

.login-box input[type="text"] , input[type="password"]
{

border: none;
border-bottom: 1px solid #fff;
background: transparent;
outline: none;
height: 40px;
color: #fff;
font-size: 16px;


}



indexing
.login-box input[type="submit"]
{

border: none;
outline: none;
height: 40px;
font-size: 18px;
border-radius: 20px;
color: #fff;
background: #1c8adb;

}


.login-box ::placeholder
{

    color: #fff;
}


.login-box input[type="submit"]:hover
{

    cursor: pointer;
    background: #39dc79;
    color: #000;
}
.login-box a{

    text-decoration: none;
    font-size: 14px;
    color: #fff;

}
    
    </style>
    <link rel="icon" href="logo.png" type="image/gif" sizes="16x16">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Health Care Management System | Login Page</title>
    
</head>
<body>
    

<div class="login-box">

<img src="logo.png" alt="Logo" class="avatar">
    <h1>Login Here</h1>
    <form action="#">
        <p>Username</p>
        <input type="text" required name="username" placeholder="Enter username here">
        <p>Password</p>
        <input type="password" name="password" required placeholder="Enter Password here">
        <input type="submit" name="submit" value="Login">
        <a href="#">Forget Password</a>
    </form>

</div>


</body>
</html>
  
  
  
  <!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">


		<title>Formicon-Flat Forms Pack</title>
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" href="icons/styles.css">
		<link rel="stylesheet" href="css/bootstrap-custom.css">
		<link rel="stylesheet" href="css/registration-form.css">

		<link href='https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,600' rel='stylesheet' type='text/css'>
		<style>
		git.io/normalize */
article,
aside,
details,
figcaption,.com { color: #93a1a1; }
.lit { color: #195f91; }
.pun, .opn, .clo { color: #93a1a1; }
.fun { color: #dc322f; }
.str, .atv { color: #D14; }
.kwd, .linenums .tag { color: #1e347b; }
.typ, .atn, .dec, .var { color: teal; }
.pln { color: #48484c; }

.prettyprint {
  padding: 8px;
  background-color: #f7f7f9;
  border: 1px solid #e1e1e8;
}
.prettyprint.linenums {
  -webkit-box-shadow: inset 40px 0 0 #fbfbfc, inset 41px 0 0 #ececf0;
     -moz-box-shadow: inset 40px 0 0 #fbfbfc, inset 41px 0 0 #ececf0;
          box-shadow: inset 40px 0 0 #fbfbfc, inset 41px 0 0 #ececf0;
}

/* Specify class=linenums on a pre to get line numbering */
ol.linenums {
  margin: 0 0 0 33px; /* IE indents via margin-left */
} 
ol.linenums li {
  padding-left: 12px;
  color: #bebec5;
  line-height: 18px;
  text-shadow: 0 1px 0 #fff;
}
figure,
footer,
header,
hgroup,
main,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
video {
  display: inline-block;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
a {
  background: transparent;
}
a:focus {
  outline: thin dotted;
}
a:active,
a:hover {
  outline: 0;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
hr {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
  height: 0;
}
mark {
  background: #ff0;
  color: #000;
}
code,
kbd,
pre,
samp {
  font-family: monospace, serif;
  font-size: 1em;
}
pre {
  white-space: pre-wrap;
}
q {
  quotes: "\201C" "\201D" "\2018" "\2019";
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 0;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
button,
input,
select,
textarea {
  font-family: inherit;
  font-size: 100%;
  margin: 0;
}
button,
input {
  line-height: normal;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="search"] {
  -webkit-appearance: textfield;
  -moz-box-sizing: content-box;
  -webkit-box-sizing: content-box;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
  vertical-align: top;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
*,
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 62.5%;
  min-height: 100%;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 14px;
  line-height: 1.428571429;
  color: #333333;
  background-color: #ffffff;
  -webkit-font-smoothing: antialiased;
  text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.004);
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #428bca;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #2a6496;
  text-decoration: underline;
}
a:focus {
  outline: thin dotted #333;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
img {
  vertical-align: middle;
}
hr {
  margin-top: 20px;
  margin-bottom: 20px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
p {
  margin: 0 0 10px;
}
.lead {
  margin-bottom: 20px;
  font-size: 16px;
  font-weight: 200;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 21px;
  }
}
small,
.small {
  font-size: 85%;
}
cite {
  font-style: normal;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #999999;
}
h1,
h2,
h3 {
  margin-top: 20px;
  margin-bottom: 10px;
}
h1 small,
h2 small,
h3 small,
h1 .small,
h2 .small,
h3 .small {
  font-size: 65%;
}
h4,
h5,
h6 {
  margin-top: 10px;
  margin-bottom: 10px;
}
h4 small,
h5 small,
h6 small,
h4 .small,
h5 .small,
h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 36px;
}
h2,
.h2 {
  font-size: 30px;
}
h3,
.h3 {
  font-size: 24px;
}
h4,
.h4 {
  font-size: 18px;
}
h5,
.h5 {
  font-size: 14px;
}
h6,
.h6 {
  font-size: 12px;
}
.page-header {
  padding-bottom: 9px;
  margin: 40px 0 20px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 10px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
.list-inline > li:first-child {
  padding-left: 0;
}
dl {
  margin-bottom: 20px;
}
dt,
dd {
  line-height: 1.428571429;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 768px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
  .dl-horizontal dd:before,
  .dl-horizontal dd:after {
    content: " ";
    /* 1 */
    display: table;
    /* 2 */
  }
  .dl-horizontal dd:after {
    clear: both;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #999999;
}
abbr.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 10px 20px;
  margin: 0 0 20px;
  border-left: 5px solid #eeeeee;
}
blockquote p {
  font-size: 17.5px;
  font-weight: 300;
  line-height: 1.25;
}
blockquote p:last-child {
  margin-bottom: 0;
}
blockquote small {
  display: block;
  line-height: 1.428571429;
  color: #999999;
}
blockquote small:before {
  content: '\2014 \00A0';
}
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
}
blockquote.pull-right p,
blockquote.pull-right small,
blockquote.pull-right .small {
  text-align: right;
}
blockquote.pull-right small:before,
blockquote.pull-right .small:before {
  content: '';
}
blockquote.pull-right small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
blockquote:before,
blockquote:after {
  content: "";
}
address {
  margin-bottom: 20px;
  font-style: normal;
  line-height: 1.428571429;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 15px;
  padding-right: 15px;
}
.container:before,
.container:after {
  content: " ";
  /* 1 */
  display: table;
  /* 2 */
}
.container:after {
  clear: both;
}
.row {
  margin-left: -15px;
  margin-right: -15px;
}
.row:before,
.row:after {
  content: " ";
  /* 1 */
  display: table;
  /* 2 */
}
.row:after {
  clear: both;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 15px;
  padding-right: 15px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666666666666%;
}
.col-xs-10 {
  width: 83.33333333333334%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666666666666%;
}
.col-xs-7 {
  width: 58.333333333333336%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666666666667%;
}
.col-xs-4 {
  width: 33.33333333333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.666666666666664%;
}
.col-xs-1 {
  width: 8.333333333333332%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666666666666%;
}
.col-xs-pull-10 {
  right: 83.33333333333334%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666666666666%;
}
.col-xs-pull-7 {
  right: 58.333333333333336%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666666666667%;
}
.col-xs-pull-4 {
  right: 33.33333333333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.666666666666664%;
}
.col-xs-pull-1 {
  right: 8.333333333333332%;
}
.col-xs-pull-0 {
  right: 0%;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666666666666%;
}
.col-xs-push-10 {
  left: 83.33333333333334%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666666666666%;
}
.col-xs-push-7 {
  left: 58.333333333333336%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666666666667%;
}
.col-xs-push-4 {
  left: 33.33333333333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.666666666666664%;
}
.col-xs-push-1 {
  left: 8.333333333333332%;
}
.col-xs-push-0 {
  left: 0%;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666666666666%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333333334%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666666666666%;
}
.col-xs-offset-7 {
  margin-left: 58.333333333333336%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666666666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.666666666666664%;
}
.col-xs-offset-1 {
  margin-left: 8.333333333333332%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .container {
    width: 750px;
  }
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666666666666%;
  }
  .col-sm-10 {
    width: 83.33333333333334%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666666666666%;
  }
  .col-sm-7 {
    width: 58.333333333333336%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666666666667%;
  }
  .col-sm-4 {
    width: 33.33333333333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.666666666666664%;
  }
  .col-sm-1 {
    width: 8.333333333333332%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666666666666%;
  }
  .col-sm-pull-10 {
    right: 83.33333333333334%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666666666666%;
  }
  .col-sm-pull-7 {
    right: 58.333333333333336%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666666666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.666666666666664%;
  }
  .col-sm-pull-1 {
    right: 8.333333333333332%;
  }
  .col-sm-pull-0 {
    right: 0%;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666666666666%;
  }
  .col-sm-push-10 {
    left: 83.33333333333334%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666666666666%;
  }
  .col-sm-push-7 {
    left: 58.333333333333336%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666666666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.666666666666664%;
  }
  .col-sm-push-1 {
    left: 8.333333333333332%;
  }
  .col-sm-push-0 {
    left: 0%;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666666666666%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333333334%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666666666666%;
  }
  .col-sm-offset-7 {
    margin-left: 58.333333333333336%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666666666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.666666666666664%;
  }
  .col-sm-offset-1 {
    margin-left: 8.333333333333332%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .container {
    width: 970px;
  }
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666666666666%;
  }
  .col-md-10 {
    width: 83.33333333333334%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666666666666%;
  }
  .col-md-7 {
    width: 58.333333333333336%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666666666667%;
  }
  .col-md-4 {
    width: 33.33333333333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.666666666666664%;
  }
  .col-md-1 {
    width: 8.333333333333332%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666666666666%;
  }
  .col-md-pull-10 {
    right: 83.33333333333334%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666666666666%;
  }
  .col-md-pull-7 {
    right: 58.333333333333336%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666666666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.666666666666664%;
  }
  .col-md-pull-1 {
    right: 8.333333333333332%;
  }
  .col-md-pull-0 {
    right: 0%;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666666666666%;
  }
  .col-md-push-10 {
    left: 83.33333333333334%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666666666666%;
  }
  .col-md-push-7 {
    left: 58.333333333333336%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666666666667%;
  }
  .col-md-push-4 {
    left: 33.33333333333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.666666666666664%;
  }
  .col-md-push-1 {
    left: 8.333333333333332%;
  }
  .col-md-push-0 {
    left: 0%;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666666666666%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333333334%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666666666666%;
  }
  .col-md-offset-7 {
    margin-left: 58.333333333333336%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666666666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.666666666666664%;
  }
  .col-md-offset-1 {
    margin-left: 8.333333333333332%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1170px;
  }
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666666666666%;
  }
  .col-lg-10 {
    width: 83.33333333333334%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666666666666%;
  }
  .col-lg-7 {
    width: 58.333333333333336%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666666666667%;
  }
  .col-lg-4 {
    width: 33.33333333333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.666666666666664%;
  }
  .col-lg-1 {
    width: 8.333333333333332%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666666666666%;
  }
  .col-lg-pull-10 {
    right: 83.33333333333334%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666666666666%;
  }
  .col-lg-pull-7 {
    right: 58.333333333333336%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666666666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.666666666666664%;
  }
  .col-lg-pull-1 {
    right: 8.333333333333332%;
  }
  .col-lg-pull-0 {
    right: 0%;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666666666666%;
  }
  .col-lg-push-10 {
    left: 83.33333333333334%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666666666666%;
  }
  .col-lg-push-7 {
    left: 58.333333333333336%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666666666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.666666666666664%;
  }
  .col-lg-push-1 {
    left: 8.333333333333332%;
  }
  .col-lg-push-0 {
    left: 0%;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666666666666%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333333334%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666666666666%;
  }
  .col-lg-offset-7 {
    margin-left: 58.333333333333336%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666666666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.666666666666664%;
  }
  .col-lg-offset-1 {
    margin-left: 8.333333333333332%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 20px;
  font-size: 21px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  /* IE8-9 */
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: thin dotted #333;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 14px;
  line-height: 1.428571429;
  color: #555555;
}
/**
 * Registration Form
 * -------------------------------------
 */
.fcorn-register {
  font-family: "Source Sans Pro";
  width: 550px;
  margin: 0 auto;
  padding: 10px 35px;
  background: #fff;
  border: 1px solid #eee;
  letter-spacing: 1px;
  box-shadow: 0 0 2px rgba(60, 60, 60, 0.1);
}
.fcorn-register p {
  margin-bottom: 30px;
}
.fcorn-register p.register-info {
  background: #b5b5b5;
  color: #fff;
  padding: 8px 15px;
  font-size: 12px;
  font-weight: 600;
  margin-top: 30px;
}
.fcorn-register p > input,
.fcorn-register p > select {
  display: inline-block;
  width: 100%;
  padding: 10px 15px;
  font-weight: 100;
  color: #686868;
  border: 1px solid rgba(159, 159, 159, 0.2);
  box-shadow: 0 0 3px rgba(60, 60, 60, 0.05);
}
.fcorn-register p > input:focus,
.fcorn-register p > select:focus {
  border: 1px solid #63c6ef;
  outline: none;
}
.fcorn-register p > select:focus {
  border: 1px solid rgba(159, 159, 159, 0.2);
}
  /** To hide default arrow */
.fcorn-register p > select {
  text-indent: 0.01px;   /** if it doesn't work change to something 0.05 etc... **/
  text-overflow: "";
  -webkit-appearance: none;
  -moz-appearance: none;
}
.fcorn-register p > select::-ms-expand {
  display: none;
}
.fcorn-register p.city-wrap,
.fcorn-register p.country-wrap {
  position: relative;
}
.fcorn-register p.city-wrap:before,
.fcorn-register p.country-wrap:before {
    /** For custom arrow in select box **/
  position: absolute;
  content: "#";
  font-family: "entypo";
  font-size: 18px;
  color: #686868;
  top: 10px;
  right: 25px;
}
.fcorn-register p > span.extern-type {
  float: right;
  text-align: right;
  font-size: 12px;
  display: block;
  color: #b5b5b5;
}

  /** Register Toogle Btn **/
.fcorn-register p.register-toggle {
  position: relative;
}
.fcorn-register p.register-toggle > .info {
  font-size: 13px;
  margin-left: 20px;
}
.fcorn-register p.register-toggle > label.toggle-label {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  -o-user-select: none;
  user-select: none;
  cursor: pointer;
  display: inline-block;
  background: #4cbeed;
  width: 60px;
  height: 24px;
  float: left;
  position: relative;
  font-size: 10px;
  color: #fff;
}
.fcorn-register p.register-toggle > label.toggle-label > input.toggle-input {
  position: absolute;
  top: 0;
  left: 0;
  opacity: 0;
}
  /** this is for labeling of on/off text **/
.fcorn-register p.register-toggle > label.toggle-label:before,
.fcorn-register p.register-toggle > label.toggle-label:after {
  position: absolute;
  top: 30%;
  line-height: 1.1;
  font-weight: 100;
}
.fcorn-register p.register-toggle > label.toggle-label:before {
  content: attr(data-on);
  left: 7px;
}
.fcorn-register p.register-toggle > label.toggle-label:after {
  content: attr(data-off);
  right: 7px;
}
  /** handle switch **/
.fcorn-register p.register-toggle > label.toggle-label .toggle-handle {
  position: absolute;
  background: #fff;
  left: 0;
  top: 0;
  border: 1px solid #4cbeed;
  display: inline-block;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  box-shadow: inset 0 0 5px rgba(50, 50, 50, 0.1);
  width: 50%;
  height: inherit;
}
.fcorn-register p.register-toggle > label.toggle-label > input.toggle-input:checked ~ .toggle-handle {
  left: 30px;
}

  /* Register button */
.fcorn-register p.register-submit {
  display: inline-block;
  float: right;
}
.fcorn-register p.register-submit > input {
  border: none;
  width: 200px;
  color: #fff;
  padding: 10px 15px;
  background: #43bbec;
  text-align: center;
  letter-spacing: 1px;
  box-shadow: 0 1px 1px #1daae3;
}
.fcorn-register p.register-submit > input:focus {
  border: none;
  outline: none;
}
.fcorn-register p.register-submit > input:hover {
  background: #39b7eb;
}
.fcorn-register p.register-submit > input:active {
  box-shadow: inset 0 0 10px #1daae3;
  -webkit-transform: translate(0, 1px);
  -ms-transform: translate(0, 1px);
  transform: translate(0, 1px);
}
		
		
		</style>
		
	</head>
	<body>
		<!-- Register Form -->
		<div class="form-wrapper"> <!-- Form-wrapper only for positioning -->
			<form action="#non" method="post" class="fcorn-register container">
				<p class="register-info">Note: All fields are required.</p>
				<div class="row">
					<p class="col-md-6"><input type="text" placeholder="First Name" required></p>
					<p class="col-md-6"><input type="text" placeholder="Last Name" required></p>
				</div>
				<p><input type="email" placeholder="Email Address" required>
				   <span class="extern-type">We'll keep this private.</span>
				</p>
				<p><input type="password" placeholder="Password" required>
					<span class="extern-type">Atleast 8 characters long.</span>
				</p>
				<p><input type="password" placeholder="Verify Password" required></p>
				<div class="row">
					
					
					
          <p class="col-md-12"><input type="text" placeholder="Membership code"><span class="extern-type">Enter your membership code, if you do not have one, leave it blank.</span></p>
				</div>
				<div class="row">
				
					<label for="city"> City:</label>
						<select id="city">
						<option value=" Amalapuram">Amalapuram</option>
							<option value=" Ahapuram">Ahapuram</option>
							<option value=" Echapuaram">Echapuaram</option>
						</select>
					</p>
					<label for="country">Country:</label>
				
						<select id ="country">
							<option value="INDIA">INDIA</option>
							
						</select>
					</p>
          <div> 
            <p class="col-xs-12"><form action="upload.php" method="post" enctype="multipart/form-data">
            Upload your personal photo:
              <input type="file" name="fileToUpload" id="fileToUpload">
              <input type="submit" value="Upload Image" name="submit" required>
           </p>
				</div>
          <br/>
				<p class="register-toggle">
					<label for="register-agree" class="toggle-label" data-on="YES" data-off="NO">
						<input type="checkbox" id="register-agree" class="toggle-input">
						<span class="toggle-handle"></span>
					</label>
					<span class="info">Do you agree to the <a href="#">terms and conditions?</a></span>
				</p>
				<p class="register-submit"><input type="submit" value="Register Now"></p>
			</form>
    </div>
    <a href=”login.html”>Link to register  Page </a>
    
	



		<!-- This is a placeholder fallback for IE9 browser -->
		<!-- For IE9 and below - placeholder fallback-->
		<!--[if lt IE 10]>
			<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
			<script src="jquery.placeholder.min.js"></script>
			<script type="text/javascript">
				$('input, textarea').placeholder();
			</script>
		<![endif]-->
	</body>
</html>
  
  
  <!DOCTYPE html>
<html> 
<head>
<title> HB Hospital | About Us </title>

		<!-- Web Fonts -->
		<link rel="stylesheet" href="//fonts.googleapis.com/css?family=Open+Sans:400,300,600&amp;subset=cyrillic,latin">

		<!-- CSS Global Compulsory -->
		<link rel="stylesheet" href="assets/plugins/bootstrap/css/bootstrap.min.css">
		<link rel="stylesheet" href="assets/css/style.css">

		<!-- CSS Header and Footer -->
		<link rel="stylesheet" href="assets/css/header.css">
		<link rel="stylesheet" href="assets/css/footer.css">

		<!-- CSS Implementing Plugins -->
		<link rel="stylesheet" href="assets/plugins/line-icons-pro/styles.css">
		<link rel="stylesheet" href="assets/plugins/line-icons/line-icons.css">
		<link rel="stylesheet" href="assets/plugins/font-awesome/css/font-awesome.min.css">

		<!-- CSS Customization -->
		<link rel="stylesheet" href="assets/css/custom.css">

</head>

<body>
		<div class="wrapper">
		<!--=== Header v1 ===-->
		<div class="header-v1">
		<!-- Topbar -->
		<div class="topbar-v1">
		<div class="container">
		<div class="row">
		<div class="col-md-6">
			<ul class="list-inline top-v1-contacts">
			<li>
			<i class="fa fa-envelope"></i> Email: unityhospital@gmail.com
			</li>
			<li>
			<i class="fa fa-phone"></i> Contact no : 88666 00555
			</li>
			</ul>
		</div>
		</div>
		</div>
		</div>

<!-- End Topbar -->

				<!-- Navbar -->
				<div class="navbar mega-menu" role="navigation">
				<div class="container">
				<!-- Brand and toggle get grouped for better mobile display -->
				<div class="res-container">
				<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-responsive-collapse">
				<span class="sr-only">Toggle navigation</span>
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
				</button>

				<div class="navbar-brand">
				<a href="index.html">
				<img src="assets/img/logo/unity_white.jpg" alt="Logo"/>
				</a>
				</div>
				</div><!--/end responsive container-->

				<!-- Collect the nav links, forms, and other content for toggling -->
				<div class="collapse navbar-collapse navbar-responsive-collapse">
				<div class="res-container">
				<ul class="nav navbar-nav">

				<!-- Collect the nav links, forms, and other content for toggling -->


				<!-- Home  -->
				<li class="mega-menu-fullwidth">
				<a href="index.html" >
				HOME
				</a>

				</li>
				<!-- End Home-->

				<!-- About Us -->
				<li class="mega-menu-fullwidth">
				<a href="about.html" >
				ABOUT US
				</a>	
				</li>
				<!-- End About us -->

				<!-- Doctors -->
				<li class="mega-menu-fullwidth">
				<a href="doctors.html" >
				DOCTORS
				</a>

				</li>
				<!-- End Doctors -->


				<!-- Gallery -->
				<li class="mega-menu-fullwidth">
				<a href="gallery.html" >
				GALLERY
				</a>

				</li>
				<!-- End Gallery -->


				<!-- Blog -->
				<li class="mega-menu-fullwidth">
				<a href="blog.html" >
				BLOGS
				</a>	
				</li>
				<!-- End Blog -->

				<!-- Contact Us -->
				<li class="mega-menu-fullwidth">
				<a href="contact.html" >
				CONTACT US
				</a>	
				</li>
				<!-- End Contact us -->

				<!-- Registration -->
				<li class="mega-menu-fullwidth">
				<a href="registration.html" >
				REGISTRATION
				</a>	
				</li>
				<!-- End registration -->

				<!-- login -->
				<li class="mega-menu-fullwidth">
				<a href="login.html" >
				LOGIN
				</a>	
				</li>
				<!-- End login -->

				<!-- Appointment -->
				<li class="mega-menu-fullwidth">
				<a href="appointment.html">
				BOOK APPOINTMENT
				</a>

				</li>
				<!-- End Appointment -->

				</ul>

				</div>
				</div>
				</div>
				</div>
				</div>
				<!-- End Navbar -->

	<!-- About Heading -->
	<div class="container content-sm" style="margin-top: -25px;">
	<div class="headline-center" style="margin-bottom: 60px;">
	<h2>ABOUT<span style="color: #72c02c;"> UNITY </span></h2>
	</div>
	</div>		

			<!-- About Section 1 -->
			<div class="container content" style="margin-top: -90px">
			<div class="row" style="margin-bottom: 40px;">
			<div class="col-md-6" style="margin-bottom: 40px;">
			<p><span style="color: #72c02c;">UNITY </span> Hospital  is a multi/super speciality hospital located at the prime location of Vaishnodevi Circle, SG Road, Ahmedabad; with state-of-the-art facilities & treatments at an affordable cost, encompassing wide spectrum of accurate diagnostics and elegant therapeutics created on the philosophical edifice of patient and ethical centricity ensuring humanistic dispensation.</p>
			<ul class="list-unstyled">
			<li><i class="fa fa-check color-green"></i> Multiple Options For Treatment.</li>
			<li><i class="fa fa-check color-green"></i> Full Of Latest Technologies and Equipments.</li>
			<li><i class="fa fa-check color-green"></i> Best Hospital Of 2020 Award Winner.</li>
			<li><i class="fa fa-check color-green"></i> 24/7 Ambulance Support.</li>
			<li><i class="fa fa-check color-green"></i> Eminent and Experienced Doctors.</li>
			</ul><br />

			<!-- Blockquotes -->
			<blockquote>
			<p>As a leading health organization in our region, we want to be a strong influence for better health and prevention, and there’s no better place to start than among our own employees.</p>
			<small>CEO Harshil Patel</small>
			</blockquote>
			</div>

			<div class="col-md-6" style="margin-bottom: 40px;">
			<div class="responsive-video">
			<iframe src="https://player.vimeo.com/video/33787650" allowFullScreen></iframe>
			</div>
			</div>
			</div><!--/row-->
			</div>
			</div>
			<!-- End About Section 1 -->
				
				<!--=== About Section 2 ===-->
				<div class="container content-sm aboutSection">
				<div class="row service-block-v6 section1">
				<div class="col-md-4" style="margin-bottom: 50px;">
				<i class="icon-custom rounded-x icon-color-u icon-line icon-medical-054"></i>
				<div class="service-desc">
				<h2>Vision</h2>
				<p>Ensuring ‘well being’ as a humane commitment to <br/>enliven humanity.</p>
				</div>
				</div>
				<div class="col-md-4" style="margin-bottom: 50px;">
				<i class="icon-custom rounded-x icon-color-u icon-line icon-medical-038"></i>
				<div class="service-desc">
				<h2>Mission</h2>
				<p>The ‘well being’ ensured by extension of Available, Accessible, Affordable, Safe, Efficacious, Professional<br/>And Ethical.</p>
				</div>
				</div>
				<div class="col-md-4">
				<i class="icon-custom rounded-x icon-color-u icon-line icon-medical-004"></i>
				<div class="service-desc">
				<h2>Core Values</h2>
				<p>Team Work, Integrity, Responsibility, Compassion,<br/> And Ethics.</p>
				</div>
				</div>
				</div><!--/end row-->
				</div>
				<!--=== End About Section 2===-->


						<!--=== About Section 3 ===-->
						<div class="bg-color-light">
						<div class="container content-sm">
						<div class="headline-center" style="margin-bottom: 60px;">
						<h2>OUR DEPARTMENTS</h2>
						<div class="line"></div>
						<p>UNITY Hospital is spread over a massive 6 acre campus <br/> providing<strong> 300+ </strong> beds and catering for nearly 45 super-specialties.</p>
						</div>

						<!-- Service Block v8 -->
						<div class="row" style="margin-bottom: 30px;">
						<div class="col-sm-6 " style="margin-bottom: 50px;">
						<div class="service-block-v8">
						<i class=" icon-medical-008"></i>
						<div class="service-block-desc">
						<h3>Cardiology</h3>
						<p>The department of cardiology at UNITY Hospital comprises of top cardiac experts who have appreciable experience in dealing with various types of cases in the cardiology and perform accurate diagnosis</p>
						</div>
						</div>
						</div>
						<div class="col-sm-6" style="margin-bottom: 20px;">
						<div class="service-block-v8">
						<i class="icon-medical-094"></i>
						<div class="service-block-desc">
						<h3>Dermatology and Cosmetology</h3>
						<p>The dermatology department of UNITY Hospital consists of a team of dermatologists and staff who are practicing in the field of dermatology and cosmetology for years and perform their best to treat the patients.</p>
						</div>
						</div>
						</div>
						</div>
						<!-- End Service Block v8 -->

						<!-- Service Block v8 -->
						<div class="row " style="margin-bottom: 30px;">
						<div class="col-sm-6 " style="margin-bottom: 50px;">
						<div class="service-block-v8">
						<i class="icon-medical-005"></i>
						<div class="service-block-desc">
						<h3>Emergency Care, CCU, & ICU</h3>
						<p>At UNITY Hospital, 24x7 care is provided to all our patients, keeping in mind patient dignity and ethical practice. Holistic care is ensured by our team of critical care experts who use a multidisciplinary approach.</p>
						</div>
						</div>
						</div>
						<div class="col-sm-6" style="margin-bottom: 20px;">
						<div class="service-block-v8">
						<i class="icon-medical-037"></i>
						<div class="service-block-desc">
						<h3>General Surgery</h3>
						<p>At UNITY Hospital, we have a team of experienced general surgeons who possess the skills to carry out the most complex surgeries.</p>
						</div>
						</div>
						</div>
						</div>
						<!-- End Service Block v8 -->

						<!-- Service Block v8 -->
						<div class="row" style="margin-bottom: 20px;">
						<div class="col-sm-6" style="margin-bottom: 50px;">
						<div class="service-block-v8">
						<i class="icon-medical-001"></i>
						<div class="service-block-desc">
						<h3>Health Checkup Packages</h3>
						<p>UNITY Hospital provides health check up packages in Ahmedabad at very affordable price. As we aim at imbibing hope, health, and happiness in the community at large, our health check up packages in Ahmedabad help in early diagnosis.</p>
						</div>
						</div>
						</div>
						<div class="col-sm-6">
						<div class="service-block-v8">
						<i class="icon-medical-044"></i>
						<div class="service-block-desc">
						<h3>Neurology</h3>
						<p>The team at the Neurology department of UNITY Hospital comprises of highly-trained, skilled, and well-experienced team of Neurologists, Neurosurgeons, interventional radiologists, Neurophysiotherpists and rehabilitation teams who make sure that the patients receive the best quality treatments.</p>
						</div>
						</div>
						</div>
						</div>
						<!-- End Service Block v8 -->
						</div>
						<!--=== End About Section 3===-->

		<!--=== Footer ===-->
		<div class="footer-v1">
		<div class="footer">
		<div class="container">
		<div class="row">
		<!-- About -->
		<div class="col-md-3" style="margin-bottom: 40px;">
		<a href="index.html"><img id="logo-footer" class="footer-logo" src="assets/img/logo/unity_white.jpg" alt=""/></a>
		<p>At Unity Hospital, we are convinced that 'quality' and 'lowest cost' are not mutually exclusive when it comes to healthcare delivery.</p>
		<p>Our mission is to deliver high quality, affordable healthcare services to the broader population in India.</p>
		</div><!--/col-md-3-->
		<!-- End About -->

		<!-- Latest -->
		<div class="col-md-3" style="margin-bottom: 40px;">
		<div class="posts">
		<div class="headline"><h2>Latest Posts</h2></div>
		<ul class="list-unstyled latest-list">
		<li>
		<a href="blog.html">Incredible content</a>
		<small>December 16, 2020</small>
		</li>
		<li>
		<a href="gallery.html">Latest Images</a>
		<small>December 16, 2020</small>
		</li>
		<li>
		<a href="terms.html">Terms and Conditions</a>
		<small>December 16, 2020</small>
		</li>
		</ul>
		</div>
		</div><!--/col-md-3-->
		<!-- End Latest -->

		<!-- Link List -->
		<div class="col-md-3" style="margin-bottom: 40px;">
		<div class="headline"><h2>Useful Links</h2></div>
		<ul class="list-unstyled link-list">
		<li><a href="about.html">About us</a><i class="fa fa-angle-right"></i></li>
		<li><a href="Contact.html">Contact us</a><i class="fa fa-angle-right"></i></li>
		<li><a href="appointment.html">Book Appointment</a><i class="fa fa-angle-right"></i></li>
		</ul>
		</div><!--/col-md-3-->
		<!-- End Link List -->

		<!-- Address -->
		<div class="col-md-3 map-img" style="margin-bottom: 40px;">
		<div class="headline"><h2>Contact Us</h2></div>
		<address class="md-margin-bottom-40">
		Unity Hospital <br />
		Ahmedabad, IN <br />
		Phone: 886 666 00555 <br />
		Email: unityhospital@gmail.com 
		</address>
		</div><!--/col-md-3-->
		<!-- End Address -->
		</div>
		</div>
		</div><!--/footer-->

		<div class="copyright">
		<div class="container">
		<div class="row">
		<div class="col-md-6">
		<p>
		2020 &copy; All Rights Reserved.
		<a href="privacy.html">Privacy Policy</a> | <a href="terms.html">Terms of Service</a>
		</p>
		</div>

		<!-- Social Links -->
		<div class="col-md-6">
		<ul class="footer-socials list-inline">
		<li>
		<a href="http://www.facebook.com" class="tooltips" data-toggle="tooltip" data-placement="top" title="" data-original-title="Facebook">
		<i class="fa fa-facebook"></i>
		</a>
		</li>
		<li>
		<a href="http://www.skype.com" class="tooltips" data-toggle="tooltip" data-placement="top" title="" data-original-title="Skype">
		<i class="fa fa-skype"></i>
		</a>
		</li>
		<li>
		<a href="http://www.googleplus.com" class="tooltips" data-toggle="tooltip" data-placement="top" title="" data-original-title="Google Plus">
		<i class="fa fa-google-plus"></i>
		</a>
		</li>
		<li>
		<a href="http://www.linkedin.com" class="tooltips" data-toggle="tooltip" data-placement="top" title="" data-original-title="Linkedin">
		<i class="fa fa-linkedin"></i>
		</a>
		</li>
		<li>
		<a href="http://www.Pinterest.com" class="tooltips" data-toggle="tooltip" data-placement="top" title="" data-original-title="Pinterest">
		<i class="fa fa-pinterest"></i>
		</a>
		</li>
		<li>
		<a href="http://www.twitter.com" class="tooltips" data-toggle="tooltip" data-placement="top" title="" data-original-title="Twitter">
		<i class="fa fa-twitter"></i>
		</a>
		</li>
		</ul>
		</div>
		<!-- End Social Links -->
		</div>
		</div>
		</div>
		</div>
</div>  <!-- End Wrapper -->

</body>
</html>
