<main>
	<div class="fix-vertical">
		<div class="placeholderdiv">
			<div class="person">
				<img width="100%" src="images/logo.svg" alt="logo" />
			</div>
			<div class="textcontainer">
				<p>Desenvolva seu website ou aplicativo conosco. Entre em contato e faça um orçamento.</p>
				<a href="mailto:contact@dustdune.com" class="mail">
					<p>Faça um orçamento</p>
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
						<path
							d="M0 3v18h24v-18h-24zm6.623 7.929l-4.623 5.712v-9.458l4.623 3.746zm-4.141-5.929h19.035l-9.517 7.713-9.518-7.713zm5.694 7.188l3.824 3.099 3.83-3.104 5.612 6.817h-18.779l5.513-6.812zm9.208-1.264l4.616-3.741v9.348l-4.616-5.607z"
							fill="#000"
						/>
					</svg>
				</a>
				<a href="mailto:contact@dustdune.com" class="mail">
					<p>Fale conosco</p>
					<svg xmlns="https://api.whatsapp.com/send?phone=5598982046032" viewBox="0 0 27 32">
						<path
							d=" M19.11 17.205c-.372 0-1.088 1.39-1.518 1.39a.63.63 0 0 1-.315-.1c-.802-.402-1.504-.817-2.163-1.447-.545-.516-1.146-1.29-1.46-1.963a.426.426 0 0 1-.073-.215c0-.33.99-.945.99-1.49 0-.143-.73-2.09-.832-2.335-.143-.372-.214-.487-.6-.487-.187 0-.36-.043-.53-.043-.302 0-.53.115-.746.315-.688.645-1.032 1.318-1.06 2.264v.114c-.015.99.472 1.977 1.017 2.78 1.23 1.82 2.506 3.41 4.554 4.34.616.287 2.035.888 2.722.888.817 0 2.15-.515 2.478-1.318.13-.33.244-.73.244-1.088 0-.058 0-.144-.03-.215-.1-.172-2.434-1.39-2.678-1.39zm-2.908 7.593c-1.747 0-3.48-.53-4.942-1.49L7.793 24.41l1.132-3.337a8.955 8.955 0 0 1-1.72-5.272c0-4.955 4.04-8.995 8.997-8.995S25.2 10.845 25.2 15.8c0 4.958-4.04 8.998-8.998 8.998zm0-19.798c-5.96 0-10.8 4.842-10.8 10.8 0 1.964.53 3.898 1.546 5.574L5 27.176l5.974-1.92a10.807 10.807 0 0 0 16.03-9.455c0-5.958-4.842-10.8-10.802-10.8z"
							fill="#000"
						/></svg
					>
				</a>
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

	.mail {
		height: 3rem;
		text-decoration: none;
		display: flex;
		background: #fff;
		width: 100%;
		align-items: center;
		justify-content: space-between;
		padding: 0.2rem 1rem;
		box-shadow: 0 0 0.5rem rgba(0, 0, 0, 0.2);
		margin-top: 1rem;
	}

	.mail > p {
		font-size: 1.2rem;
		margin-right: 1rem;
	}
	.mail > svg {
		width: 2rem;
	}
</style>
