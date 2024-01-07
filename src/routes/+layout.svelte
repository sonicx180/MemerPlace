<script>
	import './app.css';
	import Navbar from '../components/Navbar.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<svelte:head>
	<meta
		name="description"
		content="The place to find and share memes, for free!"
	/>
	<title>MemerPlace - Your place to find and share memes!</title>
</svelte:head>

<main>
	<Navbar />
	<slot />
	<Footer />
</main>

<style>
</style>
