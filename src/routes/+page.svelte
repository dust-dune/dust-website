<header>
  <div class="inner-header">
    <h1>DUST DUNE</h1>
    <div>
      <button on:click={() => console.log('home')}>Home</button>
      <button on:click={() => console.log('about')}>About us</button>
      <button on:click={() => console.log('contact')}>Contact</button>
    </div>
  </div>
</header>

<main>
  <div class="header-space"/>
  <img src="call_to_mayhem_ant.png" alt="call_to_mayhem_image" />
</main>

<footer>
  <div>
    <a href="https://www.linkedin.com/company/dustdune" target="_blank">LinkedIn</a>
    <a href="https://www.instagram.com/dustdunegames" target="_blank">Instagram</a>
    <a href="https://twitter.com/dustdune" target="_blank">Twitter</a>
    <a href="https://www.tiktok.com/@dust_dune" target="_blank">TikTok</a>
  </div>
</footer>

<style>
  :global(body) {
    background-color: #000;
    color: #fff;
    margin: 0;
    padding: 0;
  }

  main {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  header {
    position: fixed;
    display: flex;
    width: 100%;
    justify-content: center;
    align-items: center;
    background-color: #06162C;
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

  img {
    max-width: 100%;
    height: auto;
  }

  button {
    background-color: #06162C;
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

  footer {
    display: flex;
    justify-content: center;
    background-color: #06162C;
    height: 100px;
    padding: 20px;
    text-align: center;
  }

  a {
    color: #64ffda;
    margin-right: 10px;
    text-decoration: none;
  }
</style>

