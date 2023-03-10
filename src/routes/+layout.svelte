<script>
	import '$lib/styles/app.css';
</script>

<main>
	<slot />
</main>

<style>
	main {
		display: flex;
		flex-direction: column;
		align-items: center;
		max-width: 1280px;
		margin: 0 auto;
	}
</style>
