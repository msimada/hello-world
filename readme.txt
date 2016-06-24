@charset "UTF-8";

/*! normalize.css v3.0.2 | MIT License | git.io/normalize*/
html{
	font-family: sans-serif;
	-ms-text-size-adjust: 100%;
	-webkit-text-size-adjust: 100%;
}

body{
	margin: 0;
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary{
	display: block;
}

audio,
canvas,
progress,
video{
	display: inline-block;
	vertical-align: baseline;
}

audio:not([controls]){
	display: none;
	height: 0;
}

[hidden],
template{
	display: none;
}

a{
	background-color: transparent;
	text-decoration:none;
}

a:active,
a:hover{
	outline: 0;
	text-decoration:underline;
	cursor: pointer;
}

abbr[title]{
	border-bottom: 1px dotted;
}

b,
strong{
	font-weight: bold;
}

dfn{
	font-style: italic;
}

h1{
	margin: 0.67em 0;
	font-size: 2em;
}

mark{
	background: #ff0;
	color: #000;
}

small{
	font-size: 80%;
}

sub,
sup{
	vertical-align: baseline;
	line-height: 0;
	position: relative;
	font-size: 75%;
}

sup{
	top: -0.5em;
}

sub{
	bottom: -0.25em;
}

img{
	border: 0;
}

svg:not(:root){
	overflow: hidden;
}

figure{
	margin: 1em 40px;
}

hr{
	height: 0;
	-moz-box-sizing: content-box;
	box-sizing: content-box;
}

pre{
	overflow: auto;
}

code,
kbd,
pre,
samp{
	font-family: monospace, monospace;
	font-size: 1em;
}

button,
input,
optgroup,
select,
textarea{
	margin: 0;
	color: inherit;
	font: inherit;
}

button{
	overflow: visible;
}

button,
select{
	text-transform: none;
}

button,
html input[type="button"],
input[type="reset"],
input[type="submit"]{
	cursor: pointer;
	-webkit-appearance: button;
}

button[disabled],
html input[disabled]{
	cursor: default;
}

button::-moz-focus-inner,
input::-moz-focus-inner{
	padding: 0;
	border: 0;
}

input{
	line-height: normal;
}

input[type="checkbox"],
input[type="radio"]{
	padding: 0;
	box-sizing: border-box;
}

input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button{
	height: auto;
}

input[type="search"]{
	-moz-box-sizing: content-box;
	-webkit-box-sizing: content-box;
	box-sizing: content-box;
	-webkit-appearance: textfield;
}

input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration{
	-webkit-appearance: none;
}

fieldset{
	margin: 0 2px;
	padding: 0.35em 0.625em 0.75em;
	border: 1px solid #c0c0c0;
}

legend{
	padding: 0;
	border: 0;
}

textarea{
	overflow: auto;
}

optgroup{
	font-weight: bold;
}

table{
	border-collapse: collapse;
	border-spacing: 0;
}

td,
th{
	padding: 0;
}


/*------------------------------------------------------------
���Ѓe���v���[�g�̋��ʐݒ�
-------------------------------------------------------------*/

html{
	overflow-y: scroll;
}

body{
	font-family:"�q���M�m�p�S Pro W3", "Hiragino Kaku Gothic Pro", "���C���I", Meiryo, Osaka, "�l�r �o�S�V�b�N", "MS PGothic", sans-serif;
	/*font-family: Verdana, "�q���M�m�p�S ProN W3", "Hiragino Kaku Gothic ProN", "���C���I", Meiryo, sans-serif;*/
}

a{
	-webkit-transition: 0.3s;
	-o-transition: 0.3s;
	transition: 0.3s;
	color: #03c;
}
a:hover,
a:active,
a:focus{
	color: #f60;
}

address,
caption,
cite,
code,
dfn,
var,
h1,
h2,
h3,
h4,
h5,
h6{
	font-style: normal;
	font-weight: normal;
}

q{
	quotes: none;
}

q:before,q:after{
	content: '';
	content: none;
}

img{
	vertical-align: bottom;
	-ms-interpolation-mode: bicubic;
}

div{
	word-wrap: break-word;
}

pre{
	overflow: auto;
	white-space: pre-wrap;
	word-wrap: break-word;
}

form{
	margin: 0;
}

button,
input,
select,
textarea,
optgroup,
option{
	vertical-align: baseline;
}

textarea{
	min-height: 100px;
	vertical-align: top;
}

button::-moz-focus-inner,
input::-moz-focus-inner{
	margin: 0;
}

table{
	width: 100%;
	word-break: break-all;
	word-wrap: break-word;
	border-spacing: 0;
}

caption{
	text-align: left;
}

img{
	height: auto;
	max-width: 100%;
}

img{
	max-width: none\9;/*IE8�ւ̑Ή�*/
}

html:not(:target) img{
    max-width: 100%; /*IE9�ȏ�ւ̑Ή�*/
}

p{
	margin: 0 0 1em;
}

ul,
ol{
	margin-left: 30px;
	padding-left: 0;
}

li{
	margin-bottom: 0.5em;
}

/*���p*/
blockquote{
	position: relative;
	margin: 2em 0;
	padding: 115px 45px 80px;
	background: #eeeeee;
}

blockquote p:last-child{
	margin-bottom: 0;
}

blockquote:before{
	position: absolute;
	top: 40px;
	left: 30px;
	width: 58px;
	height: 45px;
	content: url(./images/icon/icon-laquo.png);
}

blockquote:after{
	position: absolute;
	right: 30px;
	bottom: 20px;
	width: 58px;
	height: 45px;
	content: url(./images/icon/icon-raquo.png);
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		blockquote:before{
			display: inline-block;
			width: 58px;
			height: 45px;
			vertical-align: middle;
			background: url(./images/icon/icon-laquo@2x.png);
			-webkit-background-size: 58px 45px;
			background-size: 58px 45px;
			content: " ";
		}

		blockquote:after{
			display: inline-block;
			width: 58px;
			height: 45px;
			vertical-align: middle;
			background: url(./images/icon/icon-raquo@2x.png);
			-webkit-background-size: 58px 45px;
			background-size: 58px 45px;
			content: " ";
		}

	}

blockquote a{
	color: #15a5e6;
}

blockquote a:hover,
blockquote a:active,
blockquote a:focus{
	color: #f60;
}

q{
	background: #ccc;
}

table{
	width: 100%;
	margin: 1em 0;
	padding: 0;
	border-top: 1px solid #cfcfcf;
	border-left: 1px solid #cfcfcf;
}

th,
td{
	padding: 0.4em 0.4em;
	border-right: 1px solid #cfcfcf;
	border-bottom: 1px solid #cfcfcf;
}

th{
	background-color: #e2e2e2;
	font-weight: bold;
	text-align: left;
}

thead th{
	background-color: #9aa4af;
	color: #fff;
	text-align: center;
}

dd{
	margin-left: 0;
	padding-left: 1em;
}

figure{
	margin: 1em 0;
}


/*--------------------------------------------------------
�e���v���[�g���C�A�E�g
--------------------------------------------------------*/

.container{
	position: relative;
}
.site-header-in,
.global-nav-in,
.main-image-in,
.main-image-in-text,
.main-image-in-text-cont,
.main-copy,
.sub-copy,
.main-image-in-text-box,
.main-body-in,
.site-footer-in{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	width: 1200px; /*�T�C�g�̉����B�����菬������΃��X�|���V�u*/
	margin: auto;
}

.main-image-in img{
	width: 100%;
}

.main-image-in.wide,
.main-image-in-text.wide{
	width: 100%;
}

/*1�J�������C�A�E�g*/
.col1 .main-body-in{
	width: 100%;
}

.col1 .breadcrumbs{
	width: 1200px;
	margin-right: auto;
	margin-left: auto;
}

/*2�J�������C�A�E�g*/
.col2 .main-conts{
	float: left;
	width: 65%;
}

.col2 .sub-conts{
	float: right;
	width: 30%;
}

/*2�J�������C�A�E�g�i���o�[�X�j*/
.col2r .main-conts{
	float: right;
	width: 65%;
}

.col2r .sub-conts{
	float: left;
	width: 30%;
}


/*--------------------------------------------------------
�w�b�_�[
--------------------------------------------------------*/

.site-header-conts{
	display: table;
	width: 100%;
	padding: 20px 0;
}
	
/*�w�b�_�[���S*/
.site-title{
	display: table-cell;
	margin: 0;
	font-size: 2.25em;
}

.site-title a{
	color: #333;
	text-decoration: none;
}

.site-title a:hover,
.site-title a:active,
.site-title a:focus{
	text-decoration: underline;
}

.normal-screen .site-title{
	font-size: 3em;
}

.normal-screen .lp-catch{
	font-size: 1.5em;
}

/*�w�b�_�[�E���̗v�f*/
.header-box{
	display: table-cell;
	text-align: right;
}

/*�w�b�_�[�̑S��ʕ\��*/
.full-screen{
	background: url(./images/lp-image.jpg) center center no-repeat;
	-webkit-background-size: cover;
	background-size: cover;
	color: #fff;
}

.full-screen .site-header-in{
	display: table;
}

.full-screen .site-header-conts{
	position:relative;
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	overflow: hidden;
	width: 100%;
	padding: 1em;
	text-align: center;
	vertical-align: middle;
	text-shadow: 1px 1px 8px #666;
}

.full-screen .site-title{
	display: block;
}

.contact-btn{
	margin-bottom: 0;
}

.full-screen .site-header-conts h1{
	width: auto;
	padding:1em 0 0;
	margin: 0;
}

.full-screen .site-header-conts p{
	font-size: 2em;
}

.full-screen .site-header-conts p.lp-catch{
	position:absolute;
	bottom:0;
	left:0;
	right:0;
	padding:0.5em 0;
	margin-bottom:0!important;
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr=#80000000,endColorstr=#80000000);/*IE8�̓��ߑ΍�*/
	background-color: rgba(00,00,00, 0.5);/*���C���r�W���A���w�i�̓��ߗ�*/
}

.full-screen .site-header-conts p.lp-catch:not(:target){
	filter: none;
}

.full-screen .site-header-conts p a{
	color: #fff;
	text-decoration: none;
}

/*--------------------------------------------------------
�O���[�o���i�r
--------------------------------------------------------*/

.global-nav{
	padding: 0;
	background:#007db8;
	border-bottom:1px solid #007db8;
}

/*�O���[�o���i�r�̊J�p�{�^��*/
.global-nav-panel{
	display: none;
	font-size: 12px;
}

.global-nav-panel span{
	display: block;
	min-height: 20px;
	line-height: 20px;
}

.icon-gn-menu{
	padding-left: 25px;
	background: url(./images/icon/icon-gn-menu.png) left center no-repeat;
}

.icon-gn-close{
	padding-left: 25px;
	background: url(./images/icon/icon-gn-close.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-gn-menu{
			background: url(./images/icon/icon-gn-menu@2x.png) left center no-repeat;
			-webkit-background-size: 20px 20px;
			background-size: 20px 20px;
		}

		.icon-gn-close{
			background: url(./images/icon/icon-gn-close@2x.png) left center no-repeat;
			-webkit-background-size: 20px 20px;
			background-size: 20px 20px;
		}
	}

.global-nav .show-menu,
.global-nav .show-menu li ul{
	display: block!important;
}

.global-nav-in ul{
	display: table;
	width: 100%;
	margin: 0;
	padding: 0;
	border-left: 1px dotted #fff;
	table-layout: fixed; /*���j���[�̕����ϓ���*/
}

.global-nav-in li{
	display: table-cell;
	list-style: none;
	position: relative;
	vertical-align: middle;
	margin: 0;
	text-align: center;
}

.global-nav-in li a{
	display: block;
	min-height: 1.5em; /*���j���[���ɍ������ς��Ƃ��ɒ���*/
	padding: 1em 1em; /*�摜�����j���[�ɂ���ꍇ�͒l��0��*/
	border-right: 1px dotted #fff;
	background-color: #007db8;
	color: #fff;
	text-decoration: none;
}

.global-nav-in li a:hover,
.global-nav-in li a:active,
.global-nav-in li a:focus,
.global-nav-in li:hover > a{
	background-color: #0098de;
	color: #FFFFFF;
}

.global-nav-in li ul{
	display: none;
	position: absolute;
	top: 100%;
	left: 0;
	z-index: 10;
	width: 100%;
	border-left: 0;
}

.global-nav-in li ul:not(:target){
	filter: none;
}

/*�h���b�v�_�E�����j���[�̃f�U�C��*/
.global-nav li ul li{
	display: list-item;
	width: 100%;
	margin: 0;
	padding: 0;
	border-top: 0;
	border-right: 0;
	border-bottom: 1px solid #dadada;
	white-space: normal;
}

.global-nav li ul li a{
	display: block;
	padding: 0.8em 1em;
}

.global-nav-in li ul li:hover > a{
	background-color: #eeeeee;
	color: #1a242f;
}

.global-nav-in li ul ul{
	top: 0;
	left: 100%;
}


/*--------------------------------------------------------
���C���r�W���A��
--------------------------------------------------------*/

.main-image{
	margin-bottom: 2em;
	
}

.main-image-in-text{
	position:relative;
	min-height:500px;
	padding:150px 0 0;
	background-size: cover;
}

.main-image-in-text-cont{
	padding:2em 0;
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr=#4D34495e,endColorstr=#4D34495e);/*IE8�̓��ߑ΍�*/
	background-color: rgba(52, 73, 94, 0.30);/*���C���r�W���A���w�i�̓��ߗ�*/
	box-sizing: border-box;
	-webkit-box-sizing: border-box;
	color:#fff;
}

.main-image-in-text-cont:not(:target){
	filter: none;
}

.main-image-in-text.wide .main-image-in-text-cont{
	width: 100%;
}

.main-image-in-text p:last-child{
	margin-bottom: 0;
}

.main-copy{
	margin:0 auto 25px;
	padding:25px 400px 0 20px;
	font-size: 3em;
	text-shadow: 2px 2px 3px #333333;	/*���C���R�s�[�e�L�X�g�̉e�ݒ�*/
	-moz-box-shadow: 2px 2px 3px #333333;�@/* Firefox�p */
	-webkit-box-shadow: 2px 2px 3px #333333;�@/* Safari,Google Chrome�p */
}

.sub-copy{
	margin:0 auto;
	padding:0 400px 25px 20px;
	font-size: 1.725em;
	text-shadow: 2px 2px 3px #000000;	/*�T�u�R�s�[�e�L�X�g�̉e�ݒ�*/
	-moz-box-shadow: 2px 2px 3px #000000;�@/* Firefox�p */
	-webkit-box-shadow: 2px 2px 3px #000000;�@/* Safari,Google Chrome�p */
}

.main-image-in-text-box{
	position:absolute;
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	z-index:1;
	height:500px;
	margin:auto;
}

.main-image-in-text-box .contact-btn{
	position:absolute;
	left:20px;
	bottom:60px;
}

/*--------------------------------------------------------
���C���{�f�B
--------------------------------------------------------*/

.main-body{
	margin-top: 2em;
	padding-bottom: 30px;
}

.no-gn .main-body{
	margin-top: 0;
}

.lp.no-gn .main-body{
	margin-top: 2em;
}


/*--------------------------------------------------------
�p���������X�g
--------------------------------------------------------*/

.breadcrumbs-in{
	margin: 2em 0;
	padding: 0;
	color: #999;
}

.no-gn .breadcrumbs-in{
	margin-top: 0;
}

.breadcrumbs-in a{
	color: #999;
}

.breadcrumbs-in a:hover,
.breadcrumbs-in a:active,
.breadcrumbs-in a:focus{
	color: #f60;
}

.breadcrumbs-in li{
	display: inline-block;
	list-style: none;
	position: relative;
	margin-right: 15px;
	padding-right: 15px;
	background: url(./images/icon/icon-brc.gif) right center no-repeat;
}

.breadcrumbs-in li:before{
	content: url(./images/icon/icon-folder-brc.png);
}

.breadcrumbs-in li.bcl-first:before{
	content: url(./images/icon/icon-home-brc.png);
}

.breadcrumbs-in li.bcl-last{
	background: none;
}

.breadcrumbs-in li.bcl-last:before{
	content: none;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){	

		.breadcrumbs-in li{
			background: url(./images/icon/icon-brc@2x.gif) right center no-repeat;
			-webkit-background-size: 5px 9px;
			background-size: 5px 9px;
		}

		.breadcrumbs-in li:before{
			width: 12px;
			height: 12px;
			background: url(./images/icon/icon-folder-brc@2x.png);
		}

		.breadcrumbs-in li.bcl-first:before{
			width: 12px;
			height: 12px;
			background: url(./images/icon/icon-home-brc@2x.png);
		}

		.breadcrumbs-in li:before,
		.breadcrumbs-in li.bcl-first:before{
			display: inline-block;
			vertical-align: middle;
			-webkit-background-size: contain;
			background-size: contain;
			content: " ";
		}

		.breadcrumbs-in li.bcl-last:before{
			width: 0;
			height: 0;
			background: none;
			content: none;
		}
	}


/*--------------------------------------------------------
���C���R���e���c
--------------------------------------------------------*/
.main-conts{
	line-height: 1.8;
	font-size:1.1em;
}

.col1 .main-conts{
	margin-bottom: 40px;
}

/*�R���e���c�̊�{�P�ʁi�usection-wrap�v�{�usection-in�v�ŃR���e���c�𕢂��j*/
.section-wrap{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	margin-bottom: 30px;
	padding: 0;
	border-bottom:1px dotted #ccc;
}

.section-wrap.wide{
	border-right: 0;
	border-left: 0;
}

.section-wrap .section-in,
.float-area{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
}

.float-area{
	margin-bottom: 10px;
}

/*1�J�������C�A�E�g*/
.col1 .section-wrap,
.col1 .float-area{
	width: 1200px;
	margin-right: auto;
	margin-left: auto;
}

.col1 .section-wrap{
	padding: 40px 80px;
}

.col1 .section-wrap.wide{
	width: 100%;
	padding: 40px 0;
}

.col1 .section-wrap.wide .section-in{
	width: 1200px;
	margin-right: auto;
	margin-left: auto;
	padding: 30px 0;
}

/*--------------------------------------------------------
�T�u�R���e���c
--------------------------------------------------------*/
.sub-conts .section-wrap{
	margin: 0 auto;
	padding: 0;
	border: none;
	font-size:.9em;
}

.sub-conts .section-wrap .section-in{
	padding: 0  15px 10px;
}

.col1 .sub-conts .section-wrap .section-in{
	padding: 30px 80px 30px;
}

/*�T�u�R���e���c�p���j���[�̃f�U�C��*/
.sub-conts .link-menu{
	margin-left: 0;
	padding-left: 0;
}

.sub-conts .link-menu li{
	list-style: none;
	margin-bottom: 1em;
	padding-left: 13px;
	background: url(./images/icon/icon-list-arw.png) left 6px no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.sub-conts .link-menu li{
			background: url(./images/icon/icon-list-arw@2x.png) left 6px no-repeat;
			-webkit-background-size: 7px 10px;
			background-size: 7px 10px;
		}

	}

.sub-conts .link-menu ul{
	margin-top: 1em;
	margin-left: 10px;
	padding-left: 0;
}

.sub-conts .link-menu-image{
	margin-right: 0;
	margin-left: 0;
}

.sub-conts .link-menu-image li{
	list-style: none;
	overflow: hidden;
	margin-bottom: 20px;
	padding-bottom: 20px;
	border-bottom: 1px dotted #ccc;
}

.sub-conts .link-menu-image li:last-child{
	margin-bottom: 0;
	padding-bottom: 0;
	border-bottom: none;	
}

.link-menu-image-thumb{
	float: left;
	margin-right: 1em;
}

.sub-conts .link-menu-image .post-title{
	overflow: hidden;
	margin-bottom: 0;
	padding: 5px 0;
	border: none;
	background: none;
	font-weight: normal;
}

/*--------------------------------------------------------
�t�b�^�[
--------------------------------------------------------*/
.site-footer{
	background: #aaaaaa;
	color: #fff;
}

.site-footer-in a{
	color: #fff;
}

.site-footer-in a:hover,
.site-footer-in a:active,
.site-footer-in a:focus{
	color: #f60;
}

/*�t�b�^�[�i�r*/
.site-footer-nav{
	margin: 0 auto;
	padding: 1em 0;
	text-align: center;
}

.site-footer-nav li{
	display: inline;
	list-style: none;
	margin-left: 50px;
	padding: 0 0 0 13px;
	background: url(./images/icon/icon-arw-next02.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.site-footer-nav li{
			background: url(./images/icon/icon-arw-next02@2x.png) left center no-repeat;
			-webkit-background-size: 7px 10px;
			background-size: 7px 10px;
		}

	}

.site-footer-nav li:first-child{
	margin-left: 0;
}

.site-footer-conts-area{
	padding: 1em 0;
}
/*�R�s�[���C�g*/
.copyright{
	margin: 0;
	padding: 15px 0;
	background: #007db8;
	color: #fff;
	text-align: center;
}

.copyright small{
	font-size: 100%;
}

/*�y�[�W�g�b�v�{�^��*/
.page-top{
	display: none;
	position: fixed;
	right: 20px;
	bottom:0;
	z-index: 99;
	line-height: 1.2;
	margin-bottom: 0;
}


/*--------------------------------------------------------
���o��
--------------------------------------------------------*/

.section-in > h1:first-child,
.section-in > h2:first-child,
.section-in > h3:first-child,
.section-in > h4:first-child,
.section-in > h5:first-child,
.section-in > h6:first-child{
	margin-top: 0;
}

.main-body h1{
	margin: 60px 0 20px;
	padding: 10px 18px;
	background: #909090;
	color: #fff;
	font-size: 1.75em;
}

.main-body h2{
	background:#0098de;
	margin: 60px 0 30px;
	padding: 15px 20px;
	font-size: 1.6em;
	line-height:1.4;
	color:#fff;
	/*box-shadow: 0 2px 6px rgba(0, 0, 0, .25);*/
}

.main-body h3{
	border-bottom:2px solid #0098de;
	margin: 60px 0 30px;
	padding: 0 0 10px 10px;
	font-weight:bold;
	font-size: 1.4em;
}

.main-body h4{
	margin: 55px 0 25px;
	padding: 0 0 0 9px;
	border-left: 6px solid #1a242f;
	background: #f6f6f6;
	font-weight: bold;
	font-size: 1.25em;
}

.main-body h5{
	margin: 55px 0 25px;
	padding: 0 0 0 9px;
	border-left: 4px solid #1a242f;
	font-weight: bold;
	font-size: 1.2em;
}

.main-body h6{
	margin: 55px 0 25px;
	font-weight: bold;
	font-size: 1.125em;
}

/*�摜���g���ꍇ�ȂǂɌ��o���̃f�U�C��������*/
.main-body .img-title{
	padding: 0;
	border: none;
	background: none;
	border-radius: 0;
	box-shadow: none;
	font-weight: normal;
	font-size: 1.0em;
}

.main-body h1 a,
.main-body h2 a{
	color: #fff;
}

.main-body h1 a:hover,
.main-body h2 a:hover,
.main-body h1 a:active,
.main-body h2 a:active,
.main-body h1 a:focus,
.main-body h2 a:focus{
	color: #f60;
}

/*�R���e���c�̊O�ɂ��錩�o��*/
.main-body .archive-title{
	margin: 0 0 30px;
	background:#1a242f;
	font-size:1.125em;
}

.col1 .main-body .archive-title{
	max-width: 1200px;
	margin-right: auto;
	margin-left: auto;
}

/*�L���^�C�g�����{�P�ʖ��̍ŏ��̌��o��*/
.section-wrap .section-title{
	line-height: 1.5;
	margin: 0 0 1em;
	padding: 0;
	border: none;
	background: transparent;
	color: #333;
	font-size: 1.8em;
	box-shadow: 0 0 0 rgba(0, 0, 0, 0);
}

.main-body .section-title a{
	color: #333;
}

.main-body .section-title a:hover,
.main-body .section-title a:active,
.main-body .section-title a:focus{
	color: #f60;
	text-decoration: underline;
}

.sub-conts .section-wrap .section-in .section-title,
.sub-conts .section-wrap .article-header .section-title,
.sub-conts h3{
	border-left:7px solid #009844;
	border-bottom:0;
	margin: 0 -10px 30px;
	padding: 7px 15px;
	background:#0dac67;
	font-weight: bold;
	font-size: 1.125em;
	color:#fff;
}

.section-wrap h2.section-title {
	padding:10px 20px;
	background:#DAF3FD;
	font-size:1.3em;
	font-weight:normal;
}
.sub-conts h4{
	background-color:#f9f9f9;
}

/*--------------------------------------------------------
�p�[�c���̃X�^�C��
--------------------------------------------------------*/

/*�ŐV���*/
.news .news-date{
	margin-right: 1em;
}

.news-item{
	padding: 1em;
	border-bottom: 1px dotted #ccc;
}

.news-item:first-child{
	padding-top: 0;
}

.news-item:last-child{
	border-bottom: 0;
}

.news .news-thumb{
	float: left;
	margin-right: 15px;
	margin-bottom: 15px;
}

.main-body .news-title,
.main-body .news-title::after{
	margin-top: 20px;
	padding: 0;
	border: none;
	background: none;
	font-weight: normal;
	font-size: 1.4em;
	line-height:1.6;
}

.main-body .news-item:first-child .news-title{
	margin-top: 0;
}

.news .news-date,
.news .news-cat,
.post-cat{
	display: inline-block;
	margin-bottom: 10px;
}

.cat{
	display: inline-block;
	margin-right: 0.5em;
	margin-bottom: 5px;
	padding: 0.1em 0.5em;
	border-bottom: none;
	color: #fff;
	font-size: 0.875em;
	word-break: break-all;
	border-radius: 3px;
}

.cat a{
	display: inline-block;
	margin: -0.1em -0.5em;
	padding: 0.1em 0.5em;
	color: #fff;
	text-decoration: none;
}

.cat001{ background: #4fc3f7; }
.cat002{ background: #ff8a65; }
.cat003{ background: #4db6ac; }
.cat004{ background: #ba68c8; }
.cat005{ background: #90a4ae; }

.news .news-cont{
	margin-bottom: 0.5em;
}

/*�L�q���X�g ������*/
.dl-style01 dt,
.dl-style01 dd{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	padding: 20px;
}

.dl-style01 dt{
	display: block;
	float: left;
	width: 35%;
}

.dl-style01 dd{
	padding-left: 35%;
	border-bottom: 1px dotted #909090;
}

/*�L�q���X�g �c����*/
.dl-style02 dt,
.dl-style02 dd{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	padding: 20px;
	border-bottom: 1px solid #fff;
}

.dl-style02 dt{
	display: block;
	background: #9aa4af;
	color: #fff;
}

.dl-style02 dd{
	background: #f6f6f6;
}

/*�e�[�u���i�������͂ݏo��ꍇ�Ƀe�[�u�����͂ޗv�f�ɐݒ�j*/
.table-scroll{
	overflow-x: auto;
	-webkit-overflow-scrolling: touch;
}

.table-comparison{
	margin: 3em 0;
	border-top: 0;
}

.table-comparison th,
.table-comparison td{
	padding: 10px;
	text-align: center;
}

.table-comparison thead .highlight span{
	display: block;
	margin: -11px;
	margin-top: -25px;
	padding: 11px;
	padding-top: 25px;
	border: 1px solid #cfcfcf;
	border-radius: 8px 8px 0 0;
}

.table-comparison th.highlight,
.table-comparison th.highlight span{
	background: #20374D;
}

.table-comparison tfoot td,
.table-comparison tfoot td span{
	background: #f2f2f2;
}

/*�J�e�S���[*/
.category-list,
.sub-conts .widget_categories ul{
	margin-left: 0;
	padding-left: 0;
}

.category-list li,
.sub-conts .widget_categories li{
	list-style: none;
	margin-bottom: 1em;
	padding-left: 15px;
	background: url(./images/icon/icon-tag.png) left 6px no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.category-list li,
		.sub-conts .widget_categories li{
			background: url(./images/icon/icon-tag@2x.png) left 6px no-repeat;
			-webkit-background-size: 12px 12px;
			background-size: 12px 12px;
		}

	}

.category-list ul,
.sub-conts .widget_categories ul ul{
	margin-top: 1em;
	margin-left: 10px;
	padding-left: 0;
}

/*�^�O�N���E�h*/
.tagcloud a{
	margin-right: 10px;
	padding-left: 15px;
	background: url(./images/icon/icon-tag.png) left bottom no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.tagcloud a{
			background: url(./images/icon/icon-tag@2x.png) left bottom no-repeat;
			-webkit-background-size: 12px 12px;
			background-size: 12px 12px;
		}

	}

/*�J�����_�[*/
.calendar{
	background: #fff;
	font-size: 0.875em;
}

.calendar caption{
	font-weight: bold;
}

.calendar th,
.calendar td{
	padding: 10px 0;
	text-align: center;
}

.calendar tfoot td{
	padding: 10px;
	border-right-width: 0;
	text-align: left;
}

.calendar tfoot td:last-child{
	border-right-width: 1px;
	text-align: right;
}

.calendar td a{
	display: block;
	margin: -10px 0;
	padding: 10px 0;
}

/*�i�g*/
.col4-wrap,
.col3-wrap,
.col2-wrap{
/*	margin: 0 0 1em;*/
}

.col4-wrap .col,
.col4-wrap .col_2of4,
.col4-wrap .col_3of4,
.col3-wrap .col,
.col3-wrap .col_2of3,
.col2-wrap .col{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	float: left;
	margin-left: 2%;
}

.col4-wrap .col:first-child,
.col4-wrap .col_2of4:first-child,
.col4-wrap .col_3of4:first-child,
.col3-wrap .col:first-child,
.col3-wrap .col_2of3:first-child,
.col2-wrap .col:first-child{
	margin-left: 0;
}

.col4-wrap .col{
	width: 23.5%;
}

.col4-wrap .col_2of4{
	width: 49%;
}

.col4-wrap .col_3of4{
	width: 74.5%;
}

.col3-wrap .col{
	width: 32%;
}

.col3-wrap .col_2of3{
	width: 66%;
}

.col2-wrap .col{
	width: 49%;
}

.col-link{
	border: 1px solid #ccc;
}

.col-link a{
	display: block;
	color: #333;
	text-decoration: none;
}

.col-link a:hover,
.col-link a:active,
.col-link a:focus{
	background: #eee;
}

/*�o�i�[�G���A*/
.banner-list{
	margin-left: 0;
}

.banner-list li{
	list-style: none;
}

.col1 .banner-list{
	text-align: center;
}

.col1 .banner-list li,
.main-conts .banner-list li{
	display: inline-block;
	margin-bottom: 1em;
}

.col1 .banner-list li:first-child,
.main-conts .banner-list li:first-child{
	margin-left: 0;
}

/*���p���ւ̃����N*/
.link-ref{
	text-align: right;
}

/*����Ȃǂ̃��X�|���V�u�Ή�*/
embed, iframe, object, video{
	max-width: 100%;
}

/*�{�^��*/
.btn{
	display: inline-block;
	padding: 1em;
	border: 0;
	background: #1a242f;
	color: #fff;
	text-decoration: none;
	border-radius: 8px;
	box-shadow: 4px 4px 0px #d0d0d0;
}

.btn:hover,
.btn:active,
.btn:focus{
	background: #555555;
	color: #FFF;
	box-shadow: 4px 4px 0px #e9e9e9;
	cursor: pointer;
}

.btn span{
	padding-left: 18px;
	background: url(./images/icon/icon-btn-arw.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.btn span{
			padding-left: 18px;
			background: url(./images/icon/icon-btn-arw@2x.png) left center no-repeat;
			-webkit-background-size: 10px 14px;
			background-size: 10px 14px;
		}

	}

.btn-green{
	padding: 25px 50px;
	background: linear-gradient(to bottom, #7ef0a6, #27ac65, #027b3b);
/*	background: #16a085;*/
	font-size: 1.25em;
	/*box-shadow: 4px 4px 0px #58942c;*/
}

.btn-green:hover,
.btn-green:active,
.btn-green:focus{
	/*background: #38c4a9;*/
	background: linear-gradient(to bottom,  #9ef0bc, #64c390, #4da376);
	/*box-shadow: 4px 4px 0px #acca96;*/
	cursor: pointer;
}

.btn-blue{
	padding: 25px 50px;
/*	background: #1f8ae5; */
	background: linear-gradient(to bottom, #78bcff, #4299ff, #0362ff);
	font-size: 1.25em;
	/*box-shadow: 4px 4px 0px #1767ac;*/
}

.btn-blue:hover,
.btn-blue:active,
.btn-blue:focus{
	/* background: #8fc5f2; */
	background: linear-gradient(to bottom,  #9ccdff, #76b4ff, #5194ff);
	/*box-shadow: 4px 4px 0px #8bb3d6;*/
	cursor: pointer;
}

.btn-orange{
	padding: 25px 50px;
	background: #f59e38;
	font-size: 1.25em;
	/*box-shadow: 4px 4px 0px #b8762a;*/
}

.btn-orange:hover,
.btn-orange:active,
.btn-orange:focus{
	background: #facf9c;
	/*box-shadow: 4px 4px 0px #dcbb95;*/
	cursor: pointer;
}

.btn-red{
	padding: 25px 50px;
	background: linear-gradient(to bottom, #fc7e7e, #f21f1f, #cb0000);
/*	background: #fe7151; */
	font-size: 1.25em;
	/*box-shadow: 4px 4px 0px #be3a1c;*/
}

.btn-red:hover,
.btn-red:active,
.btn-red:focus{
/*	background: #ffa792; */
	background: linear-gradient(to bottom,  #fc9f9f, #f76b6b, #de4d4d);
	/*box-shadow: 4px 4px 0px #df9d8e;*/
	cursor: pointer;
}

.btn-green span,
.btn-blue span,
.btn-orange span,
.btn-red span{
	padding-left: 20px;
	background: url(./images/icon/icon-btn-arw01.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.btn-green span,
		.btn-blue span,
		.btn-orange span,
		.btn-red span{
			background: url(./images/icon/icon-btn-arw01@2x.png) left center no-repeat;
			-webkit-background-size: 10px 14px;
			background-size: 10px 14px;
		}

	}

.btn-form01{
	padding: 25px 50px;
	background: #1a242f;
	font-size: 1.25em;
}

.btn-form01 span{
	padding-left: 20px;
	background: url(./images/icon/icon-btn-arw01.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.btn-form01 span{
			background: url(./images/icon/icon-btn-arw01@2x.png) left center no-repeat;
			-webkit-background-size: 10px 14px;
			background-size: 10px 14px;
		}

	}

.btn-form02{
	padding: 20px 30px;
	background: #c9c9c9;
	font-size: 1.125em;
	color: #666666;
}

.btn-form02 span{
	padding-left: 18px;
	background: url(./images/icon/icon-btn-arw02.png) left center no-repeat;
}

.btn-form02:hover span,
.btn-form02:active span,
.btn-form02:focus span{
	padding-left: 18px;
	background: url(./images/icon/icon-btn-arw01.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.btn-form02 span{
			background: url(./images/icon/icon-btn-arw02@2x.png) left center no-repeat;
			-webkit-background-size: 10px 14px;
			background-size: 10px 14px;
		}
		
		.btn-form02:hover span,
		.btn-form02:active span,
		.btn-form02:focus span{
			background: url(./images/icon/icon-btn-arw01@2x.png) left center no-repeat;
			-webkit-background-size: 10px 14px;
			background-size: 10px 14px;
		}
	}

.btn-mail{
	padding: 12px 32px;
	background: #1a242f;
}

.btn-mail span{
	padding-left: 30px;
	background: url(./images/icon/icon-btn-mail.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.btn-mail span{
			background: url(./images/icon/icon-btn-mail@2x.png) left center no-repeat;
			-webkit-background-size: 24px 18px;
			background-size: 24px 18px;
		}

	}

.btn-detail{
	background: #909090;
}

.btn-detail span{
	padding-left: 20px;
	background: url(./images/icon/icon-btn-arw01.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.btn-detail span{
			background: url(./images/icon/icon-btn-arw01@2x.png) left center no-repeat;
			-webkit-background-size: 10px 14px;
			background-size: 10px 14px;
		}

	}

/*�����{�b�N�X*/
.search-box {
	margin-left:45px;
}
.search-box input[type="text"]{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	width: 75%;
	height: 30px;
	margin-top:15px;
	padding-right: 4px;
	padding-left: 4px;
	border: 1px solid #ccc;
	border-radius: 0;
	box-shadow: inset 1px 3px 2px #eee;
}

.btn-search{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	height: 30px;
	vertical-align: top;
	margin-top:15px;
	padding: 5px;
	border: 0;
	background: #8f8f8f;
	border-radius: 0;
	cursor: pointer;
}

.btn-search img{
	width: 21px;
	height: 20px;
	vertical-align: top;
}

/*�\�[�V�����{�^��*/
.sns-list ul{
	margin: 0 0 1em;
	padding: 0;
}

.sns-list li{
	display: inline-block;
	vertical-align: top;
	line-height: 1.0;
	margin-left: 1em;
}

.sns-list li iframe{
	max-width: none;
	margin: 0;
}

.sns-list li:first-child{
	margin-left: 0;
}

/*�A�C�L���b�`*/
.eye-catch{
	float: left;
	margin-right: 1em;
	margin-bottom: 1em;
}

.post-date,
.post-pv{
	display: inline-block;
	margin-right: 1em;
	margin-bottom: 0.5em;
}

/*�o��l���Љ�P*/
.cast-box{
	padding: 30px 20px 20px;
}

.cast-box .cast{
	margin: 0 0 1.5em;
}

.cast-box .cast-name{
	margin-bottom:0.5em;
	padding:0.25em 1em;
	background:#9aa4af;
	color:#FFF;
	font-weight: bold;
	font-size: 1.25em;
}

.cast-box .cast .cast-headshot,
.cast-box .cast .cast-profile{
	margin-left: 0;
	margin-bottom: 40px;
	padding-right: 0;
}

.cast-box .cast:last-child,
.cast-box .cast:last-child .cast-headshot,
.cast-box .cast:last-child .cast-profile{
	margin-bottom: 0;
}

.cast-box .cast .cast-headshot{
	margin:10px 10px 10px 0;
	float:left;
	/*position: absolute;
	top: -10px;
	right: 10px;*/
}

.cast-box .cast .cast-profile{
	padding: 10px 10px 0 130px;
}

/*�o��l���Љ�Q*/
.cast-box02 .cast{
	position: relative;
	margin-bottom: 20px;
}

.cast-box02 .cast dd{
	padding-left: 0;
}

.cast-box02 .cast-name{
	position:absolute;
	top:150px;
	left:0;
	right:0;
	z-index:1;
	width:198px;
	max-width:100%;
	margin:0 auto;
	padding:0.5em 0;
	border-top:1px solid #848484;
	border-bottom:1px solid #848484;
	background-color: rgba(60,60,60,0.5);
	background-color: #3c3c3c\9; /*IE8�ւ̑Ή�*/
	color:#FFF;
	text-align:center;
	font-weight: bold;
}

html:not(:target) .cast-box02 .cast-name{
 background-color: rgba(60,60,60,0.5); /*IE9�ȏ�ւ̑Ή�*/
}

.cast-box02 .cast .cast-headshot{
	position:relative;
	width: 100%;
	text-align: center;
	margin-bottom:1em;
}

.col1 .cast-box02 .cast{
	padding-top: 0;
}

.col1 .cast-box02 .cast .cast-headshot{
	width: auto;
}

/*�����o��*/
.chat-l,
.chat-r{
	position: relative;
	overflow: hidden;
	margin: 0 0 2em;
}

.bubble{
	display: block;
	position: relative;
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	width: 80%;
	min-height: 60px;
	margin-bottom: 2em;
	padding: 1em;
	border: 1px solid #ccc;
	background: #fff;
}

.bubble .bubble-in{
	border-color: #fff;
}

.talker{
	display: block;
	width: 15%;
	height: auto;
	text-align: center;
}

.talker b{
	font-weight: normal;
}

.talker img{
 	display: block;
 	width: 100px;
 	max-width: 100%;
 	max-width: none\9;/*IE8�ւ̑Ή�*/
 	margin: auto;
}

html:not(:target) .talker img{
    max-width: 100%; /*IE9�ȏ�ւ̑Ή�*/
}

.chat-l .talker{
	float: left;
	margin-right: 2%;
}

.chat-r .talker{
	float: right;
	margin-left: 2%;
}

.chat-l .bubble{
	float: right;
}

.chat-r .bubble{
	float: left;
}

.bubble .bubble-in:after,
.bubble .bubble-in:before{
	position: absolute;
	top: 50%;
	width: 0;
	height: 0;
	border: solid transparent;
	content: "";
}

/*�����o���̔�����*/
.bubble .b-arw20:after,
.bubble .b-arw20:before{ top: 20%; }
.bubble .b-arw30:after,
.bubble .b-arw30:before{ top: 30%; }
.bubble .b-arw40:after,
.bubble .b-arw40:before{ top: 40%; }
.bubble .b-arw60:after,
.bubble .b-arw60:before{ top: 60%; }
.bubble .b-arw70:after,
.bubble .b-arw70:before{ top: 70%; }
.bubble .b-arw80:after,
.bubble .b-arw80:before{ top: 80%; }

.chat-l .bubble .bubble-in:after,
.chat-l .bubble .bubble-in:before{
	right: 100%;
}

.chat-r .bubble div:after,
.chat-r .bubble div:before{
	left: 100%;
}

.chat-l .bubble .bubble-in:after{
	margin-top: -8px;
	border-width: 8px 20px;
	border-color: transparent;
	border-right-color: inherit;
}

.chat-l .bubble .bubble-in:before{
	margin-top: -9px;
	border-width: 9px 21px;
	border-color: transparent;
	border-right-color: #ccc;
}

.chat-r .bubble .bubble-in:after{
	margin-top: -8px;
	border-width: 8px 20px;
	border-color: transparent;
	border-left-color: inherit;
}

.chat-r .bubble .bubble-in:before{
	margin-top: -9px;
	border-width: 9px 21px;
	border-color: transparent;
	border-left-color: #ccc;
}

.bubble p:first-child{
	margin-top: 0;
}

/*�����o�� ��b�҂������l�̏ꍇ*/
.together .talker,
.together .bubble{
	width: 100%;
}

.together .talker b{
	display: inline-block;
	text-align: center;
}

.together.chat-l .talker,
.together.chat-r .talker{
	float: none;
	margin: 0 0 20px;
}

.together.chat-l .talker{
	text-align: left;
}

.together.chat-r .talker{
	text-align: right;
}

.together.chat-l .bubble,
.together.chat-r .bubble{
	float: none;
}

.together .bubble .bubble-in:after,
.together .bubble .bubble-in:before{
	top: auto;
	bottom: 100%;
}

.together.chat-l .bubble .bubble-in:after,
.together.chat-l .bubble .bubble-in:before{
	right: auto;
	left: 10%;
}

.together.chat-r .bubble .bubble-in:after,
.together.chat-r .bubble .bubble-in:before{
	right: 10%;
	left: auto;
}

.together.chat-l .bubble .bubble-in:after{
	margin-top: -20px;
	margin-left: -8px;
	border-width: 20px 8px;
	border-color: transparent;
	border-bottom-color: inherit;
}

.together.chat-l .bubble .bubble-in:before{
	margin-top: -21px;
	margin-left: -9px;
	border-width: 21px 9px;
	border-color: transparent;
	border-bottom-color: #ccc;
}

.together.chat-r .bubble .bubble-in:after{
	border-width: 20px 8px;
	margin-top: -20px;
	margin-right: -8px;
	border-color: transparent;
	border-bottom-color: inherit;
}

.together.chat-r .bubble .bubble-in:before{
	margin-top: -21px;
	margin-right: -9px;
	border-width: 21px 9px;
	border-color: transparent;
	border-bottom-color: #ccc;
}

.bubble-in p:last-child{
	margin-bottom: 0;
}

/*�����o���w�i�F�F�iHTML�ł̂݁j*/
.bubble-blue{
	border: 1px solid #e1f5fe;
	background: #e1f5fe;
}

.chat-l .bubble-blue .bubble-in:after,
.chat-l .bubble-blue .bubble-in:before{
	border-right-color: #e1f5fe;
}

.chat-r .bubble-blue .bubble-in:after,
.chat-r .bubble-blue .bubble-in:before{
	border-left-color: #e1f5fe;
}

.together.chat-l .bubble-blue .bubble-in:after,
.together.chat-l .bubble-blue .bubble-in:before,
.together.chat-r .bubble-blue .bubble-in:after,
.together.chat-r .bubble-blue .bubble-in:before{
	border-bottom-color: #e1f5fe;
}

/*�����o���w�i�F�F�΁iHTML�ł̂݁j*/
.bubble-green{
	border: 1px solid #e8f5e9;
	background: #e8f5e9;
}

.chat-l .bubble-green .bubble-in:after,
.chat-l .bubble-green .bubble-in:before{
	border-right-color: #e8f5e9;
}

.chat-r .bubble-green .bubble-in:after,
.chat-r .bubble-green .bubble-in:before{
	border-left-color: #e8f5e9;
}

.together.chat-l .bubble-green .bubble-in:after,
.together.chat-l .bubble-green .bubble-in:before,
.together.chat-r .bubble-green .bubble-in:after,
.together.chat-r .bubble-green .bubble-in:before{
	border-bottom-color: #e8f5e9;
}

/*�����o���w�i�F�F���iHTML�ł̂݁j*/
.bubble-yellow{
	border: 1px solid #fff8ba;
	background: #fff8ba;
}

.chat-l .bubble-yellow .bubble-in:after,
.chat-l .bubble-yellow .bubble-in:before{
	border-right-color: #fff8ba;
}

.chat-r .bubble-yellow .bubble-in:after,
.chat-r .bubble-yellow .bubble-in:before{
	border-left-color: #fff8ba;
}

.together.chat-l .bubble-yellow .bubble-in:after,
.together.chat-l .bubble-yellow .bubble-in:before,
.together.chat-r .bubble-yellow .bubble-in:after,
.together.chat-r .bubble-yellow .bubble-in:before{
	border-bottom-color: #fff8ba;
}

/*�����o���w�i�F�F�I�����W�iHTML�ł̂݁j*/
.bubble-orange{
	border: 1px solid #ffd699;
	background: #ffd699;
}

.chat-l .bubble-orange .bubble-in:after,
.chat-l .bubble-orange .bubble-in:before{
	border-right-color: #ffd699;
}

.chat-r .bubble-orange .bubble-in:after,
.chat-r .bubble-orange .bubble-in:before{
	border-left-color: #ffd699;
}

.together.chat-l .bubble-orange .bubble-in:after,
.together.chat-l .bubble-orange .bubble-in:before,
.together.chat-r .bubble-orange .bubble-in:after,
.together.chat-r .bubble-orange .bubble-in:before{
	border-bottom-color: #ffd699;
}


/*�����o���w�i�F�F�s���N�iHTML�ł̂݁j*/
.bubble-pink{
	border: 1px solid #fbe9e7;
	background: #fbe9e7;
}

.chat-l .bubble-pink .bubble-in:after,
.chat-l .bubble-pink .bubble-in:before{
	border-right-color: #fbe9e7;
}

.chat-r .bubble-pink .bubble-in:after,
.chat-r .bubble-pink .bubble-in:before{
	border-left-color: #fbe9e7;
}

.together.chat-l .bubble-pink .bubble-in:after,
.together.chat-l .bubble-pink .bubble-in:before,
.together.chat-r .bubble-pink .bubble-in:after,
.together.chat-r .bubble-pink .bubble-in:before{
	border-bottom-color: #fbe9e7;
}

/*�����o���w�i�F�F�s���N�iHTML�ł̂݁j*/
.bubble-red{
	border: 1px solid #f27573;
	background: #f27573;
	color: #fff;
}

.chat-l .bubble-red .bubble-in:after,
.chat-l .bubble-red .bubble-in:before{
	border-right-color: #f27573;
}

.chat-r .bubble-red .bubble-in:after,
.chat-r .bubble-red .bubble-in:before{
	border-left-color: #f27573;
}

.together.chat-l .bubble-red .bubble-in:after,
.together.chat-l .bubble-red .bubble-in:before,
.together.chat-r .bubble-red .bubble-in:after,
.together.chat-r .bubble-red .bubble-in:before{
	border-bottom-color: #f27573;
}

/*�����o���w�i�F�F�u���b�N�iHTML�ł̂݁j*/
.bubble-black{
	border: 1px solid #777777;
	background: #777777;
	color: #fff;
}

.chat-l .bubble-black .bubble-in:after,
.chat-l .bubble-black .bubble-in:before{
	border-right-color: #777777;
}

.chat-r .bubble-black .bubble-in:after,
.chat-r .bubble-black .bubble-in:before{
	border-left-color: #777777;
}

.together.chat-l .bubble-black .bubble-in:after,
.together.chat-l .bubble-black .bubble-in:before,
.together.chat-r .bubble-black .bubble-in:after,
.together.chat-r .bubble-black .bubble-in:before{
	border-bottom-color: #777777;
}

/*�����L���O*/
.main-body .ranking-list{
	margin-right: 0;
	margin-left: 0;
}

.main-body .ranking-list li{
	list-style: none;
	overflow: hidden;
	margin-bottom: 40px;
}

.main-body .rank-title{
	padding: 5px 0;
	border: none;
	background: none;
	font-weight: normal;
	font-size: 1.5em;
}

.main-body .rank-title{
	margin-top: 0;
}

.rank-thumb{
	float: left;
	margin-right: 20px;
	margin-bottom: 20px;
}

.sub-conts .ranking-list03 .rank-thumb img{
	width: 100px;
	height: auto;
}

.col2 .sub-conts .ranking-list01 .rank-thumb,
.col2 .sub-conts .ranking-list02 .rank-thumb,
.col2r .sub-conts .ranking-list01 .rank-thumb,
.col2r .sub-conts .ranking-list02 .rank-thumb{
	float: none;
	text-align: center;
}

.rank-desc{
	overflow: hidden;
}

/*�����L���O�p�̉����A�C�R���̃��X�g*/
.ranking-list01 > li .rank-title{
	padding-left: 60px;
}

.ranking-list01 .rank01 .rank-title{ background: url(./images/icon/icon-rank01-01.png) left top no-repeat; }
.ranking-list01 .rank02 .rank-title{ background: url(./images/icon/icon-rank01-02.png) left top no-repeat; }
.ranking-list01 .rank03 .rank-title{ background: url(./images/icon/icon-rank01-03.png) left top no-repeat; }
.ranking-list01 .rank04 .rank-title{ background: url(./images/icon/icon-rank01-04.png) left top no-repeat; }
.ranking-list01 .rank05 .rank-title{ background: url(./images/icon/icon-rank01-05.png) left top no-repeat; }
.ranking-list01 .rank06 .rank-title{ background: url(./images/icon/icon-rank01-06.png) left top no-repeat; }
.ranking-list01 .rank07 .rank-title{ background: url(./images/icon/icon-rank01-07.png) left top no-repeat; }
.ranking-list01 .rank08 .rank-title{ background: url(./images/icon/icon-rank01-08.png) left top no-repeat; }
.ranking-list01 .rank09 .rank-title{ background: url(./images/icon/icon-rank01-09.png) left top no-repeat; }
.ranking-list01 .rank10 .rank-title{ background: url(./images/icon/icon-rank01-10.png) left top no-repeat; }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){	
		.ranking-list01 .rank01 .rank-title{ background: url(./images/icon/icon-rank01-01@2x.png) left top no-repeat; }
		.ranking-list01 .rank02 .rank-title{ background: url(./images/icon/icon-rank01-02@2x.png) left top no-repeat; }
		.ranking-list01 .rank03 .rank-title{ background: url(./images/icon/icon-rank01-03@2x.png) left top no-repeat; }
		.ranking-list01 .rank04 .rank-title{ background: url(./images/icon/icon-rank01-04@2x.png) left top no-repeat; }
		.ranking-list01 .rank05 .rank-title{ background: url(./images/icon/icon-rank01-05@2x.png) left top no-repeat; }
		.ranking-list01 .rank06 .rank-title{ background: url(./images/icon/icon-rank01-06@2x.png) left top no-repeat; }
		.ranking-list01 .rank07 .rank-title{ background: url(./images/icon/icon-rank01-07@2x.png) left top no-repeat; }
		.ranking-list01 .rank08 .rank-title{ background: url(./images/icon/icon-rank01-08@2x.png) left top no-repeat; }
		.ranking-list01 .rank09 .rank-title{ background: url(./images/icon/icon-rank01-09@2x.png) left top no-repeat; }
		.ranking-list01 .rank10 .rank-title{ background: url(./images/icon/icon-rank01-10@2x.png) left top no-repeat; }
		.ranking-list01 .rank01 .rank-title,
		.ranking-list01 .rank02 .rank-title,
		.ranking-list01 .rank03 .rank-title,
		.ranking-list01 .rank04 .rank-title,
		.ranking-list01 .rank05 .rank-title,
		.ranking-list01 .rank06 .rank-title,
		.ranking-list01 .rank07 .rank-title,
		.ranking-list01 .rank08 .rank-title,
		.ranking-list01 .rank09 .rank-title,
		.ranking-list01 .rank10 .rank-title{
			-webkit-background-size: 48px 40px;
			background-size: 48px 40px;
		}
	}

/*�����L���O�p�̃��_���A�C�R���̃��X�g*/
.ranking-list02 > li .rank-title{
	padding-left: 60px;
	padding-bottom: 10px;
}

.ranking-list02 .rank01 .rank-title{ background: url(./images/icon/icon-rank02-01.png) left top no-repeat; }
.ranking-list02 .rank02 .rank-title{ background: url(./images/icon/icon-rank02-02.png) left top no-repeat; }
.ranking-list02 .rank03 .rank-title{ background: url(./images/icon/icon-rank02-03.png) left top no-repeat; }
.ranking-list02 .rank04 .rank-title{ background: url(./images/icon/icon-rank02-04.png) left top no-repeat; }
.ranking-list02 .rank05 .rank-title{ background: url(./images/icon/icon-rank02-05.png) left top no-repeat; }
.ranking-list02 .rank06 .rank-title{ background: url(./images/icon/icon-rank02-06.png) left top no-repeat; }
.ranking-list02 .rank07 .rank-title{ background: url(./images/icon/icon-rank02-07.png) left top no-repeat; }
.ranking-list02 .rank08 .rank-title{ background: url(./images/icon/icon-rank02-08.png) left top no-repeat; }
.ranking-list02 .rank09 .rank-title{ background: url(./images/icon/icon-rank02-09.png) left top no-repeat; }
.ranking-list02 .rank10 .rank-title{ background: url(./images/icon/icon-rank02-10.png) left top no-repeat; }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.ranking-list02 .rank01 .rank-title{ background: url(./images/icon/icon-rank02-01@2x.png) left top no-repeat; }
		.ranking-list02 .rank02 .rank-title{ background: url(./images/icon/icon-rank02-02@2x.png) left top no-repeat; }
		.ranking-list02 .rank03 .rank-title{ background: url(./images/icon/icon-rank02-03@2x.png) left top no-repeat; }
		.ranking-list02 .rank04 .rank-title{ background: url(./images/icon/icon-rank02-04@2x.png) left top no-repeat; }
		.ranking-list02 .rank05 .rank-title{ background: url(./images/icon/icon-rank02-05@2x.png) left top no-repeat; }
		.ranking-list02 .rank06 .rank-title{ background: url(./images/icon/icon-rank02-06@2x.png) left top no-repeat; }
		.ranking-list02 .rank07 .rank-title{ background: url(./images/icon/icon-rank02-07@2x.png) left top no-repeat; }
		.ranking-list02 .rank08 .rank-title{ background: url(./images/icon/icon-rank02-08@2x.png) left top no-repeat; }
		.ranking-list02 .rank09 .rank-title{ background: url(./images/icon/icon-rank02-09@2x.png) left top no-repeat; }
		.ranking-list02 .rank10 .rank-title{ background: url(./images/icon/icon-rank02-10@2x.png) left top no-repeat; }

		.ranking-list02 .rank01 .rank-title,
		.ranking-list02 .rank02 .rank-title,
		.ranking-list02 .rank03 .rank-title,
		.ranking-list02 .rank04 .rank-title,
		.ranking-list02 .rank05 .rank-title,
		.ranking-list02 .rank06 .rank-title,
		.ranking-list02 .rank07 .rank-title,
		.ranking-list02 .rank08 .rank-title,
		.ranking-list02 .rank09 .rank-title,
		.ranking-list02 .rank10 .rank-title{
		-webkit-background-size: 40px 45px;
		background-size: 40px 45px;
		}
	}

/*�����L���O�p�̃V���v���ȃ��X�g*/
.ranking-list03 > li .rank-title{
	padding: 5px 0;
	padding-left: 58px;
	font-size: 1.25em;
}

.sub-conts .ranking-list03 > li .rank-title{
	min-height: 30px;
	padding: 0;
	padding-left: 40px;
	font-size: 1.25em;
}

.ranking-list03 .rank01 .rank-title,
.ranking-list03 .rank02 .rank-title,
.ranking-list03 .rank03 .rank-title{
	border-bottom: 1px solid #909090;
}

.ranking-list03 .rank01 .rank-title{ background: url(./images/icon/icon-rank03-01.png) left top no-repeat; }
.ranking-list03 .rank02 .rank-title{ background: url(./images/icon/icon-rank03-02.png) left top no-repeat; }
.ranking-list03 .rank03 .rank-title{ background: url(./images/icon/icon-rank03-03.png) left top no-repeat; }
.ranking-list03 .rank04 .rank-title{ background: url(./images/icon/icon-rank03-04.png) left top no-repeat; }
.ranking-list03 .rank05 .rank-title{ background: url(./images/icon/icon-rank03-05.png) left top no-repeat; }
.ranking-list03 .rank06 .rank-title{ background: url(./images/icon/icon-rank03-06.png) left top no-repeat; }
.ranking-list03 .rank07 .rank-title{ background: url(./images/icon/icon-rank03-07.png) left top no-repeat; }
.ranking-list03 .rank08 .rank-title{ background: url(./images/icon/icon-rank03-08.png) left top no-repeat; }
.ranking-list03 .rank09 .rank-title{ background: url(./images/icon/icon-rank03-09.png) left top no-repeat; }
.ranking-list03 .rank10 .rank-title{ background: url(./images/icon/icon-rank03-10.png) left top no-repeat; }

.sub-conts .ranking-list03 .rank01 .rank-title{ background: url(./images/icon/icon-rank04-01.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank02 .rank-title{ background: url(./images/icon/icon-rank04-02.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank03 .rank-title{ background: url(./images/icon/icon-rank04-03.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank04 .rank-title{ background: url(./images/icon/icon-rank04-04.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank05 .rank-title{ background: url(./images/icon/icon-rank04-05.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank06 .rank-title{ background: url(./images/icon/icon-rank04-06.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank07 .rank-title{ background: url(./images/icon/icon-rank04-07.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank08 .rank-title{ background: url(./images/icon/icon-rank04-08.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank09 .rank-title{ background: url(./images/icon/icon-rank04-09.png) left top no-repeat; }
.sub-conts .ranking-list03 .rank10 .rank-title{ background: url(./images/icon/icon-rank04-10.png) left top no-repeat; }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.ranking-list03 .rank01 .rank-title{ background: url(./images/icon/icon-rank03-01@2x.png) left top no-repeat; }
		.ranking-list03 .rank02 .rank-title{ background: url(./images/icon/icon-rank03-02@2x.png) left top no-repeat; }
		.ranking-list03 .rank03 .rank-title{ background: url(./images/icon/icon-rank03-03@2x.png) left top no-repeat; }
		.ranking-list03 .rank04 .rank-title{ background: url(./images/icon/icon-rank03-04@2x.png) left top no-repeat; }
		.ranking-list03 .rank05 .rank-title{ background: url(./images/icon/icon-rank03-05@2x.png) left top no-repeat; }
		.ranking-list03 .rank06 .rank-title{ background: url(./images/icon/icon-rank03-06@2x.png) left top no-repeat; }
		.ranking-list03 .rank07 .rank-title{ background: url(./images/icon/icon-rank03-07@2x.png) left top no-repeat; }
		.ranking-list03 .rank08 .rank-title{ background: url(./images/icon/icon-rank03-08@2x.png) left top no-repeat; }
		.ranking-list03 .rank09 .rank-title{ background: url(./images/icon/icon-rank03-09@2x.png) left top no-repeat; }
		.ranking-list03 .rank10 .rank-title{ background: url(./images/icon/icon-rank03-10@2x.png) left top no-repeat; }

		.ranking-list03 .rank01 .rank-title,
		.ranking-list03 .rank02 .rank-title,
		.ranking-list03 .rank03 .rank-title,
		.ranking-list03 .rank04 .rank-title,
		.ranking-list03 .rank05 .rank-title,
		.ranking-list03 .rank06 .rank-title,
		.ranking-list03 .rank07 .rank-title,
		.ranking-list03 .rank08 .rank-title,
		.ranking-list03 .rank09 .rank-title,
		.ranking-list03 .rank10 .rank-title{
			-webkit-background-size: 40px 48px;
			background-size: 40px 48px;
		}

		.sub-conts .ranking-list03 .rank01 .rank-title{ background: url(./images/icon/icon-rank04-01@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank02 .rank-title{ background: url(./images/icon/icon-rank04-02@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank03 .rank-title{ background: url(./images/icon/icon-rank04-03@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank04 .rank-title{ background: url(./images/icon/icon-rank04-04@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank05 .rank-title{ background: url(./images/icon/icon-rank04-05@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank06 .rank-title{ background: url(./images/icon/icon-rank04-06@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank07 .rank-title{ background: url(./images/icon/icon-rank04-07@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank08 .rank-title{ background: url(./images/icon/icon-rank04-08@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank09 .rank-title{ background: url(./images/icon/icon-rank04-09@2x.png) left top no-repeat; }
		.sub-conts .ranking-list03 .rank10 .rank-title{ background: url(./images/icon/icon-rank04-10@2x.png) left top no-repeat; }

		.sub-conts .ranking-list03 .rank01 .rank-title,
		.sub-conts .ranking-list03 .rank02 .rank-title,
		.sub-conts .ranking-list03 .rank03 .rank-title,
		.sub-conts .ranking-list03 .rank04 .rank-title,
		.sub-conts .ranking-list03 .rank05 .rank-title,
		.sub-conts .ranking-list03 .rank06 .rank-title,
		.sub-conts .ranking-list03 .rank07 .rank-title,
		.sub-conts .ranking-list03 .rank08 .rank-title,
		.sub-conts .ranking-list03 .rank09 .rank-title,
		.sub-conts .ranking-list03 .rank10 .rank-title{
			-webkit-background-size: 30px 30px;
			background-size: 30px 30px;
		}

	}

/*�����L���O�p�̉摜�{�����L���O�ԍ��̃��X�g*/
.ranking-list .on-image{
}

.ranking-list .on-image .rank-title{
	padding: 0!important;
	border: 0;
	background: none!important;
	font-size: 1.25em;
}

.ranking-list .on-image .rank-thumb{
	position: relative;
}

.ranking-list .on-image .rank-thumb:before,
.ranking-list .on-image .rank-thumb:before,
.ranking-list .on-image .rank-thumb:before{
	position: absolute;
	top: 0;
	left: 0;
}

.ranking-list03 > .rank01.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-01.png); }
.ranking-list03 > .rank02.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-02.png); }
.ranking-list03 > .rank03.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-03.png); }
.ranking-list03 > .rank04.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-04.png); }
.ranking-list03 > .rank05.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-05.png); }
.ranking-list03 > .rank06.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-06.png); }
.ranking-list03 > .rank07.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-07.png); }
.ranking-list03 > .rank08.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-08.png); }
.ranking-list03 > .rank09.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-09.png); }
.ranking-list03 > .rank10.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank03-10.png); }

.sub-conts .ranking-list03 > .rank01.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-01.png); }
.sub-conts .ranking-list03 > .rank02.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-02.png); }
.sub-conts .ranking-list03 > .rank03.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-03.png); }
.sub-conts .ranking-list03 > .rank04.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-04.png); }
.sub-conts .ranking-list03 > .rank05.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-05.png); }
.sub-conts .ranking-list03 > .rank06.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-06.png); }
.sub-conts .ranking-list03 > .rank07.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-07.png); }
.sub-conts .ranking-list03 > .rank08.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-08.png); }
.sub-conts .ranking-list03 > .rank09.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-09.png); }
.sub-conts .ranking-list03 > .rank10.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank04-10.png); }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.ranking-list03 > .rank01.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-01@2x.png); }
		.ranking-list03 > .rank02.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-02@2x.png); }
		.ranking-list03 > .rank03.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-03@2x.png); }
		.ranking-list03 > .rank04.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-04@2x.png); }
		.ranking-list03 > .rank05.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-05@2x.png); }
		.ranking-list03 > .rank06.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-06@2x.png); }
		.ranking-list03 > .rank07.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-07@2x.png); }
		.ranking-list03 > .rank08.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-08@2x.png); }
		.ranking-list03 > .rank09.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-09@2x.png); }
		.ranking-list03 > .rank10.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank03-10@2x.png); }

		.ranking-list03 > .rank01.on-image .rank-thumb:before,
		.ranking-list03 > .rank02.on-image .rank-thumb:before,
		.ranking-list03 > .rank03.on-image .rank-thumb:before,
		.ranking-list03 > .rank04.on-image .rank-thumb:before,
		.ranking-list03 > .rank05.on-image .rank-thumb:before,
		.ranking-list03 > .rank06.on-image .rank-thumb:before,
		.ranking-list03 > .rank07.on-image .rank-thumb:before,
		.ranking-list03 > .rank08.on-image .rank-thumb:before,
		.ranking-list03 > .rank09.on-image .rank-thumb:before,
		.ranking-list03 > .rank10.on-image .rank-thumb:before{
			display: inline-block;
			width: 48px;
			height: 48px;
			vertical-align: middle;
			-webkit-background-size: contain;
			background-size: contain;
			content: " ";
		}

		.sub-conts .ranking-list03 > .rank01.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-01@2x.png); }
		.sub-conts .ranking-list03 > .rank02.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-02@2x.png); }
		.sub-conts .ranking-list03 > .rank03.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-03@2x.png); }
		.sub-conts .ranking-list03 > .rank04.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-04@2x.png); }
		.sub-conts .ranking-list03 > .rank05.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-05@2x.png); }
		.sub-conts .ranking-list03 > .rank06.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-06@2x.png); }
		.sub-conts .ranking-list03 > .rank07.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-07@2x.png); }
		.sub-conts .ranking-list03 > .rank08.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-08@2x.png); }
		.sub-conts .ranking-list03 > .rank09.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-09@2x.png); }
		.sub-conts .ranking-list03 > .rank10.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank04-10@2x.png); }

		.sub-conts .ranking-list03 > .rank01.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank02.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank03.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank04.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank05.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank06.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank07.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank08.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank09.on-image .rank-thumb:before,
		.sub-conts .ranking-list03 > .rank10.on-image .rank-thumb:before{
			display: inline-block;
			width: 30px;
			height: 30px;
			vertical-align: middle;
			-webkit-background-size: contain;
			background-size: contain;
			content: " ";
		}

	}

/*�摜�{�e�L�X�g�̃��X�g�i�����L���O�p�j*/
.ranking-list04 .rank-box{
	position: relative;
	width: 320px;
	margin-right: auto;
	margin-left: auto;
}

.col1 .ranking-list04 li{
	display: inline-block;
	margin-right: 20px;
}

.ranking-list04 .rank-box img{
	width: 100%;
}

.ranking-list04 .on-image .rank-box:before,
.ranking-list04 .on-image .rank-box:before,
.ranking-list04 .on-image .rank-box:before{
	position: absolute;
	top: 0;
	left: 0;
}

.ranking-list04 .on-image .rank-box .rank-text{
	 position: absolute;
	 bottom: 0;
	 -webkit-box-sizing: border-box;
	 box-sizing: border-box;
	 width: 100%;
	 margin: 0;
	 padding: 10px;
	 background-color: rgba(0,0,0,0.5);
	 background-color: #000000\9; /*IE8�ւ̑Ή�*/
	 color: #fff;
}

html:not(:target) .ranking-list04 .on-image .rank-box .rank-text{
	background-color: rgba(0,0,0,0.5); /*IE9�ȏ�ւ̑Ή�*/
}

.ranking-list04 .on-image .rank-box a{
	color: #fff;
}

.ranking-list04 .on-image .rank-box a:hover,
.ranking-list04 .on-image .rank-box a:active,
.ranking-list04 .on-image .rank-box a:focus{
	color: #f60;
}

.ranking-list04 > .rank01.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-01.png); }
.ranking-list04 > .rank02.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-02.png); }
.ranking-list04 > .rank03.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-03.png); }
.ranking-list04 > .rank04.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-04.png); }
.ranking-list04 > .rank05.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-05.png); }
.ranking-list04 > .rank06.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-06.png); }
.ranking-list04 > .rank07.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-07.png); }
.ranking-list04 > .rank08.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-08.png); }
.ranking-list04 > .rank09.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-09.png); }
.ranking-list04 > .rank10.on-image .rank-box:before{ content: url(./images/icon/icon-rank03-10.png); }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.ranking-list04 > .rank01.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-01@2x.png); }
		.ranking-list04 > .rank02.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-02@2x.png); }
		.ranking-list04 > .rank03.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-03@2x.png); }
		.ranking-list04 > .rank04.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-04@2x.png); }
		.ranking-list04 > .rank05.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-05@2x.png); }
		.ranking-list04 > .rank06.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-06@2x.png); }
		.ranking-list04 > .rank07.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-07@2x.png); }
		.ranking-list04 > .rank08.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-08@2x.png); }
		.ranking-list04 > .rank09.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-09@2x.png); }
		.ranking-list04 > .rank10.on-image .rank-box:before{ background: url(./images/icon/icon-rank03-10@2x.png); }

		.ranking-list04 > .rank01.on-image .rank-box:before,
		.ranking-list04 > .rank02.on-image .rank-box:before,
		.ranking-list04 > .rank03.on-image .rank-box:before,
		.ranking-list04 > .rank04.on-image .rank-box:before,
		.ranking-list04 > .rank05.on-image .rank-box:before,
		.ranking-list04 > .rank06.on-image .rank-box:before,
		.ranking-list04 > .rank07.on-image .rank-box:before,
		.ranking-list04 > .rank08.on-image .rank-box:before,
		.ranking-list04 > .rank09.on-image .rank-box:before,
		.ranking-list04 > .rank10.on-image .rank-box:before{
			display: inline-block;
			width: 48px;
			height: 48px;
			vertical-align: middle;
			-webkit-background-size: contain;
			background-size: contain;
			content: " ";
		}

	}

/*�w�i�摜�{�e�L�X�g�̃��X�g�i�����L���O�p�j*/
.ranking-list05 .rank-box{
	position: relative;
	margin-right: auto;
	margin-left: auto;
	background-position: center center;
	background-size: cover;
}
.col1 .ranking-list05 .rank-box{
	width:320px;
}

.col1 .ranking-list05 li{
	display: inline-block;
	margin-right: 20px;
}

.ranking-list05 .rank-box a{
	 display: block;
	 -webkit-box-sizing: border-box;
	 box-sizing: border-box;
	 height: 180px;
	 padding: 3em 1em 1em;
	 background-color: rgba(0,0,0,0.5);
	 background-color: #000000\9; /*IE8�ւ̑Ή�*/
	 color: #fff;
}

html:not(:target) .ranking-list05 .rank-box a{
	background-color: rgba(0,0,0,0.5); /*IE9�ȏ�ւ̑Ή�*/
}

.ranking-list05 .rank-box a:hover,
.ranking-list05 .rank-box a:active,
.ranking-list05 .rank-box a:focus{
	color: #f60;
}

.ranking-list05 .on-image .rank-box:before,
.ranking-list05 .on-image .rank-box:before,
.ranking-list05 .on-image .rank-box:before{
	position: absolute;
	top: 0;
	left: 0;
}

.ranking-list05 > .rank01.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-01.png); }
.ranking-list05 > .rank02.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-02.png); }
.ranking-list05 > .rank03.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-03.png); }
.ranking-list05 > .rank04.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-04.png); }
.ranking-list05 > .rank05.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-05.png); }
.ranking-list05 > .rank06.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-06.png); }
.ranking-list05 > .rank07.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-07.png); }
.ranking-list05 > .rank08.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-08.png); }
.ranking-list05 > .rank09.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-09.png); }
.ranking-list05 > .rank10.on-image .rank-box:before{ content: url(./images/icon/icon-rank04-10.png); }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.ranking-list05 > .rank01.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-01@2x.png); }
		.ranking-list05 > .rank02.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-02@2x.png); }
		.ranking-list05 > .rank03.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-03@2x.png); }
		.ranking-list05 > .rank04.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-04@2x.png); }
		.ranking-list05 > .rank05.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-05@2x.png); }
		.ranking-list05 > .rank06.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-06@2x.png); }
		.ranking-list05 > .rank07.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-07@2x.png); }
		.ranking-list05 > .rank08.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-08@2x.png); }
		.ranking-list05 > .rank09.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-09@2x.png); }
		.ranking-list05 > .rank10.on-image .rank-box:before{ background: url(./images/icon/icon-rank04-10@2x.png); }

		.ranking-list05 > .rank01.on-image .rank-box:before,
		.ranking-list05 > .rank02.on-image .rank-box:before,
		.ranking-list05 > .rank03.on-image .rank-box:before,
		.ranking-list05 > .rank04.on-image .rank-box:before,
		.ranking-list05 > .rank05.on-image .rank-box:before,
		.ranking-list05 > .rank06.on-image .rank-box:before,
		.ranking-list05 > .rank07.on-image .rank-box:before,
		.ranking-list05 > .rank08.on-image .rank-box:before,
		.ranking-list05 > .rank09.on-image .rank-box:before,
		.ranking-list05 > .rank10.on-image .rank-box:before{
			display: inline-block;
			width: 30px;
			height: 30px;
			vertical-align: middle;
			-webkit-background-size: contain;
			background-size: contain;
			content: " ";
		}

	}

/*���ʂ̖����̃��X�g*/
.main-body .post-list01,
.main-body .post-list02{
	margin-right: 0;
	margin-left: 0;
}

.main-body .post-list01 li,
.main-body .post-list02 li{
	list-style: none;
	overflow: hidden;
	margin-bottom: 40px;
}

/*�摜�{�e�L�X�g�̃��X�g*/
.post-list01 .post-box{
	position: relative;
	margin-right: auto;
	margin-left: auto;
}

.col1 .post-list01 li{
	display: inline-block;
	margin-right: 20px;
}

.post-list01 .post-box img{
	width: 100%;
}

.post-list01 .on-image .post-box:before,
.post-list01 .on-image .post-box:before,
.post-list01 .on-image .post-box:before{
	position: absolute;
	top: 0;
	left: 0;
}

.post-list01 .on-image .post-box .post-text{
	 position: absolute;
	 bottom: 0;
	 -webkit-box-sizing: border-box;
	 box-sizing: border-box;
	 width: 100%;
	 margin: 0;
	 padding: 10px;
	 background-color: rgba(0,0,0,0.5);
	 background-color: #000000\9; /*IE8�ւ̑Ή�*/
	 color: #fff;
}

html:not(:target) .post-list01 .on-image .post-box .post-text{
	background-color: rgba(0,0,0,0.5); /*IE9�ȏ�ւ̑Ή�*/
}

.post-list01 .on-image .post-box a{
	color: #fff;
}

.post-list01 .on-image .post-box a:hover,
.post-list01 .on-image .post-box a:active,
.post-list01 .on-image .post-box a:focus{
	color: #f60;
}

/*�w�i�摜�{�e�L�X�g�̃��X�g*/
.post-list02 .post-box{
	position: relative;
	margin-right: auto;
	margin-left: auto;
	background-position: center center;
	background-size: cover;
}

.col1 .post-list02 .post-box{
	width:320px;
}

.col1 .post-list02 li{
	display: inline-block;
	margin-right: 20px;
}

.post-list02 .post-box a{
	 display: block;
	 -webkit-box-sizing: border-box;
	 box-sizing: border-box;
	 height: 180px;
	 padding: 1em;
	 background-color: rgba(0,0,0,0.5);
	 background-color: #000000\9; /*IE8�ւ̑Ή�*/
	 color: #fff;
}

html:not(:target) .post-list02 .post-box a{
 	background-color: rgba(0,0,0,0.5); /*IE9�ȏ�ւ̑Ή�*/
}

.post-list02 .post-box a:hover,
.post-list02 .post-box a:active,
.post-list02 .post-box a:focus{
	color: #f60;
}

.post-list02 .on-image .post-box:before,
.post-list02 .on-image .post-box:before,
.post-list02 .on-image .post-box:before{
	position: absolute;
	top: 0;
	left: 0;
}

/*����r���X�g*/
.review-table{
	width: auto;
	margin-top: 0;
	border-top: 1px solid #fff;
	border-left: 1px solid #fff;
}

.rank-thumb .review-table{
	width: 100%;
	margin-bottom: 0;
}

.review-table th,
.review-table td{
	line-height: 1.0;
	padding: 0.5em;
	border-right: 1px solid #fff;
	border-bottom: 1px solid #fff;
	background-color: #e9e9e9;
}

.review-table th{
	font-weight: normal;
}

.star00,
.star05,
.star10,
.star15,
.star20,
.star25,
.star30,
.star35,
.star40,
.star45,
.star50{
	padding-left: 105px;
	white-space: nowrap;
}

.star00{ background: url(./images/icon/icon-star00.png) left center no-repeat; }
.star05{ background: url(./images/icon/icon-star05.png) left center no-repeat; }
.star10{ background: url(./images/icon/icon-star10.png) left center no-repeat; }
.star15{ background: url(./images/icon/icon-star15.png) left center no-repeat; }
.star20{ background: url(./images/icon/icon-star20.png) left center no-repeat; }
.star25{ background: url(./images/icon/icon-star25.png) left center no-repeat; }
.star30{ background: url(./images/icon/icon-star30.png) left center no-repeat; }
.star35{ background: url(./images/icon/icon-star35.png) left center no-repeat; }
.star40{ background: url(./images/icon/icon-star40.png) left center no-repeat; }
.star45{ background: url(./images/icon/icon-star45.png) left center no-repeat; }
.star50{ background: url(./images/icon/icon-star50.png) left center no-repeat; }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.star00{ background: url(./images/icon/icon-star00@2x.png) left center no-repeat; }
		.star05{ background: url(./images/icon/icon-star05@2x.png) left center no-repeat; }
		.star10{ background: url(./images/icon/icon-star10@2x.png) left center no-repeat; }
		.star15{ background: url(./images/icon/icon-star15@2x.png) left center no-repeat; }
		.star20{ background: url(./images/icon/icon-star20@2x.png) left center no-repeat; }
		.star25{ background: url(./images/icon/icon-star25@2x.png) left center no-repeat; }
		.star30{ background: url(./images/icon/icon-star30@2x.png) left center no-repeat; }
		.star35{ background: url(./images/icon/icon-star35@2x.png) left center no-repeat; }
		.star40{ background: url(./images/icon/icon-star40@2x.png) left center no-repeat; }
		.star45{ background: url(./images/icon/icon-star45@2x.png) left center no-repeat; }
		.star50{ background: url(./images/icon/icon-star50@2x.png) left center no-repeat; }

		.star00,
		.star05,
		.star10,
		.star15,
		.star20,
		.star25,
		.star30,
		.star35,
		.star40,
		.star45,
		.star50{
			-webkit-background-size: 97px 17px;
			background-size: 97px 17px;
		}

	}

.item-data{
	margin-bottom: 1em;
}

.item-data dl,
.item-data dt,
.item-data dd{
	margin: 0;
}

.item-data dt,
.item-data dd{
	display: inline-block;
}

.item-data dd{
	padding-left: 0;
}

.comparative-list01 .rank-desc,
.comparative-list02 .rank-desc{
	overflow: visible;
}

.main-body .review-desc-title{
	overflow: hidden;
	margin-top: 0;
	margin-bottom: 1em;
	padding: 0 0 0 14px;
	border: none;
	border-left: 4px solid #fb8e2d;
	background: none;
	font-weight: normal;
	font-size: 1.125em;
}


/*����r�p�̉����A�C�R��*/
.comparative-list01 > li .rank-title{
	padding-left: 60px;
}

.comparative-list01 .rank01 .rank-title{ background: url(./images/icon/icon-rank01-01.png) left top no-repeat; }
.comparative-list01 .rank02 .rank-title{ background: url(./images/icon/icon-rank01-02.png) left top no-repeat; }
.comparative-list01 .rank03 .rank-title{ background: url(./images/icon/icon-rank01-03.png) left top no-repeat; }
.comparative-list01 .rank04 .rank-title{ background: url(./images/icon/icon-rank01-04.png) left top no-repeat; }
.comparative-list01 .rank05 .rank-title{ background: url(./images/icon/icon-rank01-05.png) left top no-repeat; }
.comparative-list01 .rank06 .rank-title{ background: url(./images/icon/icon-rank01-06.png) left top no-repeat; }
.comparative-list01 .rank07 .rank-title{ background: url(./images/icon/icon-rank01-07.png) left top no-repeat; }
.comparative-list01 .rank08 .rank-title{ background: url(./images/icon/icon-rank01-08.png) left top no-repeat; }
.comparative-list01 .rank09 .rank-title{ background: url(./images/icon/icon-rank01-09.png) left top no-repeat; }
.comparative-list01 .rank10 .rank-title{ background: url(./images/icon/icon-rank01-10.png) left top no-repeat; }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){	
		.comparative-list01 .rank01 .rank-title{ background: url(./images/icon/icon-rank01-01@2x.png) left top no-repeat; }
		.comparative-list01 .rank02 .rank-title{ background: url(./images/icon/icon-rank01-02@2x.png) left top no-repeat; }
		.comparative-list01 .rank03 .rank-title{ background: url(./images/icon/icon-rank01-03@2x.png) left top no-repeat; }
		.comparative-list01 .rank04 .rank-title{ background: url(./images/icon/icon-rank01-04@2x.png) left top no-repeat; }
		.comparative-list01 .rank05 .rank-title{ background: url(./images/icon/icon-rank01-05@2x.png) left top no-repeat; }
		.comparative-list01 .rank06 .rank-title{ background: url(./images/icon/icon-rank01-06@2x.png) left top no-repeat; }
		.comparative-list01 .rank07 .rank-title{ background: url(./images/icon/icon-rank01-07@2x.png) left top no-repeat; }
		.comparative-list01 .rank08 .rank-title{ background: url(./images/icon/icon-rank01-08@2x.png) left top no-repeat; }
		.comparative-list01 .rank09 .rank-title{ background: url(./images/icon/icon-rank01-09@2x.png) left top no-repeat; }
		.comparative-list01 .rank10 .rank-title{ background: url(./images/icon/icon-rank01-10@2x.png) left top no-repeat; }
		.comparative-list01 .rank01 .rank-title,
		.comparative-list01 .rank02 .rank-title,
		.comparative-list01 .rank03 .rank-title,
		.comparative-list01 .rank04 .rank-title,
		.comparative-list01 .rank05 .rank-title,
		.comparative-list01 .rank06 .rank-title,
		.comparative-list01 .rank07 .rank-title,
		.comparative-list01 .rank08 .rank-title,
		.comparative-list01 .rank09 .rank-title,
		.comparative-list01 .rank10 .rank-title{
			-webkit-background-size: 48px 40px;
			background-size: 48px 40px;
		}
	}

/*�����L���O�p�̃V���v���ȃ��X�g*/
.comparative-list02 > .rank01.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-01.png); }
.comparative-list02 > .rank02.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-02.png); }
.comparative-list02 > .rank03.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-03.png); }
.comparative-list02 > .rank04.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-04.png); }
.comparative-list02 > .rank05.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-05.png); }
.comparative-list02 > .rank06.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-06.png); }
.comparative-list02 > .rank07.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-07.png); }
.comparative-list02 > .rank08.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-08.png); }
.comparative-list02 > .rank09.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-09.png); }
.comparative-list02 > .rank10.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank05-10.png); }

.sub-conts .comparative-list02 > .rank01.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-01.png); }
.sub-conts .comparative-list02 > .rank02.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-02.png); }
.sub-conts .comparative-list02 > .rank03.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-03.png); }
.sub-conts .comparative-list02 > .rank04.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-04.png); }
.sub-conts .comparative-list02 > .rank05.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-05.png); }
.sub-conts .comparative-list02 > .rank06.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-06.png); }
.sub-conts .comparative-list02 > .rank07.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-07.png); }
.sub-conts .comparative-list02 > .rank08.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-08.png); }
.sub-conts .comparative-list02 > .rank09.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-09.png); }
.sub-conts .comparative-list02 > .rank10.on-image .rank-thumb:before{ content: url(./images/icon/icon-rank06-10.png); }

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.comparative-list02 > .rank01.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-01@2x.png); }
		.comparative-list02 > .rank02.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-02@2x.png); }
		.comparative-list02 > .rank03.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-03@2x.png); }
		.comparative-list02 > .rank04.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-04@2x.png); }
		.comparative-list02 > .rank05.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-05@2x.png); }
		.comparative-list02 > .rank06.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-06@2x.png); }
		.comparative-list02 > .rank07.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-07@2x.png); }
		.comparative-list02 > .rank08.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-08@2x.png); }
		.comparative-list02 > .rank09.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-09@2x.png); }
		.comparative-list02 > .rank10.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank05-10@2x.png); }

		.comparative-list02 > .rank01.on-image .rank-thumb:before,
		.comparative-list02 > .rank02.on-image .rank-thumb:before,
		.comparative-list02 > .rank03.on-image .rank-thumb:before,
		.comparative-list02 > .rank04.on-image .rank-thumb:before,
		.comparative-list02 > .rank05.on-image .rank-thumb:before,
		.comparative-list02 > .rank06.on-image .rank-thumb:before,
		.comparative-list02 > .rank07.on-image .rank-thumb:before,
		.comparative-list02 > .rank08.on-image .rank-thumb:before,
		.comparative-list02 > .rank09.on-image .rank-thumb:before,
		.comparative-list02 > .rank10.on-image .rank-thumb:before{
			display: inline-block;
			width: 48px;
			height: 48px;
			vertical-align: middle;
			-webkit-background-size: contain;
			background-size: contain;
			content: " ";
		}

		.sub-conts .comparative-list02 > .rank01.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-01@2x.png); }
		.sub-conts .comparative-list02 > .rank02.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-02@2x.png); }
		.sub-conts .comparative-list02 > .rank03.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-03@2x.png); }
		.sub-conts .comparative-list02 > .rank04.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-04@2x.png); }
		.sub-conts .comparative-list02 > .rank05.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-05@2x.png); }
		.sub-conts .comparative-list02 > .rank06.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-06@2x.png); }
		.sub-conts .comparative-list02 > .rank07.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-07@2x.png); }
		.sub-conts .comparative-list02 > .rank08.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-08@2x.png); }
		.sub-conts .comparative-list02 > .rank09.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-09@2x.png); }
		.sub-conts .comparative-list02 > .rank10.on-image .rank-thumb:before{ background: url(./images/icon/icon-rank06-10@2x.png); }

		.sub-conts .comparative-list02 > .rank01.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank02.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank03.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank04.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank05.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank06.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank07.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank08.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank09.on-image .rank-thumb:before,
		.sub-conts .comparative-list02 > .rank10.on-image .rank-thumb:before{
			display: inline-block;
			width: 30px;
			height: 30px;
			vertical-align: middle;
			-webkit-background-size: contain;
			background-size: contain;
			content: " ";
		}

	}

/*���͒��̊�*/
.interval img{
	display: block;
	margin: 60px auto;
}

/*�`�F�b�N���X�g*/
.check-list,
.check-list-l{
	margin-left: 0;
}

.check-list li,
.check-list-l li{
	list-style: none;	
}

.check-list li{
	margin-bottom: 1em;
	padding-left: 32px;
	background: url(./images/icon/icon-check-list.png) left 3px no-repeat;
}

.check-list-l li{
	margin-bottom: 2em;
	padding: 10px 0 10px 55px;
	background: url(./images/icon/icon-check-list-l.png) left 3px no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){	

		.check-list li{
			background: url(./images/icon/icon-check-list@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.check-list-l li{
			background: url(./images/icon/icon-check-list-l@2x.png) left 3px no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}

	}

/*Q&A*/
.qa-list dt{
	display: block;
	position:relative;
	margin-bottom: 30px;
	padding: 15px 0 15px 80px;
	background: url(./images/icon/icon-q.png) 15px center no-repeat #F6F6F6;
	font-size: 1.25em;
}


.qa-list dt:after,.qa-list dt:before {
	content: "";
	position: absolute;
	top: 100%;
	height: 0;
	width: 0;
	border: #F6F6F6 solid 2px;
}
.qa-list dt:after {
	left: 33px;
	border: 11px solid transparent;
	border-top: 11px solid #F6F6F6;
}
.qa-list dt:before {
	left: 30px;
	border: 14px solid transparent;
	border-top: 14px solid #F6F6F6;
}

.qa-list dd{
	margin-left: 0;
	margin-bottom: 70px;
	padding: 15px 0 15px 80px;
	background: url(./images/icon/icon-a.png) 15px 3px no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.qa-list dt{
			background: url(./images/icon/icon-q@2x.png) 15px center no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}

		.qa-list dd{
			background: url(./images/icon/icon-a@2x.png) 15px 3px no-repeat;
			-webkit-background-size: 48px 49px;
			background-size: 48px 49px;
		}

	}

/*�t���[�}*/
.flow-chart{
	margin-left: 0;
}

.flow-chart li{
	list-style: none;
/*	margin-bottom: 20px;*/
	padding-bottom: 55px;
	background: url(./images/icon/icon-arrow-b-chart.png) center bottom no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.flow-chart li{
			background: url(./images/icon/icon-arrow-b-chart@2x.png) center bottom no-repeat;
			-webkit-background-size: 161px 40px;
			background-size: 161px 40px;
		}

	}

.flow-chart li.end,
.flow-chart li:last-child{
	padding-bottom: 0;
	background: none;
}

.flow-chart .process-box{
	padding: 15px;
	background-color: rgb(0, 152, 222);
	color: #fff;
}

/*�\���G���A*/
.info-box{
	margin:30px 0;
	padding: 40px 30px;
	background:#eee;
}

.trailer-text {
	position: relative;
	padding: 1em 1.5em 1em 1em;
	background-color: #f6f6f6;
	font-weight: bold;
	font-size: 1.25em;
}

.trailer-text::after {
	position: absolute;
	top: 0;
	right: 0;
	content: '';
	width: 0;
	border-width: 0 24px 24px 0;
	border-style: solid;
	border-color: #fff #fff #ddd #ddd;
	box-shadow: -1px 1px 3px rgba(0, 0, 0, .1);
}

.trailer-text-l{
	border-bottom:4px solid #5d6d7e;
	background:url(./images/icon/icon-trailer-lx.png) no-repeat right bottom;
	padding:0.5em 2em 0.5em 1em;
	font-weight: bold;
	font-size: 1.5em;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.trailer-text-l{
			background:url(./images/icon/icon-trailer-lx@2x.png) no-repeat right bottom;
			-webkit-background-size: 40px 24px;
			background-size: 40px 24px;
		}

	}

/*�֘A�L��*/
.related-thumb{
	overflow: hidden;
	width: 100%;
}

.related-thumb img{
	max-width: none;
}

.related-articles-thumbs01 ul{
	margin-left: 0;
}

.related-articles-thumbs01 li{
	list-style: none;
}

.related-articles-thumbs01 img{
	width: auto;
	max-height: 100px;
}

.related-articles-thumbs01 .related-thumb{
	float: left;
	width: 100px;
	margin-right: 20px;
	margin-bottom: 20px;
}

.related-articles-thumbs02 ul{
	overflow: hidden;
	margin-left: 0;
}

.related-articles-thumbs02 li{
	list-style: none;
	float: left;
	width: 30%;
	margin-left: 5%;
}

.related-articles-thumbs02 li:first-child{
	margin-left: 0;
}

.related-articles-thumbs02 img{
	width: auto;
	max-height: 160px;
}

/*���q�l�̐�*/
.voice-box{
	padding: 30px 20px;
}

.voice-headshot img{
	border-radius: 50%;
}
.voice-content{
	overflow: hidden;
	padding:1em;
	border:1px solid #ccc;
	border-radius: 8px;
}

/*�摜�ƃe�L�X�g�̑g�ݍ��킹*/
.col-onimage > .col{
	position: relative;
	overflow: hidden;
}

.col-onimage > .col .text-onimage{
	 position: absolute;
	 bottom: 0;
	 -webkit-box-sizing: border-box;
	 box-sizing: border-box;
	 width: 100%;
	 margin: 0;
	 padding: 10px;
	 background-color: rgba(0,0,0,0.5);
	 background-color: #000000\9; /*IE8�ւ̑Ή�*/
	 color: #fff;
}

html:not(:target) .col-onimage > .col .text-onimage{
	background-color: rgba(0,0,0,0.5); /*IE9�ȏ�ւ̑Ή�*/
}

.col-onimage02 > .col{
	background-position: center center;
	background-size: cover;
}

.col-onimage02 > .col .text-onimage{
	 -webkit-box-sizing: border-box;
	 box-sizing: border-box;
	 margin: 0;
	 padding: 20px;
	 background-color: rgba(0,0,0,0.5);
	 background-color: #000000\9; /*IE8�ւ̑Ή�*/
	 color: #fff;
}

html:not(:target) .col-onimage02 > .col .text-onimage{
	background-color: rgba(0,0,0,0.5); /*IE9�ȏ�ւ̑Ή�*/
}

.col-onimage > .col .text-onimage a,
.col-onimage02 > .col a{
	color: #fff;
}

.col-onimage > .col .text-onimage a:hover,
.col-onimage > .col .text-onimage a:active,
.col-onimage > .col .text-onimage a:focus,
.col-onimage02 > .col a:hover,
.col-onimage02 > .col a:active,
.col-onimage02 > .col a:focus{
	color: #f60;
}

/*�y�[�W����*/
.link-next{
	text-align: right;
}

.blog .article-body .link-next,
.archive .article-body .link-next,
.search .article-body .link-next{
	margin-bottom: 0;
}

.link-next a{
	padding-left: 13px;
	background: url(./images/icon/icon-arw-next.png) left 6px no-repeat;
}

.link-back a{
	padding-left: 13px;
	background: url(./images/icon/icon-arw-prev.png) left 6px no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.link-next a{
			background: url(./images/icon/icon-arw-next@2x.png) left 6px no-repeat;
			-webkit-background-size: 7px 10px;
			background-size: 7px 10px;
		}

		.link-back a{
			background: url(./images/icon/icon-arw-prev@2x.png) left 6px no-repeat;
			-webkit-background-size: 7px 10px;
			background-size: 7px 10px;
		}

	}

.page-nav ol{
	margin-left: 0;
	text-align: center;
}

.page-nav li{
	display: inline-block;
	margin-right: 10px;
	padding: 4px 8px;
	border: 1px solid #c1c1c1;
}

.page-nav li:last-child{
	margin-right: 0;
}

.page-nav li a{
	display: block;
	margin: -4px -8px;
	padding: 4px 8px;
	color: #333;
	text-decoration: none;
}

.current,
.page-nav li a:hover,
.page-nav li a:active,
.page-nav li a:focus{
	background: #1a242f;
	color: #fff;
}

.page-nav-bf ul{
	margin-left: 0;
}

.page-nav-bf li{
	list-style: none;
}

.page-nav-next{
	float: right;
	padding-right: 13px;
	background: url(./images/icon/icon-arw-next.png) right center no-repeat;
}

.page-nav-prev{
	float: left;
	padding-left: 13px;
	background: url(./images/icon/icon-arw-prev.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.page-nav-next{
			background: url(./images/icon/icon-arw-next@2x.png) right center no-repeat;
			-webkit-background-size: 7px 10px;
			background-size: 7px 10px;
		}

		.page-nav-prev{
			background: url(./images/icon/icon-arw-prev@2x.png) left center no-repeat;
			-webkit-background-size: 7px 10px;
			background-size: 7px 10px;
		}

	}


/*--------------------------------------------------------
WordPress�p�̃X�^�C��
--------------------------------------------------------*/
.single .article-body,
.page .article-body{
	margin-bottom: 40px;
}

/*�֘A�L��*/
.keni-relatedposts-list li {
	border-bottom:1px dotted #ccc;
	margin-bottom:10px;
}
.keni-relatedposts-list li p{
	overflow: hidden;
}

.keni-relatedposts-list li p a[target="_blank"]{
	padding: 3px;
	padding-right: 15px;
	background: url(./images/icon/icon-outbound-link.png) right center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.keni-relatedposts-list li p a[target="_blank"]{
			background: url(./images/icon/icon-outbound-link@2x.png) right center no-repeat;
			-webkit-background-size: 12px 13px;
			background-size: 12px 13px;
		}

	}

.cont-nav{
	padding-top: 40px;
	border-top: 1px solid #ccc;
}

/*�ڎ�*/
.post-toc{
	border-top:solid 1px #dadada;
	border-bottom:solid 1px #dadada;
	margin:40px 0;
	padding: 30px 20px;
}

/*�R�����g*/
.comment-form-author,
.comment-form-mail,
.comment-form-url{
	margin-bottom: 2em;
}

.comment-form-author p,
.comment-form-mail p,
.comment-form-url p{
	margin-bottom: 0;
}

.alignleft{
	float: left;
	margin: 0 1em 1em 0;
}

.alignright{
	float: right;
	margin: 0 0 1em 1em;
}

.aligncenter{
	display: block;
	float: none;
	margin-right: auto;
	margin-bottom: 1em;
	margin-left: auto;
}

.post-tag a{
	word-break: break-all;
}

/*�R�����g�ꗗ*/
.commentlist,
.commentlist .children{
	margin-left: 0;
}

.commentlist{
	border-bottom: 1px solid #ccc;
}

.commentlist li{
	list-style: none;
	margin-bottom: 1em;
	padding-bottom: 1em;
	border-bottom: 1px dotted #ccc;
}

.commentlist li:last-child,
.commentlist ul li:last-child{
	padding-bottom: 0;
	border-bottom: 0;
}

.reply a{
	padding-left: 13px;
	background: url(./images/icon/icon-arw-next.png) left 6px no-repeat;
}

.commentlist .children{
	margin-top: 1em;
	padding-top: 1em;
	padding-left: 40px;
	border-top: 1px solid #ccc;
}

/*�E�B�W�F�b�g*/
.rsswidget img{
	vertical-align: baseline;
}

.sub-conts .widget_recent_entries ul,
.sub-conts .widget_rss ul,
.sub-conts .widget_archive ul,
.sub-conts .widget_recent_comments ul,
.sub-conts .widget_nav_menu ul{
	margin-left: 0;
	padding-left: 0;
}

.sub-conts .widget_recent_entries li,
.sub-conts .widget_rss li,
.sub-conts .widget_archive li,
.sub-conts .widget_recent_comments li,
.sub-conts .widget_nav_menu li{
	list-style: none;
	margin-bottom: 1em;
	padding-left: 13px;
	background: url(./images/icon/icon-list-arw.png) left 6px no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.sub-conts .widget_recent_entries li,
		.sub-conts .widget_rss li,
		.sub-conts .widget_archive li,
		.sub-conts .widget_recent_comments li,
        .sub-conts .widget_nav_menu li{
			background: url(./images/icon/icon-list-arw@2x.png) left 6px no-repeat;
			-webkit-background-size: 7px 10px;
			background-size: 7px 10px;
		}

	}

.sub-conts .widget_recent_entries ul ul,
.sub-conts .widget_rss ul ul,
.sub-conts .widget_archive ul ul,
.sub-conts .widget_recent_comments ul ul,
.sub-conts .widget_nav_menu ul ul{
	margin-top: 1em;
	margin-left: 10px;
}

.num-pv{
	font-size: 0.8em;
}

/*�J�����_�[*/
.calendar,
.calendar_wrap table{
	background: #fff;
	font-size: 0.875em;
}

.calendar caption,
.widget_calendar caption{
	font-weight: bold;
}

.calendar th,
.calendar td,
.widget_calendar th,
.widget_calendar td{
	padding: 10px 0;
	text-align: center;
}

.calendar tfoot td,
.widget_calendar tfoot td{
	padding: 10px;
	border-right-width: 0;
	text-align: left;
}

.calendar tfoot td:last-child,
.widget_calendar tfoot td:last-child{
	border-right-width: 1px;
	text-align: right;
}

.calendar td a,
.widget_calendar tfoot td a{
	display: block;
	margin: -10px 0;
	padding: 10px 0;
}

/*�y�[�W����*/
.link-pages{
	margin-top: 2em;
	text-align: center;
	line-height: 1.2;
}

.link-pages span{
	display: inline-block;
	margin-left: 0;
}

.link-pages a,
.link-pages span{
	display: inline-block;
	margin-right: 10px;
	margin-bottom: 0.5em;
	padding: 4px 8px;
	border: 1px solid #c1c1c1;
	text-decoration: none;
}

.link-pages span,
.link-pages a:hover,
.link-pages a:active,
.link-pages a:focus{
	background: #c1c1c1;
	color: #fff;
}

.link-pages a span{
	display: inline;
	margin-right: 0;
	padding: 0;
	border: 0;
	background: transparent;
	color: inherit;
}

.link-pages .link-pages-cap{
	display: inline-block;
	margin-right: 10px;
	padding: 0;
	border: 0;
	background: transparent;
	color: inherit;
}

/*�L���v�V����*/
.wp-caption{
	max-width: 100%;
}

/*�M�������[*/
.gallery,
.gallery-item{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
}

.gallery{
	margin-bottom: 1em;
}

.gallery-item{
	display: inline-block;
	width: 100%;
	vertical-align: top;
	text-align: center;
}

.gallery-columns-2 .gallery-item,
.gallery-columns-3 .gallery-item,
.gallery-columns-4 .gallery-item,
.gallery-columns-5 .gallery-item,
.gallery-columns-6 .gallery-item,
.gallery-columns-7 .gallery-item,
.gallery-columns-8 .gallery-item,
.gallery-columns-9 .gallery-item{
	margin: 1%;
}

.gallery-columns-2 .gallery-item{ max-width: 48%; }
.gallery-columns-3 .gallery-item{ max-width: 31.3%; }
.gallery-columns-4 .gallery-item{ max-width: 23%; }
.gallery-columns-5 .gallery-item{ max-width: 18%; }
.gallery-columns-6 .gallery-item{ max-width: 14.6%; }
.gallery-columns-7 .gallery-item{ max-width: 12.2%; }
.gallery-columns-8 .gallery-item{ max-width: 10.5%; }
.gallery-columns-9 .gallery-item{ max-width: 9.1%; }

.gallery-icon img{
	margin: 0 auto;
}

.gallery-caption{
	display: block;
	font-size: 0.875em;
}

/*--------------------------------------------------------
�f�U�C�������p�̃X�^�C��
--------------------------------------------------------*/

/*���L*/
.note{
	display: block;
	padding-left: 1em;
	text-indent: -1em;
}

.note2{
	display: block;
	padding-left: 2em;
	text-indent: -2em;
}

/*�K�{���ځE�x���E�G���[�̕����F*/
.warning,
.error{
	color: #e53935!important;
}

.required{
	display: inline-block;
	color: #e53935!important;
}

/*�T�_*/
.dot{
	position: relative;
	padding-top: 5px;
}

.dot:before{
	position: absolute;
	top: 0;
	left: 50%;
	width: 0.2em;
	height: 0.2em;
	margin-left: -.1em;
	background: #333;
	border-radius: 50%;
	content: "";
}
	
/*����
��IE8���Â��u���E�U������*/
.shadow{
	box-shadow: 4px 4px 0px #e9e9e9;
}

.shadow02{
	box-shadow: 0px 0px 4px #666;
}

.outline{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	border: 1px solid #ccc;
}

.frame{
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	max-width: 95%;
	padding: 8px;
	background: #fff;
	box-shadow: 0px 0px 8px #dadada;
}

.border{
	border: 1px solid #ccc;
}

/*�摜�̃T�C�Y����*/
img.resize10,
html:not(:target) img.resize10{
	height: auto;
	max-width: 10%;
}

img.resize20,
html:not(:target) img.resize20{
	height: auto;
	max-width: 20%;
}

img.resize30,
html:not(:target) img.resize30{
	height: auto;
	max-width: 30%;
}

img.resize40,
html:not(:target) img.resize40{
	height: auto;
	max-width: 40%;
}

img.resize50,
html:not(:target) img.resize50{
	height: auto;
	max-width: 50%;
}

img.resize60,
html:not(:target) img.resize60{
	height: auto;
	max-width: 60%;
}

img.resize70,
html:not(:target) img.resize70{
	height: auto;
	max-width: 70%;
}

img.resize80,
html:not(:target) img.resize80{
	height: auto;
	max-width: 80%;
}

img.resize90,
html:not(:target) img.resize90{
	height: auto;
	max-width: 90%;
}

/*�~
��IE8���Â��u���E�U������*/
.circle{
	border-radius: 50%;
}

/*�p��
��IE8���Â��u���E�U������*/
.rc4{ border-radius: 4px; }
.rc4-tl{ border-top-left-radius: 4px; }
.rc4-tr{ border-top-right-radius: 4px; }
.rc4-bl{ border-bottom-left-radius: 4px; }
.rc4-br{ border-bottom-right-radius: 4px; }

.rc8{ border-radius: 8px; }
.rc8-tl{ border-top-left-radius: 8px; }
.rc8-tr{ border-top-right-radius: 8px; }
.rc8-bl{ border-bottom-left-radius: 8px; }
.rc8-br{ border-bottom-right-radius: 8px; }

.rc12{ border-radius: 12px; }
.rc12-tl{ border-top-left-radius: 12px; }
.rc12-tr{ border-top-right-radius: 12px; }
.rc12-bl{ border-bottom-left-radius: 12px; }
.rc12-br{ border-bottom-right-radius: 12px; }

/*�p�ے����`
��IE8���Â��u���E�U������
������100px�܂�*/
.rc50{
	border-radius: 50px;
}

/*�����p�l�� ��IE8���Â��u���E�U������*/
.transparent-panel-wrap{
	padding: 1em;
	background: url(./images/sample09.jpg) center center;
	-webkit-background-size: cover;
	background-size: cover;
}

.transparent-panel{
	padding: 1em;
	background-color: rgba(255,255,255,0.7);
	background-color: #ffffff\9; /*IE8�ւ̑Ή�*/
}

html:not(:target) .transparent-panel{
	background-color: rgba(255,255,255,0.7); /*IE9�ȏ�ւ̑Ή�*/
}

/*��荞��
�����o�C�����ɂ���������Ȃ�*/
.fl-l{
	float: left;
	margin: 0 1em 1em 0;
}

.fl-r{
	float: right;
	margin: 0 0 1em 1em;
}

.fl-c{ clear: both; }

/*��荞��
�����o�C�����ɂ͉�荞�݉���*/
.left{
	float: left;
	margin: 0 1em 1em 0;
}

.right{
	float: right;
	margin: 0 0 1em 1em;
}

/*�����̉��ʒu*/
.al-l{ text-align: left; }
.al-r{ text-align: right; }
.al-c{ text-align: center; }

/*�����̏c�ʒu*/
.vl-t{ vertical-align: top!important; }/*���*/
.vl-m{ vertical-align: middle!important; }/*������*/
.vl-b{ vertical-align: bottom!important; }/*����*/

/*����̃u���b�N����̋����imargin�j*/
.m0{ margin: 0!important; }/*���肩���margin��0��*/
.m0-t{ margin-top: 0!important; }/*�ォ���margin��0��*/
.m0-r{ margin-right: 0!important; }/*�E�����margin��0��*/
.m0-b{ margin-bottom: 0!important; }/*�������margin��0��*/
.m0-l{ margin-left: 0!important; }/*�������margin��0��*/

.m5{ margin: 5px!important; }
.m5-t{ margin-top: 5px!important; }
.m5-r{ margin-right: 5px!important; }
.m5-b{ margin-bottom: 5px!important; }
.m5-l{ margin-left: 5px!important; }

.m10{ margin: 10px!important; }
.m10-t{ margin-top: 10px!important; }
.m10-r{ margin-right: 10px!important; }
.m10-b{ margin-bottom: 10px!important; }
.m10-l{ margin-left: 10px!important; }

.m15{ margin: 15px!important; }
.m15-t{ margin-top: 15px!important; }
.m15-r{ margin-right: 15px!important; }
.m15-b{ margin-bottom: 15px!important; }
.m15-l{ margin-left: 15px!important; }

.m20{ margin: 20px!important; }
.m20-t{ margin-top: 20px!important; }
.m20-r{ margin-right: 20px!important; }
.m20-b{ margin-bottom: 20px!important; }
.m20-l{ margin-left: 20px!important; }

.m25{ margin: 25px!important; }
.m25-t{ margin-top: 25px!important; }
.m25-r{ margin-right: 25px!important; }
.m25-b{ margin-bottom: 25px!important; }
.m25-l{ margin-left: 25px!important; }

.m30{ margin: 30px!important; }
.m30-t{ margin-top: 30px!important; }
.m30-r{ margin-right: 30px!important; }
.m30-b{ margin-bottom: 30px!important; }
.m30-l{ margin-left: 30px!important; }

.m40{ margin: 40px!important; }
.m40-t{ margin-top: 40px!important; }
.m40-r{ margin-right: 40px!important; }
.m40-b{ margin-bottom: 40px!important; }
.m40-l{ margin-left: 40px!important; }

.m50{ margin: 50px!important; }
.m50-t{ margin-top: 50px!important; }
.m50-r{ margin-right: 50px!important; }
.m50-b{ margin-bottom: 50px!important; }
.m50-l{ margin-left: 50px!important; }

.m60{ margin: 60px!important; }
.m60-t{ margin-top: 60px!important; }
.m60-r{ margin-right: 60px!important; }
.m60-b{ margin-bottom: 60px!important; }
.m60-l{ margin-left: 60px!important; }

.m70{ margin: 70px!important; }
.m70-t{ margin-top: 70px!important; }
.m70-r{ margin-right: 70px!important; }
.m70-b{ margin-bottom: 70px!important; }
.m70-l{ margin-left: 70px!important; }

.m80{ margin: 80px!important; }
.m80-t{ margin-top: 80px!important; }
.m80-r{ margin-right: 80px!important; }
.m80-b{ margin-bottom: 80px!important; }
.m80-l{ margin-left: 80px!important; }

.m90{ margin: 90px!important; }
.m90-t{ margin-top: 90px!important; }
.m90-r{ margin-right: 90px!important; }
.m90-b{ margin-bottom: 90px!important; }
.m90-l{ margin-left: 90px!important; }

.m100{ margin: 100px!important; }
.m100-t{ margin-top: 100px!important; }
.m100-r{ margin-right: 100px!important; }
.m100-b{ margin-bottom: 100px!important; }
.m100-l{ margin-left: 100px!important; }

.m120{ margin: 120px!important; }
.m120-t{ margin-top: 120px!important; }
.m120-r{ margin-right: 120px!important; }
.m120-b{ margin-bottom: 120px!important; }
.m120-l{ margin-left: 120px!important; }

.m150{ margin: 150px!important; }
.m150-t{ margin-top: 150px!important; }
.m150-r{ margin-right: 150px!important; }
.m150-b{ margin-bottom: 150px!important; }
.m150-l{ margin-left: 150px!important; }

.m200{ margin: 200px!important; }
.m200-t{ margin-top: 200px!important; }
.m200-r{ margin-right: 200px!important; }
.m200-b{ margin-bottom: 200px!important; }
.m200-l{ margin-left: 200px!important; }

.m300{ margin: 300px!important; }
.m300-t{ margin-top: 300px!important; }
.m300-r{ margin-right: 300px!important; }
.m300-b{ margin-bottom: 300px!important; }
.m300-l{ margin-left: 300px!important; }


/*����̃u���b�N����̋����ipadding�j*/
.p0{ padding: 0!important; }
.p0-t{ padding-top: 0!important; }
.p0-r{ padding-right: 0!important; }
.p0-b{ padding-bottom: 0!important; }
.p0-l{ padding-left: 0!important; }

.p5{ padding: 5px!important; }
.p5-t{ padding-top: 5px!important; }
.p5-r{ padding-right: 5px!important; }
.p5-b{ padding-bottom: 5px!important; }
.p5-l{ padding-left: 5px!important; }

.p10{ padding: 10px!important; }
.p10-t{ padding-top: 10px!important; }
.p10-r{ padding-right: 10px!important; }
.p10-b{ padding-bottom: 10px!important; }
.p10-l{ padding-left: 10px!important; }

.p15{ padding: 15px!important; }
.p15-t{ padding-top: 15px!important; }
.p15-r{ padding-right: 15px!important; }
.p15-b{ padding-bottom: 15px!important; }
.p15-l{ padding-left: 15px!important; }

.p20{ padding: 20px!important; }
.p20-t{ padding-top: 20px!important; }
.p20-r{ padding-right: 20px!important; }
.p20-b{ padding-bottom: 20px!important; }
.p20-l{ padding-left: 20px!important; }

.p25{ padding: 25px!important; }
.p25-t{ padding-top: 25px!important; }
.p25-r{ padding-right: 25px!important; }
.p25-b{ padding-bottom: 25px!important; }
.p25-l{ padding-left: 25px!important; }

.p30{ padding: 30px!important; }
.p30-t{ padding-top: 30px!important; }
.p30-r{ padding-right: 30px!important; }
.p30-b{ padding-bottom: 30px!important; }
.p30-l{ padding-left: 30px!important; }

.p40{ padding: 40px!important; }
.p40-t{ padding-top: 40px!important; }
.p40-r{ padding-right: 40px!important; }
.p40-b{ padding-bottom: 40px!important; }
.p40-l{ padding-left: 40px!important; }

.p50{ padding: 50px!important; }
.p50-t{ padding-top: 50px!important; }
.p50-r{ padding-right: 50px!important; }
.p50-b{ padding-bottom: 50px!important; }
.p50-l{ padding-left: 50px!important; }

.p60{ padding: 60px!important; }
.p60-t{ padding-top: 60px!important; }
.p60-r{ padding-right: 60px!important; }
.p60-b{ padding-bottom: 60px!important; }
.p60-l{ padding-left: 60px!important; }

.p70{ padding: 70px!important; }
.p70-t{ padding-top: 70px!important; }
.p70-r{ padding-right: 70px!important; }
.p70-b{ padding-bottom: 70px!important; }
.p70-l{ padding-left: 70px!important; }

.p80{ padding: 80px!important; }
.p80-t{ padding-top: 80px!important; }
.p80-r{ padding-right: 80px!important; }
.p80-b{ padding-bottom: 80px!important; }
.p80-l{ padding-left: 80px!important; }

.p90{ padding: 90px!important; }
.p90-t{ padding-top: 90px!important; }
.p90-r{ padding-right: 90px!important; }
.p90-b{ padding-bottom: 90px!important; }
.p90-l{ padding-left: 90px!important; }

.p100{ padding: 100px!important; }
.p100-t{ padding-top: 100px!important; }
.p100-r{ padding-right: 100px!important; }
.p100-b{ padding-bottom: 100px!important; }
.p100-l{ padding-left: 100px!important; }

/*�t�H���g�̑���*/
.b{ font-weight: bold!important; }/*����*/
.normal{ font-weight: normal!important; }/*����������*/

/*�t�H���g�T�C�Y�̐ݒ�*/
.big{ font-size: 1.2em!important; }
.big2{ font-size: 1.5em!important; }
.big3{ font-size: 1.8em!important; }
.small{ font-size: 0.8em!important; }

.f08em{ font-size: 0.8em; }
.f09em{ font-size: 0.9em; }
.f10em{ font-size: 1.0em; }
.f11em{ font-size: 1.1em; }
.f12em{ font-size: 1.2em; }
.f13em{ font-size: 1.3em; }
.f14em{ font-size: 1.4em; }
.f15em{ font-size: 1.5em; }
.f16em{ font-size: 1.6em; }
.f17em{ font-size: 1.7em; }
.f18em{ font-size: 1.8em; }
.f19em{ font-size: 1.9em; }
.f20em{ font-size: 2.0em; }
.f21em{ font-size: 2.1em; }
.f22em{ font-size: 2.2em; }
.f23em{ font-size: 2.3em; }
.f24em{ font-size: 2.4em; }
.f25em{ font-size: 2.5em; }
.f26em{ font-size: 2.6em; }
.f27em{ font-size: 2.7em; }
.f28em{ font-size: 2.8em; }
.f29em{ font-size: 2.9em; }
.f30em{ font-size: 3.0em; }

.f8pt{ font-size: 8.5pt; }
.f9pt{ font-size: 9.0pt; }
.f10pt{ font-size: 10pt; }
.f11pt{ font-size: 11pt; }
.f12pt{ font-size: 12pt; }
.f13pt{ font-size: 13pt; }
.f14pt{ font-size: 14pt; }
.f15pt{ font-size: 15pt; }
.f16pt{ font-size: 16pt; }
.f17pt{ font-size: 17pt; }
.f18pt{ font-size: 18pt; }
.f19pt{ font-size: 19pt; }
.f20pt{ font-size: 20pt; }
.f21pt{ font-size: 21pt; }
.f22pt{ font-size: 22pt; }
.f23pt{ font-size: 23pt; }
.f24pt{ font-size: 24pt; }

/*�t�H���g�̐F�ݒ�*/
.red{ color: #e53935!important; }/*��*/
.blue{ color: #0000dd!important; }/*��*/
.green{ color: #4caf50!important; }/*��*/
.yellow{ color: #ffff00!important; }/*��*/
.navy{ color: #3f51b5!important; }/*��*/
.orange{ color: #ff9800!important; }/*��*/
.pink{ color: #ec407a!important; }/*�s���N*/
.purple{ color: #9c27b0!important; }/*��*/
.olive{ color: #808000!important; }/*�I���[�u*/
.lime{ color: #00ff00!important; }/*����*/
.aqua{ color: #00bcd4!important; }/*���F*/
.black{ color: #000!important; }/*��*/
.gray{ color: #ccc!important; }/*�D*/
.white{ color: #fff!important; }/*��*/
.brown{ color: #6d4c33!important; }/*��*/

/*�}�[�J�[�\���i�w�i�ɒ��F�j*/
.box-yellow,
.box-orange,
.box-pink,
.box-lime,
.box-gray{ padding: 2px; }

.box-yellow{ background-color: #ff6; }/*��*/
.box-orange{ background-color: #f90; }/*��*/
.box-pink{ background-color: #ffccff; }/*�s���N*/
.box-lime{ background-color: #9f9; }/*����*/
.box-gray{ background-color: #ccc; }/*�D*/


/*�s�Ԃ̐ݒ�*/
.lh10{ line-height: 1.0!important; }
.lh11{ line-height: 1.1!important; }
.lh12{ line-height: 1.2!important; }
.lh13{ line-height: 1.3!important; }
.lh14{ line-height: 1.4!important; }
.lh15{ line-height: 1.5!important; }
.lh16{ line-height: 1.6!important; }
.lh17{ line-height: 1.7!important; }
.lh18{ line-height: 1.8!important; }
.lh19{ line-height: 1.9!important; }
.lh20{ line-height: 2.0!important; }

/*�������w��*/
.w05{ width: 5%; }
.w10{ width: 10%; }
.w15{ width: 15%; }
.w20{ width: 20%; }
.w25{ width: 25%; }
.w30{ width: 30%; }
.w35{ width: 35%; }
.w40{ width: 40%; }
.w45{ width: 45%; }
.w50{ width: 50%; }
.w55{ width: 55%; }
.w60{ width: 60%; }
.w65{ width: 65%; }
.w70{ width: 70%; }
.w75{ width: 75%; }
.w80{ width: 80%; }
.w85{ width: 85%; }
.w90{ width: 90%; }
.w95{ width: 95%; }
.w100{ width: 100%; }

/*�����������̐ݒ�*/
.underline{ text-decoration: underline!important; }
.del{ text-decoration: line-through; }
.noborder{ border: 0!important; }/*�g���𖳂���*/

/*�d�Ȃ�̗D��x*/
.z1{ z-index: 1!important; }
.z2{ z-index: 2!important; }
.z3{ z-index: 3!important; }
.z4{ z-index: 4!important; }
.z5{ z-index: 5!important; }
.z10{ z-index: 10!important; }
.z20{ z-index: 20!important; }
.z30{ z-index: 30!important; }
.z40{ z-index: 40!important; }
.z50{ z-index: 50!important; }

/*�����у��X�g*/
.inline{ margin: 1em 0; padding: 0; }
.inline li{
	display: inline;
	list-style-type: none;
}

/*�}�[�J�[�����̃��X�g*/
.none{ margin: 1em 0; padding: 0; }
.none li{ list-style-type: none; }


/*------------------------------------------------------------
������̑O�ɃA�C�R��
-------------------------------------------------------------*/

/*�|�C���g�A�C�R���A�C�R��*/
.icon-point{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-point.png) left 3px no-repeat;
}

.icon-point-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-point-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-point{
			background: url(./images/icon/icon-point@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-point-l{
			background: url(./images/icon/icon-point-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*���ӃA�C�R��*/
.icon-caution{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-caution.png) left 3px no-repeat;
}

.icon-caution-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-caution-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-caution{
			background: url(./images/icon/icon-caution@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-caution-l{
			background: url(./images/icon/icon-caution-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*NEW�A�C�R��*/
.icon-new{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-new.png) left 3px no-repeat;
}

.icon-new-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-new-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-new{
			background: url(./images/icon/icon-new@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-new-l{
			background: url(./images/icon/icon-new-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*���S�҃A�C�R��*/
.icon-wakaba{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-wakaba.png) left 3px no-repeat;
}

.icon-wakaba-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-wakaba-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-wakaba{
			background: url(./images/icon/icon-wakaba@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-wakaba-l{
			background: url(./images/icon/icon-wakaba-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*�ʃE�C���h�E�A�C�R��*/
.icon-blank{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-blank.png) left 3px no-repeat;
}

.icon-blank-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-blank-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-blank{
			background: url(./images/icon/icon-blank@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-blank-l{
			background: url(./images/icon/icon-blank-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*����A�C�R��*/
.icon-arrow-t{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-arrow-t.png) left 3px no-repeat;
}

.icon-arrow-t-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-arrow-t-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-arrow-t{
			background: url(./images/icon/icon-arrow-t@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-arrow-t-l{
			background: url(./images/icon/icon-arrow-t-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*���E�A�C�R��*/
.icon-arrow-r{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-arrow-r.png) left 3px no-repeat;
}

.icon-arrow-r-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-arrow-r-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-arrow-r{
			background: url(./images/icon/icon-arrow-r@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-arrow-r-l{
			background: url(./images/icon/icon-arrow-r-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*��󉺃A�C�R��*/
.icon-arrow-b{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-arrow-b.png) left 3px no-repeat;
}

.icon-arrow-b-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-arrow-b-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-arrow-b{
			background: url(./images/icon/icon-arrow-b@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-arrow-b-l{
			background: url(./images/icon/icon-arrow-b-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*��󍶃A�C�R��*/
.icon-arrow-l{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-arrow-l.png) left 3px no-repeat;
}

.icon-arrow-l-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-arrow-l-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-arrow-l{
			background: url(./images/icon/icon-arrow-l@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-arrow-l-l{
			background: url(./images/icon/icon-arrow-l-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*�_�E�����[�h�pPD�A�C�R��*/
.icon-dl{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-dl.png) left 3px no-repeat;
}

.icon-dl-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-dl-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-dl{
			background: url(./images/icon/icon-dl@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-dl-l{
			background: url(./images/icon/icon-dl-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*PDF�A�C�R��*/
.icon-pdf{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-pdf.png) left 3px no-repeat;
}

.icon-pdf-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-pdf-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-pdf{
			background: url(./images/icon/icon-pdf@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-pdf-l{
			background: url(./images/icon/icon-pdf-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*Zip�A�C�R��*/
.icon-zip{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-zip.png) left 3px no-repeat;
}


.icon-zip-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-zip-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-zip{
			background: url(./images/icon/icon-zip@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-zip-l{
			background: url(./images/icon/icon-zip-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*���[���A�C�R��*/
.icon-mail{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-mail.png) left 3px no-repeat;
}

.icon-mail-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-mail-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-mail{
			background: url(./images/icon/icon-mail@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-mail-l{
			background: url(./images/icon/icon-mail-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*�V���b�s���O�J�[�g�A�C�R��*/
.icon-cart{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-cart.png) left 3px no-repeat;
}

.icon-cart-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-cart-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-cart{
			background: url(./images/icon/icon-cart@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-cart-l{
			background: url(./images/icon/icon-cart-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*���߂��˃A�C�R��*/
.icon-search{
	padding: 0 0 0 50px;
	background: url(./images/icon/icon-search.png) left center no-repeat;
}

.icon-search-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-search-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-search{
			background: url(./images/icon/icon-search.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 36px 38px;
		}

		.icon-search-l{
			background: url(./images/icon/icon-search-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*�z�[���A�C�R��*/
.icon-home{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-home.png) left 3px no-repeat;
}

.icon-home-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-home-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-home{
			background: url(./images/icon/icon-home@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-home-l{
			background: url(./images/icon/icon-home-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*�t�H���_�A�C�R��*/
.icon-folder{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-folder.png) left 3px no-repeat;
}

.icon-folder-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-folder-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-folder{
			background: url(./images/icon/icon-folder@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-folder-l{
			background: url(./images/icon/icon-folder-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*���v�A�C�R��*/
.icon-time{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-time.png) left 3px no-repeat;
}

.icon-time-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-time-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-time{
			background: url(./images/icon/icon-time@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-time-l{
			background: url(./images/icon/icon-time-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*�J�����_�[�A�C�R��*/
.icon-calendar{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-calendar.png) left 3px no-repeat;
}


.icon-calendar-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-calendar-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-calendar{
			background: url(./images/icon/icon-calendar@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-calendar-l{
			background: url(./images/icon/icon-calendar-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*RSS�A�C�R��*/
.icon-rss{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-rss.png) left 3px no-repeat;
}

.icon-rss-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-rss-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-rss{
			background: url(./images/icon/icon-rss@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-rss-l{
			background: url(./images/icon/icon-rss-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*�r���A�C�R��*/
.icon-building{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-building.png) left 3px no-repeat;
}

.icon-building-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-building-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-building{
			background: url(./images/icon/icon-building@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-building-l{
			background: url(./images/icon/icon-building-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

/*�}�b�v�A�C�R��*/
.icon-map{
	padding: 0 0 0 30px;
	background: url(./images/icon/icon-map.png) left 3px no-repeat;
}

.icon-map-l{
	padding: 10px 0 10px 60px;
	background: url(./images/icon/icon-map-l.png) left top no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){
		.icon-map{
			background: url(./images/icon/icon-map@2x.png) left 3px no-repeat;
			-webkit-background-size: 24px 24px;
			background-size: 24px 24px;
		}

		.icon-map-l{
			background: url(./images/icon/icon-map-l@2x.png) left top no-repeat;
			-webkit-background-size: 48px 48px;
			background-size: 48px 48px;
		}
	}

.outbound{
	padding: 3px;
	padding-left: 15px;
	background: url(./images/icon/icon-outbound-link.png) left center no-repeat;
}

	/*Retina�i���𑜓x�j�f�B�X�v���C�p*/
	@media screen and (-webkit-min-device-pixel-ratio:2),
	(min-resolution: 2dppx){

		.outbound{
			background: url(./images/icon/icon-outbound-link@2x.png) left center no-repeat;
			-webkit-background-size: 12px 13px;
			background-size: 12px 13px;
		}

	}

/*--------------------------------------------------------
float�̉�荞�݂�����
--------------------------------------------------------*/
.site-header-conts:after,
.main-body-in:after,
.article-body:after,
.section-in:after,
.col4-wrap:after,
.col3-wrap:after,
.col2-wrap:after,
.news-item:after,
.related-articles-thumbs01 li:after,
.btn-area:after,
.page-nav-bf:after,
.global-nav-in li ul:after,
.banner-list:after,
.main-conts dl.cast:after,
.clearfix:after{
	content: '';
	display: block;
	clear: both;
	height: 0;
}




/*--------------------------------------------------------
	�V�K�ǉ�
--------------------------------------------------------*/
h3.goodsname{
    font-weight: bold;
    padding:0;
    margin:0;
    padding: 10px 0 10px 55px;
    background: url(./images/icon/icon-check-list-l.png) left 3px no-repeat;
   	border-bottom:0px solid #0098de;

}
/*--- header �E�u���b�N  --------*/
#header-sub {
	float:right;
	font-size:1.1em;
}
.header-copy {
	
}
.header-list {
/*	overflow:hidden; */
}
.header-list li {
	float:left;
	list-style:none;
	margin:0 10px 10px 0;
}


/*--- �O���[�o���i�r ���ݒn  --------*/
.current-menu-parent > a,
.current-menu-item > a{
	background:#0098de !important;
}

/*--- �O���[�o���i�r �h���b�v�_�E���A�C�R��  --------*/
.nav-arrow{
	position: relative;
	display: inline-block;
	padding: 0;
	vertical-align: middle;
	text-decoration: none;
}
.nav-arrow::before,
.nav-arrow::after{
	position: absolute;
	top: 0;
	bottom: 0;
	left: 0;
	margin: auto;
	content: "";
	vertical-align: middle;
}
.icon-nav::before{
	left: 6px;
	box-sizing: border-box;
	width: 6px;
	height: 6px;
	border: 6px solid transparent;
	border-top: 6px solid #fff;
}




.bnrbox { 
	list-style:none;
	margin-left:10px !important;
	margin-bottom:0 !important;
	display:-webkit-box;/*--- Android�u���E�U�p ---*/
    display:-ms-flexbox;/*--- IE10 ---*/
    display: -webkit-flex;/*--- safari�iPC�j�p ---*/
    display:flex;
    -webkit-box-pack:justify;/*--- Android�u���E�U�p ---*/
    -ms-flex-pack:justify;/*--- IE10 ---*/
    -webkit-justify-content:space-between;/*--- safari�iPC�j�p ---*/
    justify-content:space-between;
}

.conts-list {
}
.conts-list dt {
	clear:both;
	float:left;
	width:65px;
}
.conts-list dd {
	padding:0 0 7px 75px;
	margin-bottom:7px;
	border-bottom:1px dotted #ccc;
	min-height:2em;
}
.sub-conts .conts-list dd {
	min-height:2.5em;
}

ul.arrow li {
	position: relative;
}
ul.arrow li::after,
ul.arrow li::before {
	display: block;
	content: '';
	position: absolute;
}
ul.arrow li::after {
	top: .35em;
	left: -1.2em;
	width: 14px;
	height: 14px;
	background-color: #3498db;
	border-radius: 100%;
}
ul.arrow li::before {
	z-index: 2;
	top: .625em;
	left: -.975em;
	width: 4px;
	height: 4px;
	border-right: 1px solid #fff;
	border-bottom: 1px solid #fff;
	-webkit-transform: rotate(-45deg);
	transform: rotate(-45deg);
}



/*------��������T�� ---------*/
.pickup {
	overflow:hidden;
	margin:0;
	padding:0;
}
.pickup {
	border:7px solid #57BDE8;
	padding:10px 15px;
}
.pickup li {
	list-style:none;
	float:left;
	margin-right:10px;
	width:8em;
}

.detail_search,
.detail_search th,
.detail_search td{
	border:1px solid #57BDE8;
}
.detail_search th {
	background:#DAF3FD;
}


.pos_center {
	text-align:center;
}



/*------��ށE�����ŒT�� ---------*/

.search-main {
	display:flex;
}
.search-main,
.search-sub {
	overflow:hidden;
	margin:0;
}
.search-main li {
	position:relative;
	float:left;
	list-style:none;
	border:1px solid #57BDE8;
	margin:0 15px 15px 0;
	text-align:center;
	width:100%;
	border-radius:5px;
}
.search-main li span {
	font-size:.8em;
}
.search-main li a {
	display:block;
	width:100%;
	height:100%;
	position:absolute;
	left:0;
	top:0;
}
.search-main li a strong {
	line-height:3;
}
.search-main li.icon-list-clock,
.search-main li.icon-list-pencil,
.search-main li.icon-list-book,
.search-main li.icon-list-search {
	padding:35px 12px;
}
.search-main li.icon-list-clock {
	background:#DAF3FD url(./images/icon/icon-list-clock.png) 96% 85% no-repeat;
}
.search-main li.icon-list-pencil {
	background:#DAF3FD url(./images/icon/icon-list-pencil.png) 96% 85% no-repeat;
}
.search-main li.icon-list-book {
	background:#DAF3FD url(./images/icon/icon-list-book.png) 96% 85% no-repeat;
}
.search-main li.icon-list-search {
	background:#DAF3FD url(./images/icon/icon-list-search.png) 96% 85% no-repeat;
}

.search-sub li {
	float:left;
	list-style:none;
	margin:0 10px 10px 0;
	padding:5px 20px;
	border:1px solid #57BDE8;
	background: #EBF2FB;
	font-size:.8em;
	text-align:center;
	width:10em;
	border-radius:5px;
}
.search-sub li a {
	display:block;
	width:100%;
	height:100%;
	left:0;
	top:0;
}


/*------�A�C�R�� ---------*/
.icon-book {
	padding:10px 0 10px 50px;
	background: url(./images/icon/icon-book.png) left top no-repeat;
}

	



.flex-box {
	-webkit-justify-content: space-between; /* Safari */
	justify-content:         space-between;
}

.rank-box p{
	font-size:20px;
}

/*------�O���i�r�㕔�Œ�---------*/

/*.site-header {
  position: fixed;
  width: 100%;
  background-color: #fff;
  z-index: 9999;
  top: 0;
}
.main-body {
   position: relative;
   top: 200px;
}
@media only screen and (max-width : 640px){
.site-header {
   position: static;
}
.main-body {
   position: relative;
   top: 0;
}
}
*/

/* �������ʃe�[�u�� */
.search_table_list{
	font-size: 0.9em;
	line-height: 1.3em;
}

th.search_title{
	width:20%
}

/*�L���h���b�O�֎~*/
article{
    -moz-user-select: none;
    -webkit-user-select: none;
    -ms-user-select: none;
}

/* �{�^���A�j���[�V���� */
.btn_animation {
	animation: prun 1.5s ease-in infinite;
	-webkit-animation: prun 1.5s ease-in infinite;
}

@keyframes prun {
	48%, 62% { transform: scale(1.0, 1.0) }
	50% { transform: scale(1.1, 0.9) }
	56% { transform: scale(0.9, 1.1) translate(0, -5px) }
	59% { transform: scale(1.0, 1.0) translate(0, -3px) }
}
@-webkit-keyframes prun{
	48%, 62% {-webkit-transform: scale(1.0, 1.0)}
	50% {-webkit-transform: scale(1.1, 0.9)}
	56% {-webkit-transform: scale(0.9, 1.1) translate(0, -5px)}
	59% {-webkit-transform: scale(1.0, 1.0) translate(0, -3px)}
}



/* selekit */
td.detail_title{
	background-color: #DAF3FD;
}

#close_btn{
	display: inline-block;
	font-size:100%;
	padding: 1em;
	border: 0;
	background: #696A6B;
	color: #fff;
	text-decoration: none;
	border-radius: 8px;
	box-shadow: 4px 4px 0px #d0d0d0;
	padding: 5px 15px 5px 10px!important;
}

#close_btn:hover,
#close_btn:active,
#close_btn:focus{
	background: #555555;
	color: #FFF;
	box-shadow: 4px 4px 0px #e9e9e9;
	cursor: pointer;
}

.service_image{
	width:40%;
	float:left
}

.service_table td{
	font-size:90%
}

.service_point{
	clear:both;
	font-size:80%
}

/*---------------------------------------------------------------------
	generated by Keni Template Maker Ver.7.0 on 2016-02-26 15:15:44
----------------------------------------------------------------------*/
