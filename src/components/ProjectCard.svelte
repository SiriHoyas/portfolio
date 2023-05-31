<script>
  export let project;
</script>

<a href="/projects/{project.id}}" class="container">
  <div class="title">
    <div class="dot-container">
      <div class="circle circle1" />
      <div class="circle circle2" />
      <div class="circle circle3" />
    </div>
  </div>
  <div class="image-container">
    <img alt="Siri" src={project.media} />
  </div>
  <div class="footer">
    <h2 class="project-title">{project.title}</h2>
    <p class="description">{project.description}</p>
  </div>
</a>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap");
  .container {
    height: 300px;
    width: 350px;
    display: flex;
    flex-direction: column;
    border-radius: 6px;
    border: 0.5px solid black;
    box-shadow: 0px 0px 7px 0px rgba(107, 107, 107, 0.75);
    text-decoration: none;
    color: black;
  }

  .container:hover {
    animation: wiggle 500ms infinite;
    animation-timing-function: linear;
  }
  @keyframes wiggle {
    0% {
      transform: translate(0, 2px);
    }
    50% {
      transform: translate(0, -2px);
    }
    100% {
      transform: translate(0, 2px);
    }
  }
  .title {
    border-radius: 6px;
    background-color: #f4f4f4;
    display: flex;
    align-items: center;
    padding: 0.7rem;
  }

  .project-title {
    font-family: "Press Start 2P", cursive;
    font-size: 1rem;
    margin: 0;
    margin-top: 1rem;
  }
  .dot-container {
    display: flex;

    border-radius: 10px 10px 0 0;
  }
  .circle {
    border-radius: 100%;
    width: 10px;
    height: 10px;
    margin-left: 0.3rem;
    border: 0.1px solid rgb(109, 109, 109);
  }

  .circle1 {
    background-color: #c1e5bb;
  }

  .circle2 {
    background-color: #ddbbe5;
  }

  .circle3 {
    background-color: #94ded3;
  }

  .image-container {
    margin: 0;
    display: flex;
  }
  .image-container img {
    margin: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
  }

  .footer {
    height: 100px;
    font-family: "Press Start 2P", cursive;
    background-color: #f4f4f4;
    border-radius: 0 0 10px 10px;
    padding: 1rem;
  }

  .description {
    font-size: 0.6rem;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
</style>
