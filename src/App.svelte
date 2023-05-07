<script>
	import Header from "./components/Header.svelte";
	import Footer from "./components/Footer.svelte";
 	import Navigation from "./components/Navigation.svelte";
	import Index from "./components/Index.svelte";
	import Discounts from "./components/Discounts.svelte";


	
</script>

<main>
	<Header/>
	<Navigation/>
	
    
	<Index/>
	
	<!-- <Discounts/> -->
	<Footer/>
</main>

<style>
	main {
		/* padding: 1em; */
		margin: 0 auto;
	}

	/* h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	} */

	/* @media (min-width: 640px) {
		main {
			max-width: none;
		}
	} */

	
</style>