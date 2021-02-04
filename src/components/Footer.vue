<template>
	<footer class="bg-dark py-5 text-white">
		<div class="container">
			<div class="row aos-animate  text-small-center" data-aos="fade-up">
				<div class="col-md-3 mb-3 mb-md-0">
					<h2 class="text-white ">About Us</h2>
					<p>
						Every single day thousands of Americans suffer from all different kinds
						and
						types of pain. Starting with back pain, neck pain, muscle pains,
						migraines
						and many other once-off or chronic body pains – a quality physical
						therapy
						is a viable answer!
					</p>
				</div>
				<div class="col-md-3 mb-3 mb-md-0">
					<h2 class="text-white">Services</h2>
					<ul class="list-unstyled ">
						<li class="mb-2" v-for="x in 3">Sports Injurites</li>
					</ul>
				</div>
				<div class="col-md-3 mb-3 mb-md-0">
					<h2 class="text-white">Locations</h2>
					<ul class="list-unstyled">
						<li class="mb-2" v-for="x in 3">
							<i class="fa fa-home"></i>
							411 W Church St #200,
							Orlando, FL 32802
						</li>
					</ul>
				</div>
				<div class="col-md-3">
					<h2 class="text-white">Times</h2>
					<ul class="list-unstyled">
						<li class="mb-2 d-md-flex  align-items-center justify-content-between"
						    v-for="x in 3">
							<h6 class="text-white">Monday</h6>
							<div class="text-white-50">
								8:00 - 20:00
							</div>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</footer>
</template>

<script>
	export default {
		name: 'Footer',
		data () {
			return {}
		}
	}
</script>
<style>
	
	@media (max-width: 768px) {
		.text-small-center {
			text-align: center;
		}
	}
</style>
