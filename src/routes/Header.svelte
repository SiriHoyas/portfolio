<script>
  import Daisy from "../components/icons/Daisy.svelte";

  console.log("hello");
</script>

<header>
  <span class="background-container">
    <img src="src/routes/navbar.png" alt="navbar" />
  </span>
  <nav>
    <div class="link-container">
      <a href="/" class="links">
        <Daisy />
        <p>Home</p>
      </a>
      <a href="/projects" class="links">
        <Daisy />
        <p>Projects</p>
      </a>
    </div>
    <a href="/" class="logo-container">
      <p class="title">HEYSIRI</p>
      <span class="subtitle-container">
        <p>.</p>
        <p class="subtitle">CODES</p>
      </span>
    </a>
  </nav>
</header>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Bungee&display=swap");

  header {
    background-color: transparent;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  nav {
    position: absolute;
    display: flex;
    width: 100%;
    justify-content: space-between;
    top: 0;
  }

  .background-container {
    z-index: -1;
    position: relative;
    width: 100vw;
  }
  img {
    width: 100%;
    height: 200px;
  }

  .link-container {
    font-family: "Bungee", cursive;
    margin-top: 1rem;
    margin-left: 8rem;
    display: flex;
    align-items: center;
    height: fit-content;
    font-size: 1.5rem;
    text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
  }
  .links {
    display: flex;
    text-decoration: none;
    color: #f9da8f;
  }
  .links p {
    margin: 0;
    margin-left: 0.4rem;
    margin-right: 2rem;
  }

  .logo-container {
    margin-right: 2rem;
    margin-top: 1rem;
    text-decoration: none;
  }

  .logo-container p {
    font-family: "Bungee", cursive;
    text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
    color: #f9da8f;
    margin: 0;
    font-size: 2rem;
    text-decoration: none;
  }

  .subtitle {
    text-align: end;
  }

  .subtitle-container {
    display: flex;
    justify-content: space-between;
  }
</style>
