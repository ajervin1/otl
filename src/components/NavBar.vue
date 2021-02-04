<template>
	<nav class="navbar navbar-expand-lg navbar-light bg-light py-5 align-items-center">
		<a class="navbar-brand" href="#">
			<img width="200px" src="https://ld-wp73.template-help.com/wordpress/prod_5718/v2/wp-content/uploads/2019/10/Retina_Logo1.png" class="">
		</a>
		<button class="navbar-toggler" type="button" data-toggle="collapse"
		        data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
		        aria-expanded="false" aria-label="Toggle navigation">
			<span class="navbar-toggler-icon"></span>
		</button>
		
		<div class="collapse navbar-collapse" id="navbarSupportedContent">
			<ul class="navbar-nav ml-auto">
				
				<li class="nav-item">
					<a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
				</li>
				
				<li class="nav-item">
					<a class="nav-link" href="#">About <span class="sr-only">(current)</span></a>
				</li>
				
				<li class="nav-item mr-4">
					<a class="nav-link" href="#">Blog</a>
				</li>
				
				<li class="nav-item">
					<button class="btn btn-primary">Request An Appointment</button>
				</li>
			</ul>
		
		</div>
	</nav>
</template>

<script>
	export default {
		name: 'NavBar',
		
	}
</script>
