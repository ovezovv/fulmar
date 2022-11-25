<script>
	import Header from '../lib/components/Header.svelte';
	import Slider from '../lib/components/Slider.svelte';
	import ContactUs from '../lib/components/ContactUs.svelte';
	import AboutUs from '../lib/components/AboutUs.svelte';
</script>

<body id="section_1">
	<Header />

	<main>
		<Slider />
		<section class="section-padding">
			<div class="container">
				<div class="row">
					<div class="col-lg-10 col-12 text-center mx-auto">
						<h2 class="mb-5">Welcome to Fulmar International</h2>
					</div>

					<div class="col-lg-3 col-md-6 col-12 mb-4 mb-lg-0">
						<div class="featured-block d-flex justify-content-center align-items-center">
							<a href="donate.html" class="d-block">
								<img src="images/icons/hands.png" class="featured-block-image img-fluid" alt="" />

								<p class="featured-block-text">Become a <strong>volunteer</strong></p>
							</a>
						</div>
					</div>

					<div class="col-lg-3 col-md-6 col-12 mb-4 mb-lg-0 mb-md-4">
						<div class="featured-block d-flex justify-content-center align-items-center">
							<a href="donate.html" class="d-block">
								<img src="images/icons/heart.png" class="featured-block-image img-fluid" alt="" />

								<p class="featured-block-text"><strong>Caring</strong> Earth</p>
							</a>
						</div>
					</div>

					<div class="col-lg-3 col-md-6 col-12 mb-4 mb-lg-0 mb-md-4">
						<div class="featured-block d-flex justify-content-center align-items-center">
							<a href="donate.html" class="d-block">
								<img src="images/icons/receive.png" class="featured-block-image img-fluid" alt="" />

								<p class="featured-block-text">Make a <strong>Donation</strong></p>
							</a>
						</div>
					</div>

					<div class="col-lg-3 col-md-6 col-12 mb-4 mb-lg-0">
						<div class="featured-block d-flex justify-content-center align-items-center">
							<a href="donate.html" class="d-block">
								<img
									src="images/icons/scholarship.png"
									class="featured-block-image img-fluid"
									alt=""
								/>

								<p class="featured-block-text"><strong>Scholarship</strong> Program</p>
							</a>
						</div>
					</div>
				</div>
			</div>
		</section>

		<AboutUs />

		<!-- <section class="about-section section-padding">
			<div class="container">
				<div class="row">
					<div class="col-lg-6 col-md-5 col-12">
						<img
							src="images/portrait-volunteer-who-organized-donations-charity.jpg"
							class="about-image ms-lg-auto bg-light shadow-lg img-fluid"
							alt=""
						/>
					</div>

					<div class="col-lg-5 col-md-7 col-12">
						<div class="custom-text-block">
							<h2 class="mb-0">Sandy Chan</h2>

							<p class="text-muted mb-lg-4 mb-md-4">Founding Partner</p>

							<p>
								Lorem Ipsum dolor sit amet, consectetur adipsicing kengan omeg kohm tokito
								Professional charity theme based
							</p>

							<p>Sed leo nisl, posuere at molestie ac, suscipit auctor mauris. Etiam quis metus</p>

							<ul class="social-icon mt-4">
								<li class="social-icon-item">
									<a href="#" class="social-icon-link bi-twitter" />
								</li>

								<li class="social-icon-item">
									<a href="#" class="social-icon-link bi-facebook" />
								</li>

								<li class="social-icon-item">
									<a href="#" class="social-icon-link bi-instagram" />
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</section> -->

		<section class="cta-section section-padding">
			<div class="container">
				<div class="row justify-content-center align-items-center">
					<div class="col-lg-5 col-12 ms-auto">
						<h2 class="mb-0">Make an impact. <br /> Save lives.</h2>
					</div>

					<div class="col-lg-5 col-12">
						<a href="#" class="me-4">Make a donation</a>

						<a href="#section_4" class="custom-btn btn smoothscroll">Become a volunteer</a>
					</div>
				</div>
			</div>
		</section>

		<section class="section-padding section-bg" id="section_3">
			<div class="container">
				<div class="row">
					<div class="col-lg-12 col-12 text-center mb-4">
						<h2>Our Services</h2>
					</div>

					<div class="col-lg-4 col-md-6 col-12 mb-4 mb-lg-0">
						<div class="custom-block-wrap">
							<img
								src="images/causes/group-african-kids-paying-attention-class.jpg"
								class="custom-block-image img-fluid"
								alt=""
							/>

							<div class="custom-block">
								<div class="custom-block-body">
									<h5 class="mb-3">Children Education</h5>

									<p>Lorem Ipsum dolor sit amet, consectetur adipsicing kengan omeg kohm tokito</p>
								</div>

								<a href="donate.html" class="custom-btn btn">Read more...</a>
							</div>
						</div>
					</div>

					<div class="col-lg-4 col-md-6 col-12 mb-4 mb-lg-0">
						<div class="custom-block-wrap">
							<img
								src="images/causes/poor-child-landfill-looks-forward-with-hope.jpg"
								class="custom-block-image img-fluid"
								alt=""
							/>

							<div class="custom-block">
								<div class="custom-block-body">
									<h5 class="mb-3">Poverty Development</h5>

									<p>
										Sed leo nisl, posuere at molestie ac, suscipit auctor mauris. Etiam quis metus
										tempor
									</p>
								</div>

								<a href="donate.html" class="custom-btn btn">Read more...</a>
							</div>
						</div>
					</div>

					<div class="col-lg-4 col-md-6 col-12">
						<div class="custom-block-wrap">
							<img
								src="images/causes/african-woman-pouring-water-recipient-outdoors.jpg"
								class="custom-block-image img-fluid"
								alt=""
							/>

							<div class="custom-block">
								<div class="custom-block-body">
									<h5 class="mb-3">Supply drinking water</h5>

									<p>
										Orci varius natoque penatibus et magnis dis parturient montes, nascetur
										ridiculus
									</p>
								</div>

								<a href="donate.html" class="custom-btn btn">Read more...</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>

		<!-- <section class="volunteer-section section-padding" id="section_4">
			<div class="container">
				<div class="row">
					<div class="col-lg-6 col-12">
						<h2 class="text-white mb-4">Volunteer</h2>

						<form
							class="custom-form volunteer-form mb-5 mb-lg-0"
							action="#"
							method="post"
							role="form"
						>
							<h3 class="mb-4">Become a volunteer today</h3>

							<div class="row">
								<div class="col-lg-6 col-12">
									<input
										type="text"
										name="volunteer-name"
										id="volunteer-name"
										class="form-control"
										placeholder="Jack Doe"
										required
									/>
								</div>

								<div class="col-lg-6 col-12">
									<input
										type="email"
										name="volunteer-email"
										id="volunteer-email"
										pattern="[^ @]*@[^ @]*"
										class="form-control"
										placeholder="Jackdoe@gmail.com"
										required
									/>
								</div>

								<div class="col-lg-6 col-12">
									<input
										type="text"
										name="volunteer-subject"
										id="volunteer-subject"
										class="form-control"
										placeholder="Subject"
										required
									/>
								</div>

								<div class="col-lg-6 col-12">
									<div class="input-group input-group-file">
										<input type="file" class="form-control" id="inputGroupFile02" />

										<label class="input-group-text" for="inputGroupFile02">Upload your CV</label>

										<i class="bi-cloud-arrow-up ms-auto" />
									</div>
								</div>
							</div>

							<textarea
								name="volunteer-message"
								rows="3"
								class="form-control"
								id="volunteer-message"
								placeholder="Comment (Optional)"
							/>

							<button type="submit" class="form-control">Submit</button>
						</form>
					</div>

					<div class="col-lg-6 col-12">
						<img
							src="images/smiling-casual-woman-dressed-volunteer-t-shirt-with-badge.jpg"
							class="volunteer-image img-fluid"
							alt=""
						/>

						<div class="custom-block-body text-center">
							<h4 class="text-white mt-lg-3 mb-lg-3">About Volunteering</h4>

							<p class="text-white">
								Lorem Ipsum dolor sit amet, consectetur adipsicing kengan omeg kohm tokito
								Professional charity theme based
							</p>
						</div>
					</div>
				</div>
			</div>
		</section> -->

		<section class="testimonial-section section-padding section-bg">
			<div class="container">
				<div class="row">
					<div class="col-lg-8 col-12 mx-auto">
						<h2 class="mb-lg-3">Happy customers</h2>

						<div
							id="testimonial-carousel"
							class="carousel carousel-fade slide"
							data-bs-ride="carousel"
						>
							<div class="carousel-inner">
								<div class="carousel-item active">
									<div class="carousel-caption">
										<h4 class="carousel-title">
											Lorem Ipsum dolor sit amet, consectetur adipsicing kengan omeg kohm tokito
											charity theme
										</h4>

										<small class="carousel-name"
											><span class="carousel-name-title">Maria</span>, Boss</small
										>
									</div>
								</div>

								<div class="carousel-item">
									<div class="carousel-caption">
										<h4 class="carousel-title">
											Sed leo nisl, posuere at molestie ac, suscipit auctor mauris quis metus tempor
											orci
										</h4>

										<small class="carousel-name"
											><span class="carousel-name-title">Thomas</span>, Partner</small
										>
									</div>
								</div>

								<div class="carousel-item">
									<div class="carousel-caption">
										<h4 class="carousel-title">
											Lorem Ipsum dolor sit amet, consectetur adipsicing kengan omeg kohm tokito
											charity theme
										</h4>

										<small class="carousel-name"
											><span class="carousel-name-title">Jane</span>, Advisor</small
										>
									</div>
								</div>

								<div class="carousel-item">
									<div class="carousel-caption">
										<h4 class="carousel-title">
											Sed leo nisl, posuere at molestie ac, suscipit auctor mauris quis metus tempor
											orci
										</h4>

										<small class="carousel-name"
											><span class="carousel-name-title">Bob</span>, Entreprenuer</small
										>
									</div>
								</div>

								<ol class="carousel-indicators">
									<li data-bs-target="#testimonial-carousel" data-bs-slide-to="0" class="active">
										<img
											src="images/avatar/portrait-beautiful-young-woman-standing-grey-wall.jpg"
											class="img-fluid rounded-circle avatar-image"
											alt="avatar"
										/>
									</li>

									<li data-bs-target="#testimonial-carousel" data-bs-slide-to="1" class="">
										<img
											src="images/avatar/portrait-young-redhead-bearded-male.jpg"
											class="img-fluid rounded-circle avatar-image"
											alt="avatar"
										/>
									</li>

									<li data-bs-target="#testimonial-carousel" data-bs-slide-to="2" class="">
										<img
											src="images/avatar/pretty-blonde-woman-wearing-white-t-shirt.jpg"
											class="img-fluid rounded-circle avatar-image"
											alt="avatar"
										/>
									</li>

									<li data-bs-target="#testimonial-carousel" data-bs-slide-to="3" class="">
										<img
											src="images/avatar/studio-portrait-emotional-happy-funny.jpg"
											class="img-fluid rounded-circle avatar-image"
											alt="avatar"
										/>
									</li>
								</ol>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>

		<ContactUs />
	</main>

	<footer class="site-footer">
		<div class="container">
			<div class="row">
				<div class="col-lg-3 col-12 mb-4">
					<img src="images/logo.png" class="logo img-fluid" alt="" />
				</div>

				<div class="col-lg-4 col-md-6 col-12 mb-4">
					<h5 class="site-footer-title mb-3">Quick Links</h5>

					<ul class="footer-menu">
						<li class="footer-menu-item"><a href="#" class="footer-menu-link">Our Story</a></li>

						<li class="footer-menu-item"><a href="#" class="footer-menu-link">Newsroom</a></li>

						<li class="footer-menu-item"><a href="#" class="footer-menu-link">Causes</a></li>

						<li class="footer-menu-item">
							<a href="#" class="footer-menu-link">Become a volunteer</a>
						</li>

						<li class="footer-menu-item">
							<a href="#" class="footer-menu-link">Partner with us</a>
						</li>
					</ul>
				</div>

				<div class="col-lg-4 col-md-6 col-12 mx-auto">
					<h5 class="site-footer-title mb-3">Contact Infomation</h5>

					<p class="text-white d-flex mb-2">
						<i class="bi-telephone me-2" />

						<a href="tel: 305-240-9671" class="site-footer-link"> 305-240-9671 </a>
					</p>

					<p class="text-white d-flex">
						<i class="bi-envelope me-2" />

						<a href="mailto:info@yourgmail.com" class="site-footer-link"> donate@charity.org </a>
					</p>

					<p class="text-white d-flex mt-3">
						<i class="bi-geo-alt me-2" />
						1006 N Plum Grove Rd Unit 107 SCHAUMBURG IL 60173
					</p>

					<a href="#" class="custom-btn btn mt-3">Get Direction</a>
				</div>
			</div>
		</div>

		<div class="site-footer-bottom">
			<div class="container">
				<div class="row">
					<div class="col-lg-6 col-md-7 col-12">
						<p class="copyright-text mb-0">
							Copyright © {new Date().getFullYear()} <a href="#">Fulmar International</a>
						</p>
					</div>

					<div
						class="col-lg-6 col-md-5 col-12 d-flex justify-content-center align-items-center mx-auto"
					>
						<ul class="social-icon">
							<li class="social-icon-item">
								<a href="#" class="social-icon-link bi-twitter" />
							</li>
							<li class="social-icon-item">
								<a href="#" class="social-icon-link bi-instagram" />
							</li>
							<li class="social-icon-item">
								<a href="#" class="social-icon-link bi-linkedin" />
							</li>
						</ul>
					</div>
				</div>
			</div>
		</div>
	</footer>
</body>
