<script>
  import Header from "./Header.svelte";
  import "./styles.css";
</script>

<div class="app">
  <Header />
  <main>
    <slot />
  </main>
</div>

<style>
  .app {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  }

  main {
    flex: 1;
    display: flex;
    flex-direction: column;
    width: 100%;
    box-sizing: border-box;
    background-size: 100%;
    background-repeat: no-repeat;
    background-position: top;
  }
</style>
