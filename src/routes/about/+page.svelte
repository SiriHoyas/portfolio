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
      <ProfileCard src={"./../../assets/siri1.png"} caption={"Hello!"} sticker={"/src/components/icons/purpleFlower.svg"} />
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
  <section class="information-container">
    <div class="information-card contact-card">
      <h2>Find me here!</h2>
      <a href="https://www.linkedin.com/in/siri-h%C3%B8y%C3%A5s-2bb74b1a2/" class="socials-link">
        <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg"><g fill-rule="evenodd"><path d="m48 64h-32a16.0007 16.0007 0 0 1 -16-16v-32a16.0007 16.0007 0 0 1 16-16h32a16 16 0 0 1 16 16v32a16 16 0 0 1 -16 16" fill="#2864b4" /><path d="m30 18h18a9.0006 9.0006 0 0 0 .92-17.954c-.306-.017-.609-.046-.92-.046h-32a16.0007 16.0007 0 0 0 -16 16v32a30.0007 30.0007 0 0 1 30-30" fill="#417dcd" /><path d="m48 32a16 16 0 1 0 16 16v-32a16 16 0 0 1 -16 16" fill="#0f4b9b" /></g><rect fill="#fff" height="27" rx="2" width="8" x="12" y="25" /><circle cx="16" cy="16" fill="#fff" r="5" /><path d="m34 28.64a9.2164 9.2164 0 0 1 8-4.64c5.087 0 10 3 10 11v15a1.9994 1.9994 0 0 1 -2 2h-4a1.9994 1.9994 0 0 1 -2-2v-14a5 5 0 0 0 -10 0v14a1.9994 1.9994 0 0 1 -2 2h-4a1.9994 1.9994 0 0 1 -2-2v-23a1.9994 1.9994 0 0 1 2-2h4a1.9994 1.9994 0 0 1 2 2z" fill="#fff" fill-rule="evenodd" /></svg>
        <p>Linkedin</p>
      </a>
      <a href="https://github.com/SiriHoyas" class="socials-link">
        <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 496 496" style="enable-background:new 0 0 496 496;" xml:space="preserve">
          <path
            id="SVGCleanerId_0"
            style="fill:#3E77BF;"
            d="M247.992,5.163C111.048,5.163,0,116.627,0,254.163
c0,109.992,71.048,203.32,169.632,236.24c12.392,2.296,16.912-5.392,16.912-12c0-5.904-0.216-21.56-0.336-42.344
c-69,15.064-83.552-33.376-83.552-33.376c-11.264-28.768-27.52-36.408-27.52-36.408c-22.528-15.456,1.696-15.16,1.696-15.16
c24.88,1.752,37.976,25.672,37.976,25.672c22.144,38.048,58.064,27.048,72.192,20.672c2.232-16.08,8.656-27.064,15.736-33.28
c-55.056-6.296-112.944-27.64-112.944-123.04c0-27.176,9.656-49.408,25.52-66.832c-2.568-6.296-11.072-31.6,2.416-65.872
c0,0,20.832-6.688,68.2,25.52c19.784-5.52,41-8.28,62.096-8.392c21.048,0.112,42.28,2.864,62.096,8.392
c47.328-32.208,68.128-25.52,68.128-25.52c13.52,34.272,5.016,59.576,2.456,65.872c15.904,17.424,25.504,39.648,25.504,66.832
c0,95.64-57.984,116.68-113.232,122.856c8.904,7.688,16.832,22.872,16.832,46.112c0,33.296-0.296,60.128-0.296,68.296
c0,6.672,4.472,14.424,17.048,11.968C425.016,457.387,496,364.123,496,254.163C496,116.627,384.952,5.163,247.992,5.163z"
          />
          <g>
            <path
              id="SVGCleanerId_0_1_"
              style="fill:#3E77BF;"
              d="M247.992,5.163C111.048,5.163,0,116.627,0,254.163
 c0,109.992,71.048,203.32,169.632,236.24c12.392,2.296,16.912-5.392,16.912-12c0-5.904-0.216-21.56-0.336-42.344
 c-69,15.064-83.552-33.376-83.552-33.376c-11.264-28.768-27.52-36.408-27.52-36.408c-22.528-15.456,1.696-15.16,1.696-15.16
 c24.88,1.752,37.976,25.672,37.976,25.672c22.144,38.048,58.064,27.048,72.192,20.672c2.232-16.08,8.656-27.064,15.736-33.28
 c-55.056-6.296-112.944-27.64-112.944-123.04c0-27.176,9.656-49.408,25.52-66.832c-2.568-6.296-11.072-31.6,2.416-65.872
 c0,0,20.832-6.688,68.2,25.52c19.784-5.52,41-8.28,62.096-8.392c21.048,0.112,42.28,2.864,62.096,8.392
 c47.328-32.208,68.128-25.52,68.128-25.52c13.52,34.272,5.016,59.576,2.456,65.872c15.904,17.424,25.504,39.648,25.504,66.832
 c0,95.64-57.984,116.68-113.232,122.856c8.904,7.688,16.832,22.872,16.832,46.112c0,33.296-0.296,60.128-0.296,68.296
 c0,6.672,4.472,14.424,17.048,11.968C425.016,457.387,496,364.123,496,254.163C496,116.627,384.952,5.163,247.992,5.163z"
            />
          </g>
          <g>
            <path
              style="fill:#114C82;"
              d="M378.496,109.131c13.128,33.904,4.752,58.928,2.2,65.176c15.904,17.424,25.504,39.648,25.504,66.832
 c0,95.64-57.984,116.68-113.232,122.856c8.904,7.688,16.832,22.872,16.832,46.112c0,33.296-0.296,60.128-0.296,68.296
 c0,6.672,4.472,14.424,17.048,11.968C425.016,457.387,496,364.123,496,254.163c0-29.56-5.152-57.896-14.568-84.2
 C447.24,133.963,409.184,109.987,378.496,109.131z"
            />
            <path
              style="fill:#114C82;"
              d="M192.976,377.323c2.784-5.616,6.184-9.984,9.76-13.144c-30.176-3.456-61.168-11.512-83.048-33.744
 C136.52,358.451,163.928,371.195,192.976,377.323z"
            />
          </g>
          <path
            style="fill:#6CA9EA;"
            d="M12.912,270.947c0-137.536,111.048-249,247.992-249c76.04,0,144.056,34.392,189.536,88.488
C405.52,46.755,331.616,5.163,247.992,5.163C111.048,5.163,0,116.627,0,254.163c0,61.32,22.12,117.424,58.752,160.792
C29.944,374.291,12.912,324.643,12.912,270.947z"
          />
          <path
            style="fill:#083E66;"
            d="M322.712,426.899c0-23.232-7.928-38.44-16.832-46.128c55.248-6.16,113.24-27.216,113.24-122.848
c0-27.184-9.6-49.4-25.52-66.824c2.576-6.296,11.096-31.608-2.456-65.872c0,0-2.576-0.792-7.896-0.488
c5.808,25.84-0.416,44.32-2.552,49.568c15.904,17.424,25.504,39.648,25.504,66.832c0,95.64-57.984,116.68-113.232,122.856
c8.904,7.688,16.832,22.872,16.832,46.112c0,33.296-0.296,60.128-0.296,68.296c0,5.872,3.496,12.568,12.92,12.408
C322.488,479.555,322.712,455.659,322.712,426.899z"
          />
          <path
            style="fill:#114C82;"
            d="M117.464,423.995c5.208,10.72,22.712,36.4,68.888,30.992c-0.064-5.648-0.112-11.976-0.144-18.928
C150.584,443.835,129.552,434.667,117.464,423.995z"
          />
          <path
            style="fill:#6CA9EA;"
            d="M126.368,391.387c-1.592-2.4-4.576-6.472-8.904-10.544
C120.272,385.011,123.256,388.507,126.368,391.387z"
          />
        </svg>

        <p>GitHub</p>
      </a>
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
  .contact-card {
    width: 90%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .socials-link {
    display: flex;
    align-items: center;
  }
  .contact-card svg {
    width: 40px;
    height: 40px;
  }
  .contact-card p {
    font-family: "Bungee", cursive;
    text-decoration: none;
    color: var(--dark-yellow);
    text-shadow: var(--text-shadow);
    margin-left: 1rem;
    font-size: 1.5rem;
  }

  @media screen and (max-width: 1180px) {
    main {
      width: 90%;
    }
    .information-container {
      flex-direction: column;
      align-items: center;
    }
    .information-card {
      width: 100%;
    }
  }
</style>
