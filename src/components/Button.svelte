<script>
  export let type;
  export let href;
  export let variant;
  export let spacing;
</script>

{#if href}
  <a class="btn {spacing} {variant}" {href}><slot /></a>
{:else}
  <button class="btn {spacing} {variant}" {type}><slot /></button>
{/if}

<style>
  @import url("https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap");
  .btn {
    border-radius: 7px;
    padding: 0.6rem 3rem;
    font-family: "Press Start 2P", cursive;
    box-shadow: 2px 2px 0px 0px rgba(0, 0, 0, 0.75);
    cursor: pointer;
    border: 1px solid black;
    color: black;
    text-decoration: none;
    font-size: 1rem;
    width: fit-content;
  }
  .primary {
    background-color: var(--poison-green);
  }
  .secondary {
    background-color: var(--first-run);
  }
  .left {
    margin-left: 1rem;
  }
  .right {
    margin-right: 1rem;
  }
</style>
