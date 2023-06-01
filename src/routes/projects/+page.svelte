<script>
  import ProjectCard from "../../components/ProjectCard.svelte";
  import { projects } from "../../data/projects";
</script>

<main>
  {#each Object.entries(projects) as [index, projects]}
    <ProjectCard project={projects} />
  {/each}
</main>

<style>
  main {
    margin: 0 auto;
    margin-top: 5rem;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-column-gap: 40px;
    grid-row-gap: 40px;
    margin-bottom: 4rem;
  }
  @media screen and (max-width: 1180px) {
    main {
      grid-template-columns: repeat(2, 1fr);
    }
  }
  @media screen and (max-width: 768px) {
    main {
      grid-template-columns: repeat(1, 1fr);
    }
  }
</style>
