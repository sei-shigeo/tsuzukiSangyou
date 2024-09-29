<script>
	import Header from '$lib/components/Header.svelte';
	import MainVisual from '$lib/components/MainVisual.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import '../app.css';
</script>

<div class="layout">
	<header>
		<Header />
	</header>
	<main>
		<MainVisual />
		<slot />
	</main>
	<footer>
		<Footer />
	</footer>
</div>

<style>
	.layout {
		display: grid;
		grid-template-rows: auto 1fr auto;
		grid-template-areas: 'h' 'm' 'f';
	}
	header {
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		z-index: 100;
		grid-area: h;
		background-color: var(--white);
		box-shadow: 0 10px 10px rgba(0, 0, 0, 0.5);
	}
	main {
		grid-area: m;
	}
	footer {
		grid-area: f;
	}
</style>
