# BON-BON
<!DOCTYPE html>
  <html> <!--<![endif]-->
	<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>BON-BON</title>

	<link rel="shortcut icon" href="favicon.ico">

	<link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,700' rel='stylesheet' type='text/css'>

	<!-- Animate.css -->
	<link rel="stylesheet" href="css/animate.css">
	<!-- Icomoon Icon Fonts-->
	<link rel="stylesheet" href="css/icomoon.css">
	<!-- Bootstrap  -->
	<link rel="stylesheet" href="css/bootstrap.css">
	<!-- Owl Carousel -->
	<link rel="stylesheet" href="css/owl.carousel.min.css">
	<link rel="stylesheet" href="css/owl.theme.default.min.css">

	<link rel="stylesheet" href="css/style.css">



	<script src="js/modernizr-2.6.2.min.js"></script>

	</head>
	<body>
	<div class="box-wrap">
		<header role="banner" id="fh5co-header">
			<div class="container">
				<nav class="navbar navbar-default">
					<div class="row">
						<div class="col-md-3">
							<div class="fh5co-navbar-brand">
								<a class="fh5co-logo" href="index.html"><img src="images/logo.png" style="width:150px; height: 55px;"></a>
                <div class="text-center1">
                    <!-- Кнопка, для открытия модального окна -->
                    <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#feedbackForm" id="kek">
        E-mail
                    </button>
                  </div>

                <div class="modal fade" id="feedbackForm" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
                  <div class="modal-dialog" role="document">
                    <div class="modal-content">
                      <div class="modal-header">
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                        <h4 class="modal-title" id="myModalLabel">Зв`яжіться з нами відправивши повідомлення.</h4>
                      </div>

                      <div class="modal-body">

                          <!-- Сообщение, отображаемое в случае успешной отправки данных -->
                          <div class="alert alert-success hidden" role="alert" id="msgSubmit" style="margin-bottom: 0px;">
                            <strong>Увага!</strong> Ваше повідомлення відправлено.
                          </div>

                          <form id="messageForm" enctype="multipart/form-data">
                            <div class="row">
                              <div id="error" class="col-sm-12" style="color: #ff0000; margin-top: 5px; margin-bottom: 5px;"></div>
                              <!-- Имя и email пользователя -->
                              <div class="col-sm-6">
                                <!-- Имя пользователя -->
                                <div class="form-group has-feedback">
                                  <label for="name" class="control-label">Введіть ваше ім`я:</label>
                                  <input type="text" id="name" name="name" class="form-control" required="required" value=""  minlength="2" maxlength="30">
                                  <span class="glyphicon form-control-feedback"></span>
                                </div>
                              </div>
                              <div class="col-sm-6">
                                <!-- Email пользователя -->
                                <div class="form-group has-feedback">
                                  <label for="email" class="control-label">Введіть адрес email:</label>
                                  <input type="email" id="email" name="email" class="form-control" required="required"  value=""  maxlength="30">
                                  <span class="glyphicon form-control-feedback"></span>
                                </div>
                              </div>
                            </div>
                            <!-- Сообщение пользователя -->
                            <div class="form-group has-feedback">
                              <label for="message" class="control-label">Введіть повідомлення:</label>
                              <textarea id="message" class="form-control" rows="3"  minlength="20" maxlength="500" required="required"></textarea>
                            </div>
                            </div>
                            <!-- Кнопка, отправляющая форму по технологии AJAX -->
                            <button name="send-message" type="submit" class="btn btn-primary pull-right" id="btn1" >Відправити повідомлення</button>
                          </form><!-- Конец формы -->
                          <div class="clearfix"></div>
                              </div>
                            </div>
                          </div>
							</div>
						</div>
					</div>
				</nav>
		  </div>
		</header>
		<div class="owl-carousel owl-carousel1 owl-carousel-fullwidth fh5co-light-arrow animate-box" data-animate-effect="fadeIn">
			<div class="item"><a href="images/logo1.png" class="image-popup"><img src="images/first.jpg" alt="image"></a></div>
			<div class="item"><a href="images/logo2.jpg" class="image-popup"><img src="images/im6.jpg" alt="image"></a></div>
		</div>
		<div id="fh5co-media-section">
			<div class="container">
				<div class="row animate-box">
					<div class="col-md-8 col-md-offset-2 text-center heading-section">
						<h3>Ласкаво просимо</h3>
						<p>
Кожне наше весілля сьогодні - це окремий авторський проект, спеціально створений для двох конкретних людей. І ми не шкодуємо ані сил, ані часу, щоб день весілля назавжди запам'ятався як один з найкращих днів у житті.					</div>
				</div>
				<div class="row">
					<div class="col-md-7 animate-box">
						<div class="fh5co-cover" style="background-image: url(images/im9.jpg);">
							<div class="desc">
								<p>Відгуки</p>
							</div>
						</div>
					</div>
					<div class="col-md-3">
						<div class="fh5co-cover">
							
								<div class="fh5co-cover-hero animate-box">
									<div class="fh5co-cover-thumb" style="background-image: url(images/im16.jpg);"></div>
									<div class="desc-thumb">
										<p>Портфоліо</p>
									</div>
								</div>

								<div class="fh5co-cover-hero animate-box">
								<div class="fh5co-cover-thumb" style="background-image: url(images/im15.jpg);"></div>
								<div class="desc-thumb">
									<p>Пропозиції</p>
									</div>
								</div>

								<div class="fh5co-cover-hero animate-box">
								<div class="fh5co-cover-thumb" style="background-image: url(images/im13.jpg);"></div>
								<div class="desc-thumb">
									<p>Про нас</p>
									</div>
								</div>

								</div>
							</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- END fh5co-media-section -->
		<div id="fh5co-intro-section">
			<div class="fh5co-intro-cover text-center animate-box" data-animate-effect="fadeIn" data-stellar-background-ratio="1" style="background-image: url(images/im5.jpg);">
				<a href="#" class="btn">Організація весілля - це відповідальне і тонка справа.</br>
										Наречена в цей день хоче бути найкрасивішою в світі, </br>
										наречений відчуває величезну відповідальність, і разом </br>
										вони вірять, що це - найважливіший крок до величезного</br>
										сімейного щастя. Додайте сюди хвилювання батьків, які </br>
										чекали на цю подію все життя і Ви зрозумієте, що саме</br>
										від весільного організатора залежить наскільки легким </br>
										і виключно красивим буде весільний день.</a>
			</div>
		</div>
		<!-- END fh5co-intro-section -->
		<div id="fh5co-product-section">
			<div class="container">
				<div class="row">
					<div class="col-md-8 col-md-offset-2 text-center heading-section animate-box">
						<h3>Наші весілля</h3>
					</div>
				</div>
				<div class="owl-carousel owl-carousel2">
					<div class="item animate-box"><a href="images/im1.jpg" class="image-popup"><img src="images/im1.jpg" alt="image"></a></div>
					<div class="item animate-box"><a href="images/im2.jpg" class="image-popup"><img src="images/im2.jpg" alt="image"></a></div>
					<div class="item animate-box"><a href="images/im4.jpg" class="image-popup"><img src="images/im4.jpg" alt="image"></a></div>
					<div class="item animate-box"><a href="images/im11.jpg" class="image-popup"><img src="images/im11.jpg" alt="image"></a></div>
					<div class="item animate-box"><a href="images/im12.jpg" class="image-popup"><img src="images/im12.jpg" alt="image"></a></div>
				</div>
			</div>
		</div>
		<!-- END fh5co-product-section -->
		<div id="fh5co-section" class="fh5co-grey-section">
			<div class="container">
				<div class="row">
					<div class="col-md-3 animate-box text-center">
						<div class="fh5co-inner">
							<div class="holder-section">
								<h3>150</h3>
								<p>реалізованих проектів </p>
							</div>
						</div>
					</div>
					<div class="col-md-4 animate-box text-center">
						<div class="fh5co-inner">
							<div class="holder-section">
								<h3>252</h3>
								<p>романтичних мість для весілля </p>
							</div>
						</div>
					</div>
					<div class="col-md-4 animate-box text-center">
						<div class="fh5co-inner">
							<div class="holder-section">
								<h3>2 тижня</h3>
								<p>мінімальний час організації весілля </p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<footer>
			<div id="footer">
				<div class="container">
					<div class="row">
						<div class="col-md-6 col-md-offset-3 text-center">

							<p><a href="#"></a>BON-BON <i class="icon-heart"></i></p>
						</div>
					</div>
				</div>
			</div>
		</footer>
	</div>

	<script src="js/jquery.min.js"></script>
	<script src="js/jquery.easing.1.3.js"></script>
	<script src="js/bootstrap.min.js"></script>
		<script src="js/owl.carousel.min.js"></script>
	<script src="js/jquery.waypoints.min.js"></script>
	<script src="js/jquery.stellar.min.js"></script>
	<script src="js/main.js"></script>

	</body>
</html>
