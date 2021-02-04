<template>
	<section class="coupon py-10 bg-primary hero-image jarallax"  data-jarallax data-speed="0.1">
		<div class="overlay"></div>
		<div class="container">
			<div class="row justify-content-center">
				<div class="col-12 col-md-10 text-center">
					<article class="hero-content aos-animate" data-aos="fade-up">
						<h2 class="text-white display-2">Whether you are 20 years old or 70
							years old</h2>
						<p class="lead text-white-50">Acute, chronic or post-traumatic pain can
							get you
							anytime Physical Therapy is the tool for making your body and whole
							health improve and get back on track!</p>
						<button class="btn btn-secondary  btn-lg">
							<i class="fa fa-dollar-sign"></i>
							Print Coupon
						</button>
					</article>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
	
	
	
	
	export default {
		name: 'Coupon',
		
		data () {
			return {}
		},
	}
</script>
<style lang="scss">
	.coupon{
		padding-top: 10rem;
		padding-bottom: 10rem;
		position: relative;
	}
	
	.hero-image {
		background-image: url("https://demo.themesberg.com/bootstrap/spaces/assets/img/hero-1.jpg");
		background-repeat: no-repeat;
		background-position: top center;
		background-size: cover;
	}
	
	.overlay {
		position: absolute;
		content: "";
		background: #0d1b48;
		width: 100%;
		height: 100%;
		top: 0;
		left: 0;
		opacity: .8;
		z-index: 0;
	}
</style>
