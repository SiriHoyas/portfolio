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
    height: 110px;
  }

  .link-container {
    font-family: "Bungee", cursive;
    margin-top: 1.3rem;
    display: flex;
    margin-left: 3rem;
    align-items: center;
    height: fit-content;
    font-size: 1.4rem;
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
</style>
