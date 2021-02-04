<template>
	<section class="categories py-15 bd-gray-100">
		<div class="container">
			<div class="top row justify-content-center mb-5">
				<div class="col-md-8 text-center">
					<h2 class="aos-animate" data-aos="fade-up">Types Of Therapies</h2>
				
				</div>
			</div>
			
			<!--Categories-->
			<div class="row">
				<div class="col-md-4 mb-4 mb-md-3" v-for="x in 3">
					<article class="card shadow aos-animate" data-aos="fade-up">
						<img src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/Depositphotos_69001363_original.jpg"
						     class="card-img-top transition-zoom-hover">
						<div class="card-footer bg-primary text-center">
							<h3 class="text-white">
								Chronic Pain
							</h3>
						</div>
					</article>
				</div>
			</div>
			<div class="text-md-center mt-4">
				<button class="btn btn-secondary btn-big btn-lg shadow">
					<i class="fa fa-cog"></i>
					View Services</button>
			</div>
	
		</div>
	</section>
</template>

<script>
	export default {
		name: 'Categories',
		data () {
			return {}
		}
	}
</script>
<style>
	@media (max-width: 768px) {
		.btn-big, .btn-group {
			width:100%;
		}
	}
</style>
