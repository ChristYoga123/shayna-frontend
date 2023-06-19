<template>
	<div class="home">
		<!-- Header Section Begin -->
		<HeaderShayna />
		<!-- Header End -->
		<!-- Hero Section Begin -->
		<section class="hero-section">
			<carousel class="hero-items" :items="1" :nav="false" :dots="false" :autoplay="true">
				<div class="single-hero-items set-bg" style="background-image: url('/img/hero-1.jpg')">
					<div class="container">
						<div class="row">
							<div class="col-lg-5">
								<span>Bag,kids</span>
								<h1>Black friday</h1>
								<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore</p>
								<a href="#" class="primary-btn">Shop Now</a>
							</div>
						</div>
					</div>
				</div>
				<div class="single-hero-items set-bg" style="background-image: url('/img/hero-2.jpg')">
					<div class="container">
						<div class="row">
							<div class="col-lg-5">
								<span>Bag,kids</span>
								<h1>Black friday</h1>
								<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore</p>
								<a href="#" class="primary-btn">Shop Now</a>
							</div>
						</div>
					</div>
				</div>
			</carousel>
		</section>
		<!-- Hero Section End -->
		<!-- Women Banner Section Begin -->
		<section class="women-banner spad">
			<div class="container-fluid">
				<div class="row">
					<div class="col-lg-12 mt-5">
						<carousel class="product-slider" :nav="false" :items="3" :margin="20" :dots="false" :autoplay="true">
							<div class="product-item">
								<div class="pi-pic">
									<img src="img/mickey1.jpg" alt="" />
									<ul>
										<li class="w-icon active">
											<router-link to="/product"><i class="icon_bag_alt"></i></router-link>
										</li>
										<li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
									</ul>
								</div>
								<div class="pi-text">
									<div class="catagory-name">Coat</div>
									<router-link to="/product">
										<h5>Mickey Baggy</h5>
									</router-link>
									<div class="product-price">
										$14.00
										<span>$35.00</span>
									</div>
								</div>
							</div>
							<div class="product-item">
								<div class="pi-pic">
									<img src="img/products/women-2.jpg" alt="" />
									<ul>
										<li class="w-icon active">
											<a href="#"><i class="icon_bag_alt"></i></a>
										</li>
										<li class="quick-view"><a href="#">+ Quick View</a></li>
									</ul>
								</div>
								<div class="pi-text">
									<div class="catagory-name">Shoes</div>
									<a href="#">
										<h5>Guangzhou sweater</h5>
									</a>
									<div class="product-price">$13.00</div>
								</div>
							</div>
							<div class="product-item">
								<div class="pi-pic">
									<img src="img/products/women-3.jpg" alt="" />
									<ul>
										<li class="w-icon active">
											<a href="#"><i class="icon_bag_alt"></i></a>
										</li>
										<li class="quick-view"><a href="#">+ Quick View</a></li>
									</ul>
								</div>
								<div class="pi-text">
									<div class="catagory-name">Towel</div>
									<a href="#">
										<h5>Pure Pineapple</h5>
									</a>
									<div class="product-price">$34.00</div>
								</div>
							</div>
							<div class="product-item">
								<div class="pi-pic">
									<img src="img/products/women-4.jpg" alt="" />
									<ul>
										<li class="w-icon active">
											<a href="#"><i class="icon_bag_alt"></i></a>
										</li>
										<li class="quick-view"><a href="#">+ Quick View</a></li>
										<li class="w-icon">
											<a href="#"><i class="fa fa-random"></i></a>
										</li>
									</ul>
								</div>
								<div class="pi-text">
									<div class="catagory-name">Towel</div>
									<a href="#">
										<h5>Converse Shoes</h5>
									</a>
									<div class="product-price">$34.00</div>
								</div>
							</div>
						</carousel>
					</div>
				</div>
			</div>
		</section>
		<!-- Women Banner Section End -->
		<!-- Instagram Section Begin -->
		<div class="instagram-photo">
			<div class="insta-item set-bg" style="background-image: url('img/insta-1.jpg')">
				<div class="inside-text">
					<i class="ti-instagram"></i>
					<h5><a href="#">shayna_gallery</a></h5>
				</div>
			</div>
			<div class="insta-item set-bg" style="background-image: url('img/insta-2.jpg')">
				<div class="inside-text">
					<i class="ti-instagram"></i>
					<h5><a href="#">shayna_gallery</a></h5>
				</div>
			</div>
			<div class="insta-item set-bg" style="background-image: url('img/insta-3.jpg')">
				<div class="inside-text">
					<i class="ti-instagram"></i>
					<h5><a href="#">shayna_gallery</a></h5>
				</div>
			</div>
			<div class="insta-item set-bg" style="background-image: url('img/insta-4.jpg')">
				<div class="inside-text">
					<i class="ti-instagram"></i>
					<h5><a href="#">shayna_gallery</a></h5>
				</div>
			</div>
			<div class="insta-item set-bg" style="background-image: url('img/insta-5.jpg')">
				<div class="inside-text">
					<i class="ti-instagram"></i>
					<h5><a href="#">shayna_gallery</a></h5>
				</div>
			</div>
			<div class="insta-item set-bg" style="background-image: url('img/insta-6.jpg')">
				<div class="inside-text">
					<i class="ti-instagram"></i>
					<h5><a href="#">shayna_gallery</a></h5>
				</div>
			</div>
		</div>
		<!-- Instagram Section End -->
		<!-- Partner Logo Section Begin -->
		<div class="partner-logo">
			<div class="container">
				<carousel class="logo-carousel" :nav="false" :items="5">
					<div class="logo-item">
						<div class="tablecell-inner">
							<img src="img/logo-carousel/logo-1.png" alt="" />
						</div>
					</div>
					<div class="logo-item">
						<div class="tablecell-inner">
							<img src="img/logo-carousel/logo-2.png" alt="" />
						</div>
					</div>
					<div class="logo-item">
						<div class="tablecell-inner">
							<img src="img/logo-carousel/logo-3.png" alt="" />
						</div>
					</div>
					<div class="logo-item">
						<div class="tablecell-inner">
							<img src="img/logo-carousel/logo-4.png" alt="" />
						</div>
					</div>
					<div class="logo-item">
						<div class="tablecell-inner">
							<img src="img/logo-carousel/logo-5.png" alt="" />
						</div>
					</div>
				</carousel>
			</div>
		</div>
		<!-- Partner Logo Section End -->
		<!-- Footer Section Begin -->
		<FooterShayna />
		<!-- Footer Section End -->
	</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderShayna from "@/components/HeaderShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";
import carousel from "vue-owl-carousel";
export default {
	name: "HomeView",
	components: {
		// HelloWorld,
		HeaderShayna,
		carousel,
		FooterShayna,
	},
};
</script>
