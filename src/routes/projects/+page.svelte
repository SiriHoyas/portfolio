<script>
  import ProjectCard from "../../components/ProjectCard.svelte";
</script>

<main>
  <ProjectCard />
  <ProjectCard />
  <ProjectCard />
  <ProjectCard />
  <ProjectCard />
  <ProjectCard />
  <ProjectCard />
  <ProjectCard />
</main>

<style>
  main {
    margin: 0 auto;
    margin-top: 5rem;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-column-gap: 40px;
    grid-row-gap: 40px;
  }
</style>
