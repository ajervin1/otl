<template>
	<section class="container py-5">
		<h2 class="text-center mb-6">Types Of Therapy</h2>
		<div class="row">
			<div class="col-4" v-for="x in 3">
				<article class="card">
					<img src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/Depositphotos_69001363_original.jpg"
					     class="card-img-top">
					<div class="card-footer text-center">
						<h3>Chronic Pains</h3>
					</div>
				</article>
			</div>
		</div>
		<div class="text-center mt-4">
			<button class="btn btn-primary">View All Services</button>
		</div>
	</section>
</template>

<script>
	export default {
		name: 'Types',
		data () {
			return {}
		}
	}
</script>
