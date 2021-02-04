<template>
	<div id="app" class="">
		<NavBar />
		<Hero />
		<Welcome />
		<Coupon />
		<Types />
		<Testimonials class="py-10" />
		<BlogEntries />
		<Footer />
	</div>
</template>

<script>
	
	
	import NavBar from './components/NavBar'
	import Hero from './components/Hero'
	import Welcome from './components/Welcome'
	import Coupon from './components/Coupon'
	import Types from './components/Types'
	import Testimonials from './components/Testimonials'
	import BlogEntries from './components/BlogEntries'
	import Footer from './components/Footer'
	
	export default {
		name: 'App',
		components: { Footer, BlogEntries, Testimonials, Types, Coupon, Welcome, Hero, NavBar },
	}
</script>

<style lang="scss">

</style>
