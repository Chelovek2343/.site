<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<link rel="stylesheet" href="assets/css/style.css">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Mulish:wght@300;400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
	<title>Travel</title>
</head>
<body>

	<!-- Header -->
	<header class="header">
		<div class="container-fluid">
			<!-- Nav -->
			<nav class="navbar navbar-expand-lg navbar-primary|secondary|success|danger|warning|info|light|dark bg-primary|secondary|success|danger|warning|info|light|dark">
			 <a class="navbar-brand" href="#">
			  	<img src="assets/img/Header/header_logo.png" alt="">
			 </a>
			  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
			    <span class="navbar-toggler-icon"></span>
			  </button>
			
			  <div class="collapse navbar-collapse" id="navbarSupportedContent">
			    <ul class="navbar-nav ml-auto">
			      <li class="nav-item active">
			        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
			      </li>
			      <li class="nav-item">
			        <a class="nav-link" href="#">Destinations</a>
			      </li>

			      <li class="nav-item">
			        <a class="nav-link" href="#">About</a>
			      </li>
			      <li class="nav-item dropdown">
			        <a class="nav-link" href="#">
			          Partner
			        </a>
			      </li>
			    </ul>
			    <button class="btn_log">Login</button>
			    <button class="btn_reg">Register</button>
			  </div>
			</nav>

			<!-- Header_cont -->
				<div class="header_title">
					Explore and <br> Travel
				</div>

				<p>Holiday finder</p>

				<!-- Form 1 -->
				<form action="URL">
					<div class="row">
						<!-- Location -->
						<div class="col-md-3">
							<select name="#" id="#">
								<option value="">
									Location
								</option>

							</select>
						</div>

						<!-- Activity -->
						<div class="col-md-4">
							<select name="#" id="activity">
								<option value="">
									Activity
								</option>

							</select>
						</div>
					</div>
				</form>

				<!-- Form 2 -->
				<form action="">
					<div class="row">
						<!-- Location -->
						<div class="col-md-3">
							<select name="#" id="#">
								<option value="">
									Grade
								</option>

							</select>
						</div>

						<!-- Activity -->
						<div class="col-md-3">
							<select name="#" id="activity">
								<option value="">
									Date
								</option>

							</select>
						</div>
					</div>	
				</form>

				<button class="btn_log btn_log--btn_exp">
					Explore
				</button>

				<img src="assets/img/Header/header_img.png" class="header_img img-fluid" alt="">
		</div>

	</header>

	<!-- Way -->
	<section class="way">
		<div class="container">
			<div class="row">
				<div class="col-md-7">
					<img src="assets/img/Way/way_img.png" alt="">
				</div>

				<div class="col-md-5">
					<h1 class="way_title">
						A new way to explore the world 
					</h1>

					<p class="way_text">
						For decades travellers have reached for Lonely Planet books when looking to plan and execute their perfect <br> 	
						trip, but now, they can also let Lonely Planet Experiences lead the way
					</p>

					<button class="btn_log btn_log--btn_way">Learn More</button>
			</div>
				</div>
			</div>
		</div>
	</section>

	<!-- Landscape -->
	<section class="landscape">
		<div class="container">
			<div class="row">
				<div class="col-md-5">
					<h1 class="way_title">
						Featured destinations
					</h1>
				</div>


				<a href="#" class="land_btn ml-auto">View all</a>
					<a class="land_btn" href="#">
						<i class="fas fa-arrow-right"></i>
					</a>
			</div>

			<!-- Img -->
			<div class="row">
				<div class="col-md-3">
					<img src="assets/img/Landscape/landsc_raja.png" alt="">
					<p>Raja Ampat <br> <span class="colortext">Indonesia</span></p>
				</div>

				<div class="col-md-3">
					<img src="assets/img/Landscape/landsc_fanji.png" alt="">
					<p>Fanjingshan <br> <span class="colortext">China</span></p>
				</div>

				<div class="col-md-3">
					<img src="assets/img/Landscape/landsc_vevey.png" alt="">
					<p>Vevey <br> <span class="colortext">Switzerland</span></p>
				</div>

				<div class="col-md-3">
					<img src="assets/img/Landscape/landsc_skadar.png" alt="">
					<p>Skadar <br> <span class="colortext">Montenegro</span></p>
				</div>
			</div>
		</div>
	</section>

	<section class="guides">
		<div class="container">
			<div class="row">
				<div class="col-md-5">
					<h1 class="way_title">
						Guides by Thousand Sunny
					</h1>

					<p class="way_text">
						Packed with tips and advice from our on-the-ground experts, our city guides app (iOS and Android) is the ultimate resource before and during a trip.
					</p>

					<button class="btn_log btn_log--btn_way">Download</button>
				</div>
			</div>

			<img src="assets/img/Guides/guides_img.png" alt="" class="img-fluid">
		</div>
	</section>

	<!-- Testimonials -->
	<section class="testimonials">
		<div class="container">
			<h1 class="way_title">
				Testimonials
			</h1>

			<!-- Stars -->
			<div class="row">
				<div class="col-md-2">
					<img src="assets/img/Testimonials/test_stars.png" class="test_stars img-fluid" alt="">
				</div>
			</div>

			<!-- Testimonials_text -->
			<div class="row">
				<div class="col-md-5">
					<p class="test_text">“Quisque in lacus a urna fermentum euismod. Integer mi nibh, dapibus ac scelerisque eu, facilisis quis purus. Morbi blandit sit amet turpis nec”</p>
				</div>
			</div>

			<!-- Testimonials_name -->
			<div class="row">
				<div class="col-md-3">
					<p class="test_name">
						Edward Newgate
					</p>
				</div>
			</div>

			<!-- Testimonials_prof -->
			<div class="row">
				<div class="col-md-2">
					<p class="test_prof">
						Founder Circle
					</p>
				</div>
			</div>

			<div class="row">
				<div class="col-md-4 ml-auto">
					<img src="assets/img/Testimonials/test_img.png" class="test_person" alt="">
				</div>

				<a href="#">
					<i class="fas fa-chevron-circle-left"></i>
				</a>
				
				<a href="#">
					<i class="fas fa-chevron-circle-right"></i>
				</a>
			</div>
		</div>
	</section>

	<!-- Trend -->
	<section class="trend">
		<div class="container">
			<div class="row">
				<div class="col-md-5">
					<h1 class="way_title">
						 Trending stories
					</h1>
				</div>


				<a  href="#" class="land_btn ml-auto">View all</a>
					<a class="land_btn" href="#">
						<i class="fas fa-arrow-right"></i>
					</a>
			</div>

			<div class="row">
				<div class="col-md-3">
					<img src="assets/img/Trend/trend_img.png" alt="">
					<h5> The many benefits of taking a healing holiday</h5>
					<p>‘Helaing holidays’ are on the rise tohelp maximise your health and happines...</p>
					<a href="#">Read more</a>
				</div>

				<div class="col-md-3">
					<img src="assets/img/Trend/trend_img_2.png" alt="">
					<h5> The best Kyoto restaurant to try Japanese food</h5>
					<p>From tofu to teahouses, here’s our guide to Kyoto’s best restaurants to visit...</p>
					<a href="#">Read more</a>
				</div>

				<div class="col-md-3">
					<img src="assets/img/Trend/trend-img_3.png" alt="">
					<h5>Skip Chichen Itza and head to this remote Yucatan</h5>
					<p>It’s remote and challenging to get,but braving the jungle and exploring these ruins without the...</p>
					<a href="#">Read more</a>
				</div>

				<div class="col-md-3">
					<img src="assets/img/Trend/trend-img_4.png" alt="">
					<h5>Surf’s up at these beginner spots around the world</h5>
					<p>If learning to surf has in on your to-do list for a while, the good news is: it’s never too late...</p>
					<a href="#">Read more</a>
				</div>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer class="footer">
			<img src="assets/img/Header/header_logo.png" alt="">
			<p class="footer_text">Plan and book your perfect trip with <br> expert advice, travel tips destination <br> information from us</p>
			<p class="footer_rights">©2020 Thousand Sunny. All rights reserved</p>

		<div class="container">
			<!-- Footer_col 1 -->
			<p class="footer_col">Destinations</p>

			<p class="footer_col_inner">Africa</p>

			<p class="footer_col_inner">Antarctica</p>

			<p class="footer_col_inner">Asia</p>

			<p class="footer_col_inner">Europe</p>

			<p class="footer_col_inner">America</p>

			<!-- Footer_col 2 -->
			<p class="footer_col footer_col--shop">Shop</p>

			<p class="footer_col_inner footer_col--items"> Destination Guides</p>

			<p class="footer_col_inner footer_col--items">Pictorial & Gifts</p>

			<p class="footer_col_inner footer_col--items">Special Offers</p>

			<p class="footer_col_inner footer_col--items">Delivery Times</p>

			<p class="footer_col_inner footer_col--items">FAQs</p>

			<!-- Footer_col 3 -->
			<p class="footer_col footer_col--interests">Interests</p>

			<p class="footer_col_inner footer_col--item">Adventure Travel</p>

			<p class="footer_col_inner footer_col--item">And Culture</p>

			<p class="footer_col_inner footer_col--item">Wildlife And Nature</p>

			<p class="footer_col_inner footer_col--item">Family Holidays</p>

			<p class="footer_col_inner footer_col--item">Food And Drink</p>

			<hr>

			<a href="#">
				<i class="fab fa-twitter"></i>
			</a>

			<a href="#">
				<i class="fab fa-facebook-f"></i>
			</a>

			<a href="#">
				<i class="fab fa-instagram"></i>
			</a>

			<a href="#">
				<i class="fab fa-linkedin-in"></i>
			</a>

			<a href="#">
				<i class="fab fa-youtube"></i>
			</a>
		</div>
	</footer>

	<!-- Jqery -->
	<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha256-4+XzXVhsDmqanXGHaHvgh1gMQKX40OUvDEBTu8JcmNs=" crossorigin="anonymous"></script>
	<!-- Bootstrap -->
	<script src="https://code achievements
	jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
	<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
</body>
</html>
