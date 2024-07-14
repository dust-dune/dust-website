<script>
	import Footer from '../components/footer.svelte';
</script>

<main>
	<h class="message">In development</h>
</main>

<Footer />

<style>
	:global(body) {
		color: #fff;
		margin: 0;
		padding: 0;
	}

	:global(html) {
		font-size: 16px;
		font-family: 'Roboto', sans-serif;
	}

	main {
		width: 100%;
		min-height: 100vh;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}

	.message {
		font-size: 24px;
		color: #000;
	}
</style>
