<template>
	<section class="blog py-15 bd-gray-200">
		<div class="container">
			<div class="row justify-content-center mb-4">
				<div class="col-md-8 text-center">
					<h2>Recent Blog Entries</h2>
				</div>
			</div>
			
			<div class="row">
				<div class="col-md-4 mb-4 mb-md-0 aos-animate" data-aos="fade-up" v-for="x in 3">
					<article class="card shadow">
						<img src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/img19-1170x780-1170x650.jpg"
						     class="card-img-top transition-zoom-hover">
						<div class="card-body">
							<h3 class="">Chronic Muscle Pains</h3>
							<div class="details mb-3">
								<span class="mr-1 text-primary ">admin </span>
								<span class="mr-1 text-primary ml-2">October 1, 2019 </span>
								<span class="text-primary ml-2">
								<i class="fa fa-comments"></i>
								2
							</span>
							</div>
							<p>
								Choosing a fitting website template is probably the most responsible
								e-business task of them all… But cheer up, as we’ve prepared a lot
								of useful tips on...
							</p>
							<button class="btn btn-primary btm-sm">View Blog</button>
						</div>
					
					</article>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
	export default {
		name: 'Blog',
		data () {
			return {}
		}
	}
</script>
