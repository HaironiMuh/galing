<script>
	import Nav from '../components/Nav.svelte';
	import Banner from '../components/Banner.svelte';
	import Promo from '../components/Promo.svelte';
	import Makanan from '../components/Makanan.svelte';
	import Lirik from '../components/Lirik.svelte';
	import Instagram from '../components/Instagram.svelte';

	// export let segment;
</script>

<style>
	main {
		position: relative;
		max-width: 56em;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
	}

	.container{
		background-color:red;
		height: 500px;
		width: 100%;
	}
</style>

<Nav />
<Banner />
<Promo />
<Makanan />
<Lirik />
<Makanan />
<Instagram />

<!-- <main>
	<slot></slot>
</main> -->