<template>
	<footer class="bg-dark py-7">
		<div class="container text-white">
			<div class="row">
				<div class="col-3" v-for="x in 4">
					<h4 class="mb-4 text-white">About Us</h4>
					<p class="text-white-50">
						Every single day thousands of Americans suffer from all different kinds and
						types of pain. Starting with back pain, neck pain, muscle pains, migraines
						and many other once-off or chronic body pains – a quality physical therapy
						is a viable answer!
					</p>
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
