<script>
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
</script>

<Header />

<main>
	<slot />
</main>

<footer>
	<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
</footer>

<style>
	footer {
		max-width: 1520px;
		margin: 0 auto;
		padding-left: 15px;
		padding-right: 15px;
	}
</style>
