<template>
	<div>
		<NavBar />
		<Hero />
		<Welcome />
		<Coupon />
		<Categories />
		<Testimonials />
		<Blog />
		<Footer />
	</div>
</template>

<script>



	import Hero from './components/Hero'
	import NavBar from './components/NavBar'
	import Blog from './components/Blog'
	import Footer from './components/Footer'
	import Welcome from './components/Welcome'
	import Coupon from './components/Coupon'
	import Categories from './components/Categories'
	import Testimonials from './components/Testimonials'

	export default {
		name: 'App',
		components: { Testimonials, Categories, Coupon, Welcome, Footer, Blog, NavBar, Hero },
		data () {
			return {}
		},
	}
</script>
<style lang="scss">
	@import "node_modules/bootstrap/scss/bootstrap";
	.d {
		border: 2px #ff0000 solid;
	}
</style>
