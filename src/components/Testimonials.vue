<template>
	<section class="testimonials py-20 position-relative hero-image jarallax" data-jarallax
	         data-speed="0.1">
		<div class="overlay"></div>
		<div class="container aos-animate" data-aos="fade-up">
			<div class="row justify-content-center mb-4">
				<div class="col-8 text-center">
					<h2 class="text-white">Testimonials</h2>
				</div>
			</div>
			<div class="row">
				<div class="col-md-4" v-for="x in 3">
					<article class=" p-4 text-center text-white">
						<img src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/testimonials-1.png"
						     class="transition-3d-hover">
						<h3 class="text-white">Anthony Ervin</h3>
						<p class="">
							I had been struggling with the various types and intensities of back
							pains for all of my adult life. Thank God one of my friends referred me
							here…
						</p>
					</article>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
	export default {
		name: 'Testimonials',
		data () {
			return {}
		}
	}
</script>
