<main>
	<div class="fix-vertical">
		<div class="placeholderdiv">
			<div class="person">
				<img width="100%" src="images/logo.svg" alt="logo" />
			</div>
			<div class="textcontainer">
				<h1>Dust Dune</h1>
				<p>Desenvolva seu website ou aplicativo conosco. Entre em contato e faça um orçamento.</p>
				<a href="mailto:contact@dustdune.com"> Fazer Orçamento </a>
			</div>
		</div>
	</div>
</main>

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

	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	main {
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		min-height: 100vh;
		width: 100%;
		background: radial-gradient(circle, #290a72, #0a043c);
		position: relative;
		font-family: 'poppins', sans-serif;
		overflow-x: hidden;
		overflow-y: scroll !important;
	}

	.person {
		width: 20vw;
		margin-right: 2rem;

		@media (max-width: 1000px) {
			margin-right: 0rem;
			margin-bottom: 2rem;
		}
	}

	a {
		color: #000;
		font-weight: bold;
		font-size: 1.2rem;
		text-align: center;
		text-decoration: none;
		background: #fff;
		padding: 1rem 1rem;
		border-radius: 0.5rem;
		display: inline-block;
		margin-top: 1rem;
		box-shadow: 0 0 5rem rgba(1, 1, 1, 0.4);
	}

	.textcontainer {
		display: flex;
		flex-direction: column;
	}

	.fix-vertical {
		height: 100%;
		width: 100%;
		overflow-x: hidden;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.placeholderdiv {
		max-width: 60rem;
		display: flex;
		align-items: center;
		background-color: #222222;
		padding: 2rem 4rem;
		border-radius: 0.5rem;
		box-shadow: 0 0 5rem rgba(0, 0, 0, 0.4);

		@media (max-width: 1000px) {
			flex-direction: column;
			max-width: 70%;
		}

		@media (max-width: 800px) {
			flex-direction: column;
			max-width: 90%;
		}

		@media (max-width: 500px) {
			padding: 2rem;
			width: 80%;
		}
	}
</style>
