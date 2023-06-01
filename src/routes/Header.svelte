<script>
  import Daisy from "../components/icons/Daisy.svelte";
  import navbar from "./../routes/navbar.png";

  console.log("hello");
</script>

<header>
  <span class="background-container">
    <img src={navbar} alt="navbar" />
  </span>
  <nav>
    <a href="/">
      <h2 class="logo">Heysiri.codes</h2>
    </a>
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
  </nav>
</header>

<style>
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
    height: 130px;
  }

  h2 {
    font-family: "Bungee", cursive;
    font-size: 2rem;
    margin-left: 3rem;
    color: var(--medium-yellow);
    text-shadow: var(--text-shadow);
  }

  a {
    text-decoration: none;
  }
  .link-container {
    font-family: "Bungee", cursive;
    margin-top: 1.3rem;
    display: flex;
    margin-left: 3rem;
    align-items: center;
    height: fit-content;
    font-size: 1.4rem;
    text-shadow: var(--text-shadow);
  }
  .links {
    display: flex;
    text-decoration: none;
    color: var(--medium-yellow);
  }
  .links p {
    margin: 0;
    margin-left: 0.4rem;
    margin-right: 3rem;
  }
</style>
