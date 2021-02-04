<template>
	<section id="hero" class="hero mt-9 bg-primary hero-image jarallax"  data-jarallax data-speed="0.1">
		<div class="overlay"></div>
		
		<div class="container">
			<div class="row justify-content-center">
				<div class="col-12 col-md-10 text-center">
					<article class="hero-content animate__animated animate__fadeInLeft">
						<h1 class="display-2 text-white">Find Your Space</h1>
						<p class="lead text-white-50">12,000+ coworking spaces with desks, offices &
							meeting rooms in 165+ countries. Discover and reserve space today.</p>
						<button class="btn btn-secondary btn-lg">
							<i class="fa fa-book"></i>
							Read More</button>
					</article>
				
				</div>
			</div>
		</div>
	
	</section>
</template>

<script>
	
	
	
	export default {
		name: 'Hero',
		data () {
			return {}
		},
	}
</script>
<style lang="scss">
	.hero {
		padding-top: 15rem;
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
