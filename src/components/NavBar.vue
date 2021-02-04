<template>
	<nav class="navbar navbar-light navbar-expand-lg bg-white fixed-top py-4 px-4">
		<div class="logo">
			<img src="https://themesberg.com/docs/spaces/assets/brand/dark.svg" height="30px">
		</div>
		<button class="navbar-toggler" data-toggle="collapse" data-target="#navigation">
			<span class="navbar-toggler-icon"></span>
		</button>
		
		<div class="collapse navbar-collapse" id="navigation">
			<!--Nav Right-->
			<div class="ml-auto nav-right d-flex align-items-center">
				<nav class="navbar-nav d-flex">
					<a href="" class="nav-item nav-link" v-for="link in links">{{ link }}</a>
				
				</nav>
			
			</div>
			<div class="ml-md-4">
				<button class="btn btn-primary shadow">
					<i class="fa fa-phone"></i>
					Request An Appointment (651-208-4535)
				</button>
			</div>
		</div>
		
	
	</nav>
</template>

<script>
	export default {
		name: 'NavBar',
		data () {
			return {
				links: [ 'Home', 'About Us', 'Services', 'Blog', 'Contacts' ],
				
			}
		},
	}
</script>
