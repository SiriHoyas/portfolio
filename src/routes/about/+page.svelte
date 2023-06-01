<script>
  import ProfileCard from "../../components/ProfileCard.svelte";
</script>

<main>
  <section class="information-container">
    <div class="information-card">
      <h1>Hi! I'm Siri</h1>
      <p>Hey there! I'm a woman living in Kristiansand with my amazing husband.</p>
      <p>I spent a good chunk of my career, around 10 years, in the consumer electronics industry. Starting as a part-time cashier, I worked my way up to become a department manager for operations.</p>
      <p>It was quite a journey, and I even got selected as one of 30 people in the company with leadership potential, which led me to their leadership development program.</p>
    </div>
    <div class="profile-card-container">
      <ProfileCard src={"/src/assets/siri1.png"} caption={"Hello!"} sticker={"/src/components/icons/purpleFlower.svg"} />
    </div>
  </section>
  <section class="information-container">
    <div class="profile-card-container">
      <ProfileCard src={"/src/assets/siri2.png"} caption={"I love disc golf!"} sticker={"/src/components/icons/star.svg"} />
    </div>
    <div class="information-card">
      <h2>I love coding</h2>
      <p>Technology has always fascinated me, and during the lockdown, I decided to dive deeper into it. I took some online tutorials on JavaScript, HTML, and CSS, and something just clicked. I realized that I wanted to turn this interest into a full-fledged career.</p>
      <p>That's when I made the leap and pursued a higher professional degree in frontend development from Noroff. I recently finished school in the summer of 2023, and boy, did I learn a lot! JavaScript and React became my go-to tools, and I also had the chance to explore design basics, UX, and UI design.</p>
      <p>I really enjoy designing, but coding... that's where my heart truly lies. There's something so satisfying about bringing ideas to life through programming. I love the thrill of solving problems and creating websites and applications that are not only functional but also visually appealing.</p>
    </div>
  </section>

  <section class="information-container">
    <div class="information-card">
      <h2>After work</h2>
      <p>When I'm not immersed in the world of coding, I love spending time with my awesome group of friends who share similar interests and hobbies. We have a blast together and enjoy engaging in various activities that bring us closer.</p>
      <p>One of my biggest passions is disc golf, and I proudly play for Lillesand IL Frisbeegolf. It's not just a game for me; it's a way of life. I'm deeply committed to building up the representation of women in this sport, not only in Sørlandet but throughout the country. To promote inclusivity, I organize women-only tournaments and, together with my friends, we're working on establishing a female-only club for disc golfers in our area. I want to create a safe and supportive space where people can come together, improve their skills, and feel a sense of belonging.</p>
      <p>n addition to my disc golf pursuits, I'm also involved with the Norwegian Disc Sport Association. It's an exciting opportunity for me to contribute to the growth and development of the sport at a national level.</p>
      <p>Music holds a special place in my heart, and I find immense joy in attending concerts and immersing myself in different genres. It's a source of inspiration and relaxation for me, and I can't imagine life without it.</p>
    </div>
    <div class="profile-card-container">
      <ProfileCard src={"/src/assets/siri3.png"} caption={"I love disc golf!"} sticker={"/src/components/icons/sunflower.svg"} />
    </div>
  </section>
</main>

<style>
  main {
    width: 80%;
    display: flex;
    flex-direction: column;
    margin: 0 auto;
    margin-bottom: 4rem;
  }
  .information-container {
    margin-top: 4rem;
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

  h1,
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
    margin-bottom: 0.5rem;
  }
</style>
