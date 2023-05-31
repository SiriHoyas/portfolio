<script>
  export let data;
</script>

<main>
  <section class="image-container">
    <div class="dot-container">
      <div class="circle circle1" />
      <div class="circle circle2" />
      <div class="circle circle3" />
    </div>
    <img src={"/src/assets/holidazeThombnail.png"} alt="wee" />
    <footer><h1>{data.project}</h1></footer>
  </section>
  <section class="info-container">
    <div class="quick-info">
      <h2>Info</h2>
      <span class="quick-info-container">
        <p>Subject:</p>
        <h3 class="quick-info-data">Exam project 2</h3>
      </span>
      <span>
        <p>Technology:</p>
        <ul>
          <li>React</li>
          <li>MUI</li>
        </ul>
      </span>
      <span class="quick-info-container">
        <p>Grade:</p>
        <h3 class="quick-info-data">A</h3>
      </span>
    </div>
    <div class="description">
      <h2>Description</h2>
      <p>The goal of this project is to develop a front-end for a venue booking site called Holidaze. While the required features are defined, the design and user experience are left open-ended, providing the freedom to plan, design, and build a modern application that meets the needs of both customers and administrators. The application consists of two main components: the customer-facing side, where users can browse and book holidays at various venues, and the admin-facing side, where registered users can manage venues and bookings. The project uses Noroffs internal API.The goal of this project is to develop a front-end for a venue booking site called Holidaze. While the required features are defined, the design and user experience are left open-ended, providing the freedom to plan, design, and build a modern application that meets the needs of both customers and administrators. The application consists of two main components: the customer-facing side, where users can browse and book holidays at various venues, and the admin-facing side, where registered users can manage venues and bookings. The project uses Noroffs internal API.</p>
    </div>
  </section>
</main>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Bungee&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Montserrat+Alternates:wght@400;500;600&display=swap");
  main {
    width: 60%;
    margin: 0 auto;
    align-items: center;
    display: flex;
    flex-direction: column;
    margin-top: 4rem;
    margin-bottom: 4rem;
  }
  .image-container {
    background-color: #385e97;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    padding: 0 1rem;
  }
  .image-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .dot-container {
    display: flex;
    border-radius: 10px 10px 0 0;
    background-color: #385e97;
  }

  .circle {
    border-radius: 100%;
    width: 13px;
    height: 13px;
    margin-left: 0.3rem;
    margin-top: 1rem;
    border: 0.1px solid rgb(109, 109, 109);
    margin-bottom: 1rem;
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
  footer {
    padding: 1rem;
  }

  h1,
  h2,
  h3 {
    font-family: "Bungee", cursive;
    margin: 0;
    text-align: center;
    text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
    color: #ffd169;
    margin: 0;
    font-size: 2.5rem;
  }

  h2 {
    font-size: 1.5rem;
  }
  h3 {
    font-size: 1rem;
    margin: 0;
  }

  .info-container {
    display: flex;
    justify-content: space-between;
    margin-top: 2rem;
    width: 100%;
    gap: 2rem;
  }
  .quick-info,
  .description {
    background-color: #385e97;
    padding: 1rem;
    border-radius: 10px;
  }
  .quick-info {
    width: 40%;
  }
  .description {
    width: 50%;
  }
  p {
    font-family: "Montserrat Alternates", sans-serif;
    font-weight: 600;
    margin-bottom: 0.5rem;
    color: rgb(218, 218, 218);
  }
  .quick-info-container {
    display: flex;
    align-items: baseline;
  }
  .quick-info-data {
    margin-left: 0.9rem;
  }

  ul {
    font-family: "Montserrat Alternates", sans-serif;
    padding: 0 1rem;
    margin: 0;
    list-style-type: none;
    color: rgb(218, 218, 218);
  }

  @media screen and (max-width: 1180px) {
    main {
      width: 85%;
    }
    .info-container {
      flex-direction: column;
      align-items: center;
    }
    .image-container {
      width: 100%;
    }
    .quick-info {
      width: 100%;
    }
    .description {
      width: 100%;
    }
  }
</style>
