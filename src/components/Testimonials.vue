<template>
	<section class="container py-7 mt-6">
		<h2 class="text-center mb-6">Testimonials</h2>
		<div class="row">
			<div class="col-4" v-for="x in 3">
				<article class="text-center">
					<img width="50px"
					     src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/testimonials-1.png">
					<h4 class="mb-4">Ryan Banies</h4>
					<p>
						Lorem ipsum dolor sit amet, consectetur adipisicing elit. Debitis,
						natus!
					</p>
				</article>
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
