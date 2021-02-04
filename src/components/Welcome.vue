<template>
	<section class="container">
		<div class="py-10 row justify-content-center">
			<div class="col-6 text-center">
				<h2 class="mb-5">Welcome To Out Site</h2>
				<p class="lead">
					When one of our founders, Peter Stevenson was choosing between a regular medical
					career and a work path of the practicing physiotherapist, he based his choice on
					what he loved doing the most.
				</p>
			</div>
		</div>
		<div class="row">
			<div class="col-4" v-for="x in 3">
				<article class="card text-center border">
					<div class="card-body">
						<img src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/img4-1-1.png"
						     class="mb-4">
						<h4>Therapies Spectrum</h4>
						<p>
							While we’re definitely not the biggest practice in the US, we have the
							widest range of physiotherapy services, as opposed to our competitors!
						</p>
					</div>
				</article>
			</div>
		</div>
	
	</section>

</template>

<script>
	export default {
		name: 'Welcome',
		data () {
			return {}
		}
	}
</script>
