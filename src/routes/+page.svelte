<script>
  import Button from "../components/Button.svelte";
  import ProfileCard from "../components/ProfileCard.svelte";
</script>

<main>
  <section class="heading">
    <div>
      <h1>Hi! I'm Siri</h1>
      <h2>I am a frontend developer</h2>
      <p>Welcome to my frontend developer portfolio! I'm a skilled developer passionate about crafting engaging user experiences with clean code. With expertise in HTML, CSS, JavaScript, and front-end frameworks, I bring websites to life.</p>
    </div>
    <div>
      <Button />
    </div>
  </section>
  <section class="about">
    <ProfileCard />
  </section>
</main>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Bungee&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Montserrat+Alternates&display=swap");
  main {
    display: flex;
    justify-content: center;
    margin-top: 4rem;
  }
  .heading {
    width: 30%;
  }

  h1,
  h2 {
    font-family: "Bungee", cursive;
    text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
    color: #e9ad4e;
  }
  h1 {
    font-size: 3rem;
    margin: 0;
  }
  h2 {
    margin-top: 0;
  }
  p {
    font-family: "Montserrat Alternates", sans-serif;
    width: 90%;
  }
</style>
