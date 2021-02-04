<template>
	<section class="welcome py-10 bd-gray-100">
		<div class="container">
			<div class="row justify-content-center mb-4">
				<div class="col-md-8 text-center " >
					<div class="aos-init aos-animate" data-aos="fade-up">
						<h2>Welcome</h2>
						<p >
							
							When one of our founders, Peter Stevenson was choosing between a regular
							medical career and a work path of the practicing physiotherapist, he
							based his choice on what he loved doing the most.
						</p>
					</div>
			
				</div>
			</div>
			<div class="row">
				<div class="col-md-4 mb-4 mb-md-0" v-for="x in 3">
					<article class="border aos-init aos-animate p-4 text-center" data-aos="fade-up">
						<img  src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/img4-1-1.png"
						     >
						<h4 class="my-3">Therapies Spectrum</h4>
						<p>
							While we’re definitely not the biggest practice in the US, we have
							the widest range of physiotherapy services, as opposed to our
							competitors!
						</p>
					</article>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
	export default {
		name: 'Welcome',
		data () {
			return {
				animate: 'animate__animated animate__fadeIn',
				animate2: 'animate__animated animate__fadeInLeft'
			}
		}
	}
</script>
