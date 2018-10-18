body, html {
	font-family: 'Montserrat', sans-serif;
	text-rendering: optimizeLegibility !important;
	-webkit-font-smoothing: antialiased !important;
	color: #555;
	font-weight: 400;
	width: 100% !important;
	height: 100% !important;
}
h1 {
	color: #FADADD;
	font-size: 64px;
	font-weight: 800;
	margin-top: 0;
	text-transform: uppercase;
	margin-bottom: 10px;
}
h2 {
	margin: 0 0 20px 0;
	font-weight: 700;
	font-size: 42px;
	color: #702963;
	text-transform: uppercase;
}
h3 {
	font-size: 18px;
	text-transform: uppercase;
	margin-bottom: 20px;
}
h4 {
	font-size: 14px;
	letter-spacing: 1px;
	margin-bottom: 20px;
	text-transform: uppercase;
}
h5 {
	text-transform: uppercase;
	font-weight: 700;
	line-height: 20px;
}
p {
	font-family: 'Roboto', sans-serif;
	font-size: 15px;
	font-weight: 400;
	color: #5D3954;
}
p.intro {
	margin: 12px 0 0;
	line-height: 24px;
}
a {
	color: #222;
}
a:hover, a:focus {
	text-decoration: none;
	color: #000;
}
ul, ol {
	list-style: none;
}
ul, ol {
	padding: 0;
	webkit-padding: 0;
	moz-padding: 0;
}
hr {
	height: 6px;
	width: 70px;
	position: relative;
	background: #444;
	margin-bottom: 20px;
	margin-left: 0;
	border: 0;
}
.btn:active, .btn.active {
	background-image: none;
	outline: 0;
	-webkit-box-shadow: none;
	box-shadow: none;
}
a:focus, .btn:focus, .btn:active:focus, .btn.active:focus, .btn.focus, .btn:active.focus, .btn.active.focus {
	outline: none;
	outline-offset: none;
}
.section-title {
	margin-bottom: 50px;
}
.btn-custom {
	font-family: 'Montserrat', sans-serif;
	text-transform: uppercase;
	color: #444;
	background-color: transparent;
	border: 2px solid #444;
	padding: 14px 20px;
	margin: 0;
	font-size: 14px;
	border-radius: 0;
	margin-top: 20px;
	margin-right: 30px;
	transition: all 0.5s;
}
.btn-custom:hover, .btn-custom:focus, .btn-custom.focus, .btn-custom:active, .btn-custom.active {
	color: #DDA0DD;
	background-color: #5D3954;
}
/* Header Section */
.intro {
	display: table;
	width: 100%;
	padding: 0;
	margin-bottom: 80px;
	background: url(../img/intro-bg.jpg) no-repeat right top;
	background-color: #5D3954;
	-webkit-background-size: cover;
	-moz-background-size: cover;
	background-size: cover;
	-o-background-size: cover;
}
.intro .overlay {
	/* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#ffffff+0,d5dade+100&0.5+0,0+100 */
	background: -moz-linear-gradient(left, rgba(255,255,255,0.5) 0%, rgba(213,218,222,0) 100%); /* FF3.6-15 */
	background: -webkit-linear-gradient(left, rgba(255,255,255,0.5) 0%, rgba(213,218,222,0) 100%); /* Chrome10-25,Safari5.1-6 */
	background: linear-gradient(to right, rgba(255,255,255,0.5) 0%, rgba(213,218,222,0) 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#80ffffff', endColorstr='#00d5dade', GradientType=1 ); /* IE6-9 */
}
.intro .fa {
	font-size: 94px;
	margin-bottom: 40px;
	color: #fff;
}
.intro p {
	color: #444;
	margin: 10px 0 20px 0;
	font-size: 22px;
}
header .intro-text {
	padding-top: 250px;
	padding-bottom: 200px;
}
/* Portfolio Section */
#portfolio {
	padding: 40px 0 100px 0;
}
.categories {
	margin-bottom: 80px;
}
ul.cat li {
	display: inline-block;
}
ol.type li {
	display: inline-block;
	margin-right: 20px;
}
ol.type li a {
	font-family: 'Montserrat', sans-serif;
	color: #444;
	font-size: 14px;
	padding: 10px 20px;
	border: 2px solid #444;
	border-radius: 0;
	text-transform: uppercase;
}
ol.type li a.active {
	background: #444;
	color: #eee;
}
ol.type li a:hover {
	background: #444;
	color: #eee;
}
.isotope-item {
	z-index: 2
}
.isotope-hidden.isotope-item {
	z-index: 1
}
.isotope, .isotope .isotope-item {
	/* change duration value to whatever you like */
	-webkit-transition-duration: 0.8s;
	-moz-transition-duration: 0.8s;
	transition-duration: 0.8s;
}
.isotope-item {
	margin-right: -1px;
	-webkit-backface-visibility: hidden;
	backface-visibility: hidden;
	padding: 0 10px;
}
.isotope {
	-webkit-backface-visibility: hidden;
	backface-visibility: hidden;
	-webkit-transition-property: height, width;
	-moz-transition-property: height, width;
	transition-property: height, width;
}
.isotope .isotope-item {
	-webkit-backface-visibility: hidden;
	backface-visibility: hidden;
	-webkit-transition-property: -webkit-transform, opacity;
	-moz-transition-property: -moz-transform, opacity;
	transition-property: transform, opacity;
}
.portfolio-item {
	margin: 10px 0;
	-webkit-transition: all 0.5s ease-out;
	-moz-transition: all 0.5s ease-out;
	-ms-transition: all 0.5s ease-out;
	-o-transition: all 0.5s ease-out;
	transition: all 0.5s ease-out;
}
.portfolio-item .hover-bg {
	overflow: hidden;
	position: relative;
}
.hover-bg .hover-text {
	position: absolute;
	text-align: center;
	margin: 0 auto;
	color: #333;
	background: rgba(255, 255, 255, 0.75);
	height: 100%;
	width: 100%;
	opacity: 0;
	transition: all 0.5s;
}
.hover-bg .hover-text .overlay-caption {
	display: table;
	height: 100%;
	width: 100%;
}
.hover-bg .hover-text .overlay-caption .overlay-content {
	display: table-cell;
	vertical-align: middle;
}
.hover-bg:hover .hover-text {
	opacity: 1;
}
/* Contact Section */
#contact {
	padding: 60px 0 60px 0;
	background: #262626;
}
#contact h2 {
	font-weight: 400;
	color: #777;
	margin: 60px 0;
}
#contact img {
	width: 140px;
	margin: 5px 30px 10px 0;
}
#contact p {
	color: #666;
	margin-bottom: 20px;
	line-height: 24px;
}
#contact .social {
	margin-top: 40px;
}
#contact .social ul li {
	display: inline-block;
	margin-right: 20px;
}
#contact .social i.fa {
	font-size: 26px;
	padding: 4px;
	color: #777;
	transition: all 0.3s;
}
#contact .social i.fa:hover {
	color: #eee;
}
#contact form {
	padding: 0;
}
#contact .text-danger {
	color: #cc0033;
	text-align: left;
}
label {
	font-size: 12px;
	font-weight: 400;
	float: left;
}
#contact .form-control {
	display: block;
	width: 100%;
	padding: 6px 12px;
	font-size: 15px;
	font-weight: 400;
	line-height: 1.42857143;
	color: #aaa;
	background-color: #444;
	background-image: none;
	border: 0;
	border-radius: 0;
	-webkit-box-shadow: none;
	box-shadow: none;
	-webkit-transition: none;
	-o-transition: none;
	transition: none;
}
#contact .form-control:focus {
	border-color: #999;
	outline: 0;
	-webkit-box-shadow: transparent;
	box-shadow: transparent;
}
.form-control::-webkit-input-placeholder {
color: #777;
}
.form-control:-moz-placeholder {
color: #777;
}
.form-control::-moz-placeholder {
color: #777;
}
.form-control:-ms-input-placeholder {
color: #777;
}
#contact .btn-default {
	font-weight: 400;
	color: #666;
	background-color: transparent;
	border: 2px solid #666;
	padding: 10px 20px;
	margin: 0;
	font-size: 15px;
	border-radius: 0;
	margin-top: 20px;
	text-transform: uppercase;
	transition: all 0.3s;
}
#contact .btn-default:hover, .btn-default:focus, .btn-default.focus, .btn-default:active, .btn-default.active {
	background-color: #666;
	color: #999;
}
/* Footer Section*/
#footer {
	background: #262626;
	padding: 50px 0 20px 0;
}
#footer p {
	font-size: 15px;
	color: #666;
}



<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Ирвин Пенн - Фотограф </title>
<meta name="description" content="">
<meta name="author" content="">

<!-- Favicons
    ================================================== -->
<link rel="shortcut icon" href="img/favicon.ico" type="image/x-icon">
<link rel="apple-touch-icon" href="img/apple-touch-icon.png">
<link rel="apple-touch-icon" sizes="72x72" href="img/apple-touch-icon-72x72.png">
<link rel="apple-touch-icon" sizes="114x114" href="img/apple-touch-icon-114x114.png">

<!-- Bootstrap -->
<link rel="stylesheet" type="text/css"  href="css/bootstrap.css">
<link rel="stylesheet" type="text/css" href="fonts/font-awesome/css/font-awesome.css">

<!-- Stylesheet
    ================================================== -->
<link rel="stylesheet" type="text/css"  href="css/style.css">
<link rel="stylesheet" type="text/css" href="css/nivo-lightbox/nivo-lightbox.css">
<link rel="stylesheet" type="text/css" href="css/nivo-lightbox/default.css">
<link href="https://fonts.googleapis.com/css?family=Montserrat:400,700" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700,900" rel="stylesheet">

<!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
<!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
</head>
<body>
<!-- Header -->
<header id="header">
  <div class="intro">
    <div class="overlay">
      <div class="container">
        <div class="row">
          <div class="col-xs-12 col-md-8">
            <div class="intro-text"> 
             <div class="img-item">
              <h1>Ирвин Пенн</h1>
              <p>Фотограф</p>
              <a href="#portfolio" class="btn btn-custom btn-lg page-scroll">Работы</a> <a href="#contact" class="btn btn-custom btn-lg page-scroll">Обо мне</a> </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </header> 
<!-- Portfolio Section -->
<div id="portfolio">
  <div class="container">
    <div class="section-title">
      <h2>Работы</h2>
    </div>
    <div class="categories">
      <ul class="cat">
        <li>
          <ol class="type">
            <li><a href="#" data-filter="*" class="active">Все</a></li>
            <li><a href="#" data-filter=".lorem">Мода</a></li>
            <li><a href="#" data-filter=".dolor">Портреты знаменитостей</a></li>
            <li><a href="#" data-filter=".adipiscing">Натюрморты</a></li>
          </ol>
        </li>
      </ul>
    </div>
    <div class="row">
      <div class="portfolio-items">
        <div class="col-sm-6 col-md-4 lorem">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_8.jpg" title="в платье осенней листвы" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>в платье осенней листвы</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_8.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 adipiscing">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_5.jpg" title="Геометрические фрукты" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>Геометрические фрукты</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_5.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 dolor">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_9.jpg" title="Немолод, но так же хорош" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>Немолод, но так же хорош</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_9.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 adipiscing">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_7.jpg" title="некудышный визажист" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>некудышный визажист</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_7.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 dolor">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_15.jpg" title="Приятные сны" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>Приятные сны</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_15.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 dolor">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/80_6d198d6c6a24fc0d21d6ab95e6961815.jpg" title="Магия чёрного" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>Магия чёрного</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/80_6d198d6c6a24fc0d21d6ab95e6961815.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 adipiscing">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_2.jpg" title="Цвет настроения какой пожелаешь" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>Цвет настроения какой пожелаешь</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_2.jpg" class="img-responsive" alt="Цвет настроения какой пожелаешь"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 lorem">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/80_d7682cdf10e5ce461727dba4d0c6228e.jpg" title="в сто сорок солнц закат пылал" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>в сто сорок солнц закат пылал</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/80_d7682cdf10e5ce461727dba4d0c6228e.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 adipiscing">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_3.jpg" title="в поисках дома" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>в поисках дома</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_3.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 dolor">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/80_43faafca3cd41d381828877fe797c2e8.jpg" title="чёрный плащ" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>чёрный плащ</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/80_43faafca3cd41d381828877fe797c2e8.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 lorem">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/80_96651b726b38c82e545e7a9527e45de0.jpg" title="Дочь Дракулы" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>Дочь Дракулы</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/80_96651b726b38c82e545e7a9527e45de0.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 dolor">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/80_e6e3b6ecc6fdf2f57735900cea57715c.png" title="вся глубина в твоих глазах" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>вся глубина в твоих глазах</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/80_e6e3b6ecc6fdf2f57735900cea57715c.png" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 adipiscing">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://phnx-static.s3.eu-central-1.amazonaws.com/phnx/archidea/35/90/48/359048/b17445fb202a91ebd409fb836e9022af.jpg" title="завтрак" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>завтрак</h4>
                  </div>
                </div>
              </div>
              <img src="https://phnx-static.s3.eu-central-1.amazonaws.com/phnx/archidea/35/90/48/359048/b17445fb202a91ebd409fb836e9022af.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 dolor">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/80_6aa2597a872e37a7437c4d2540ada1e3.jpg" title="грустная красота" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>грустная красота</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/80_6aa2597a872e37a7437c4d2540ada1e3.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 dolor">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_1.jpg" title="в гостях у принца" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>в гостях у принца</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/irvin_pen_1.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 lorem">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="http://3.bp.blogspot.com/-LuT8i8LGyog/UbhF6_7kJYI/AAAAAAAAG74/hfiTPLco4Ww/s1600/t2_irving_penn_balenciaga.jpg" title="губы бантиком, брови домиком" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>губы бантиком, брови домиком</h4>
                  </div>
                </div>
              </div>
              <img src="http://3.bp.blogspot.com/-LuT8i8LGyog/UbhF6_7kJYI/AAAAAAAAG74/hfiTPLco4Ww/s1600/t2_irving_penn_balenciaga.jpg" class="img-responsive" alt="губы бантиком, брови домиком"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 lorem">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://cameralabs.org/media/lab15/oktybr/21-1/80_6c1720db3ed481dd2d886ed457c4d912.jpg" title="трудно быть женщиной" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>трудно быть женщиной</h4>
                  </div>
                </div>
              </div>
              <img src="https://cameralabs.org/media/lab15/oktybr/21-1/80_6c1720db3ed481dd2d886ed457c4d912.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
        <div class="col-sm-6 col-md-4 adipiscing">
          <div class="portfolio-item">
            <div class="hover-bg"> <a href="https://pre-party.com.ua/uploads/2018/Olya/May/Irving_Penn/Irving_Penn_20.jpg" title="долматинец" data-lightbox-gallery="gallery1">
              <div class="hover-text">
                <div class="overlay-caption">
                  <div class="overlay-content">
                    <h4>долматинец</h4>
                  </div>
                </div>
              </div>
              <img src="https://pre-party.com.ua/uploads/2018/Olya/May/Irving_Penn/Irving_Penn_20.jpg" class="img-responsive" alt="Project Title"> </a> </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- Contact Section -->
<div id="contact">
  <div class="container">
    <h2>Обо мне</h2>
    <div class="col-md-6">
      <div class="section-title">
        <div class="row"> 
          <p>Меня зовут Ирвин Пенн. Фотография - это то, чем я живу. Все свои года я пронёс через это исскуство и рад им делиться с вами. Мои работы это плод любви и труда. Настоящий ценитель красивого и утонченного это заметит невооруженным глазом.</p>
          <p>Проработав несколько лет в модном журнале Vogue, я смог найти свою нишу. А именно любовь к нетревиальному натюрморту, моде и портретам делают моё творчество живым и настоящим. </p>
          <div class="social">
            <ul>
              <li><a href="https://www.instagram.com/lobodez__z/?hl=ru"><i class="fa fa-facebook"></i></a></li>
              <li><a href="https://www.instagram.com/lobodez__z/?hl=ru"><i class="fa fa-instagram"></i></a></li>
              <li><a href="https://www.instagram.com/lobodez__z/?hl=ru"><i class="fa fa-behance"></i></a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <script>
    <form id="myform">
    <form id="myform" method="post">
<label>name</label>
<input type="text" name="name" />
<label>to_name</label>
<input type="text" name="to_name" />
<br><br>
<button>
Send
</button>
</form>

<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

<script type="text/javascript" src="https://cdn.emailjs.com/sdk/2.2.4/email.min.js"></script>
<script type="text/javascript">
   (function(){
      emailjs.init("user_8tm9f5RXD5VusvoXyhgCh");
   })();
</script>
<script>
var myform = $("#myform");
myform.submit(function(event){
	event.preventDefault();

  // Change to your service ID, or keep using the default service
  var service_id = "default_service";
  var template_id = "zvezdapoleey_gmail_com";

  myform.find("button").text("Sending...");
  emailjs.sendForm(service_id,template_id,myform[0])
  	.then(function(){ 
    	alert("Спасибо, мы вскоре с вами свяжемся!");
       myform.find("button").text("Send");
    }, function(err) {
       alert("Извините, попробуйте снова!\r\n Response:\n " + JSON.stringify(err));
       myform.find("button").text("Send");
    });
  return false;
});
</script>

    <div class="col-md-5 col-md-offset-1">
      <div class="section-title">
        <p>Eсли вы желаете со мной связаться, то пишите на почту <strong>zvezdapoleey@gmail.com</strong> или оставьте заявку здесь на сайте </p>
      </div>
      <form name="отправить сообщение" id="бланк" novalidate>
        <div class="row">
          <div class="col-md-6">
            <div class="form-group">
              <input type="текст" id="Имя" class="form-control" name="name" placeholder="Имя" required="required"> 
              <p class="help-block text-danger"></p>
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-group">
              <input type="Email" id="Email" class="form-control" name="email" placeholder="Email" required="required">
              <p class="help-block text-danger"></p>
            </div>
          </div>
        </div>
        <div class="form-group">
          <textarea name="Сообщение" id="Сообщение" class="form-control" rows="4" placeholder="Сообщение" required></textarea>
          <p class="help-block text-danger"></p>
        </div>
        <div id="success"></div>
        <button type="submit" value=“send-message”  class="btn btn-default btn-lg">Оправить</button>
      </form>
    </div>
  </div>
</div>
<div id="footer">
  <div class="container">
    <p>&copy; 2016 Ирвин Пенн. Все права защищены</p>
  </div>
</div>
<script type="text/javascript" src="js/jquery.1.11.1.js"></script> 
<script type="text/javascript" src="js/bootstrap.js"></script> 
<script type="text/javascript" src="js/SmoothScroll.js"></script> 
<script type="text/javascript" src="js/nivo-lightbox.js"></script> 
<script type="text/javascript" src="js/jquery.isotope.js"></script> 
<script type="text/javascript" src="js/jqBootstrapValidation.js"></script> 
<script type="text/javascript" src="js/contact_me.js"></script> 
<script type="text/javascript" src="js/main.js"></script>

</body>
</html>
