<script>
	import Footer from '../components/footer.svelte';
</script>

<!-- <header> -->
<!-- 	<div class="inner-header"> -->
<!-- 		<h1>dust dune</h1> -->
<!-- 		<div> -->
<!-- 			<button on:click={() => console.log('home')}>Home</button> -->
<!-- 			<button on:click={() => console.log('about')}>About us</button> -->
<!-- 			<button on:click={() => console.log('contact')}>Contact</button> -->
<!-- 		</div> -->
<!-- 	</div> -->
<!-- </header> -->

<main>
	<div class="header-space" />
	<h class="message">Vai dar td certo Mari, minha princesa 💖</h>
	<img
		src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExbjVsMmI2ZHFob3d5ZWJjaTQyZTBmcmtjbmUwM2Fkb25ydDF0cnpjbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/9G0AdBbVrkV3O/giphy.webp"
		alt="Vai dar td certo Mari, minha princesa 💖"
	/>
</main>

<Footer />

<style>
	:global(body) {
		color: #fff;
		margin: 0;
		padding: 0;
	}

	main {
		width: 100vw;
		min-height: 80vh;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}

	.message {
		font-size: 24px;
		color: #000;
	}

	header {
		position: fixed;
		display: flex;
		width: 100%;
		justify-content: center;
		align-items: center;
		background-color: #06162c;
	}

	.header-space {
		height: 100px;
	}

	.inner-header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		width: 100%;
		max-width: 1200px;
	}

	h1 {
		font-size: 42px;
		margin-left: 20px;
	}

	button {
		background-color: #06162c;
		color: #fff;
		border: none;
		outline: none;
		padding: 0px;
		margin: 20px;
		cursor: pointer;
		font-size: 16px;
	}

	button:hover {
		color: #64ffda;
	}
</style>
