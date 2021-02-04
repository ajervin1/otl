<template>
	<section class=" py-7">
		<h2 class="text-center mb-5">Recent Blog Entries</h2>
		<div class="row">
			<div class="col-4" v-for="x in 3">
				<article class="card">
					<img src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/img19-1170x780-1170x650.jpg"
					     class="card-img-top">
					<div class="card-body">
						<h4>Chronic Muscle Pains</h4>
						<p>
							Choosing a fitting website template is probably the most responsible
							e-business task of them all… But cheer up, as we’ve prepared a lot
							of useful tips on...
						</p>
					</div>
				</article>
			</div>
		</div>
	</section>
</template>

<script>
	export default {
		name: 'BlogEntries',
		data () {
			return {}
		}
	}
</script>
