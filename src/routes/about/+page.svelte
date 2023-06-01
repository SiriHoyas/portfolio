<script>
  import ProfileCard from "../../components/ProfileCard.svelte";
</script>

<main>
  <section class="information-container">
    <div class="information-card">
      <h2>Title</h2>
      <p>Disc golf is a popular outdoor sport that combines elements of golf and frisbee. It is played on a course consisting of a series of targets called "baskets." The objective of the game is to throw a disc into each basket in as few throws as possible. Players start at a designated tee area and throw the disc towards the basket, navigating the course's various obstacles such as trees, bushes, and elevation changes. Disc golf can be enjoyed by people of all ages and skill levels, as there are different types of discs available for different throwing techniques. The sport provides a great opportunity to enjoy nature and exercise while engaging in a competitive activity. Disc golf courses can be found in parks, recreational areas, and even dedicated disc golf facilities. It fosters a sense of community and camaraderie among players, with tournaments and leagues held regularly. The game requires strategy, accuracy, and control, as players must consider the distance, wind conditions, and terrain when selecting their throwing techniques. Disc golf continues to grow in popularity worldwide, with enthusiasts organizing events and spreading the joy of this exciting sport.</p>
    </div>
    <div class="profile-card-container">
      <ProfileCard />
    </div>
  </section>
</main>

<style>
  main {
    width: 80%;
    display: flex;
    flex-direction: column;
    margin: 0 auto;
  }
  .information-container {
    margin-top: 2rem;
    display: flex;
    justify-content: space-evenly;
  }
  .information-card {
    width: 40%;
    padding: 1rem;
    background-color: var(--poison-green);
    border-radius: 10px;
  }

  .profile-card-container {
    margin-top: 3rem;
  }

  h2 {
    font-family: "Bungee", cursive;
    margin: 0;
    text-align: center;
    text-shadow: var(--text-shadow);
    color: #94ded3;
    margin: 0;
    font-size: 2.5rem;
  }
  p {
    font-family: "Montserrat Alternates", sans-serif;
    font-weight: 600;
    margin-bottom: 0.5rem;
  }
</style>
