<script>
  import Button from "../components/Button.svelte";
  import ProfileCard from "../components/ProfileCard.svelte";
  import siri from "./../assets/portrait.jpeg";
  import redFlower from "./../assets/redFlower.svg";
</script>

<main>
  <svg class="main-sticker" id="Layer_1" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" data-name="Layer 1"><path d="m46.612 59.508c-1.948-2.7-3.117-8.924-.436-10.885s8.196 1.077 10.144 3.777a6.072 6.072 0 0 1 -1.328 8.441 5.97 5.97 0 0 1 -8.38-1.333z" fill="#fad4af" /><path d="m57.717 49.307c-3.254 1.024-9.695.226-10.753-2.925s3.67-7.464 6.924-8.488a6.24 6.24 0 0 1 7.812 3.853 5.962 5.962 0 0 1 -3.983 7.56z" fill="#fad4af" /><path d="m60.74 39.97a6.358 6.358 0 0 0 -5.85-1.08c-3.26 1.03-7.98 5.34-6.93 8.49a2.734 2.734 0 0 0 .38.74 3.557 3.557 0 0 1 -1.38-1.74c-1.05-3.15 3.67-7.46 6.93-8.49a6.336 6.336 0 0 1 6.85 2.08z" fill="#fbddbf" /><path d="m33.68 52.4c1.948-2.7 7.464-5.743 10.144-3.781s1.512 8.185-.436 10.885a5.97 5.97 0 0 1 -8.38 1.337 6.072 6.072 0 0 1 -1.328-8.441z" fill="#fad4af" /><path d="m44.6 49.48c-2.75-1.66-8.02 1.29-9.92 3.92a6.088 6.088 0 0 0 .15 7.31 6.071 6.071 0 0 1 -1.15-8.31c1.95-2.7 7.46-5.74 10.14-3.78a2.791 2.791 0 0 1 .78.86z" fill="#fbddbf" /><path d="m51 36c0 3.314-2.686 9-6 9s-6-5.686-6-9a6 6 0 0 1 12 0z" fill="#fad4af" /><path d="m40 37a12.589 12.589 0 0 0 2.66 7.06 12 12 0 0 1 -3.66-8.06 6 6 0 0 1 10.71-3.71 5.944 5.944 0 0 0 -3.71-1.29 6 6 0 0 0 -6 6z" fill="#fbddbf" /><path d="m36.112 37.894c3.254 1.024 7.981 5.336 6.924 8.488s-7.5 3.949-10.753 2.925a5.962 5.962 0 0 1 -3.978-7.56 6.24 6.24 0 0 1 7.807-3.853z" fill="#fad4af" /><circle cx="45" cy="47" fill="#fbf1d6" r="4" /><path d="m41.21 41.37a12.26 12.26 0 0 0 -4.1-2.48 6.255 6.255 0 0 0 -7.81 3.86 5.835 5.835 0 0 0 .98 5.5 5.894 5.894 0 0 1 -1.98-6.5 6.255 6.255 0 0 1 7.81-3.86 12.764 12.764 0 0 1 5.1 3.48z" fill="#fbddbf" /><path d="m48.28 44.72a3.993 3.993 0 0 0 -5.56 5.56 4 4 0 1 1 5.56-5.56z" fill="#fcf4de" /><path d="m13.8 22.569c1.513 2.309 2.512 7.918.2 9.431s-7.053-1.641-8.567-3.95a5 5 0 0 1 8.367-5.481z" fill="#b3dbdb" /><path d="m5.535 29.279c2.555-.726 7.965.057 8.665 2.721s-3.586 6.2-6.141 6.927a4.775 4.775 0 0 1 -5.885-3.51 5.027 5.027 0 0 1 3.361-6.138z" fill="#b3dbdb" /><path d="m22.908 28.893c-1.729 2.153-6.754 4.836-8.908 3.107s-.619-7.215 1.11-9.368a5 5 0 0 1 7.8 6.261z" fill="#b3dbdb" /><path d="m13.6 22.31a5 5 0 0 0 -7.17 6.74c.15.22.32.45.52.69a8.8 8.8 0 0 1 -1.52-1.69 4.995 4.995 0 0 1 8.17-5.74z" fill="#c2e2e2" /><path d="m13.9 31.34a10.416 10.416 0 0 0 -7.36-1.06 5.019 5.019 0 0 0 -3.37 6.14 4.892 4.892 0 0 0 .84 1.73 4.924 4.924 0 0 1 -1.84-2.73 5.019 5.019 0 0 1 3.37-6.14c2.32-.67 7.02-.07 8.36 2.06z" fill="#c2e2e2" /><path d="m23.01 22.76a5 5 0 0 0 -6.9.87c-1.53 1.91-2.91 6.42-1.7 8.63a2.186 2.186 0 0 1 -.41-.26c-2.15-1.73-.62-7.21 1.11-9.37a5 5 0 0 1 7.03-.77 5.282 5.282 0 0 1 .87.9z" fill="#c2e2e2" /><path d="m8.621 39.75c.133-2.758 2.621-7.883 5.379-7.75s4.742 5.474 4.609 8.232a5 5 0 1 1 -9.988-.482z" fill="#b3dbdb" /><path d="m19.669 39.512c-2.476-.979-6.412-4.93-5.473-7.512s6.4-2.818 8.872-1.839a5.068 5.068 0 0 1 2.783 6.448 4.737 4.737 0 0 1 -6.182 2.903z" fill="#b3dbdb" /><circle cx="14" cy="32" fill="#fbf1d6" r="3" /><path d="m16.56 30.44a3 3 0 0 0 -4.12 4.12 3.084 3.084 0 0 1 -.95-.92 3 3 0 1 1 5.02-3.28c.02.03.03.05.05.08z" fill="#fcf4de" /><g fill="#fdafab"><path d="m46.69 18.6c-2.751.245-8.167-1.52-8.412-4.27s4.774-5.445 7.525-5.69a5 5 0 0 1 .887 9.96z" /><path d="m36.815 23.648c-1.083-2.541-1.078-8.237 1.463-9.32s6.653 2.858 7.736 5.4a5 5 0 0 1 -9.2 3.922z" /><path d="m44.811 8.006c-.607 2.633-3.939 7.131-6.627 6.518s-3.718-6.1-3.111-8.738a4.995 4.995 0 0 1 9.738 2.22z" /><path d="m33.983 6.076c2.369 1.4 5.713 5.94 4.3 8.274s-7.063 1.575-9.433.178a4.885 4.885 0 0 1 -1.721-6.756 5.044 5.044 0 0 1 6.854-1.696z" /><path d="m28.889 15.953c2.072-1.8 7.476-3.524 9.295-1.449s-.637 7.164-2.709 8.961a5.014 5.014 0 0 1 -7.044-.5 4.949 4.949 0 0 1 .458-7.012z" /></g><path d="m50.24 10.61a4.958 4.958 0 0 0 -3.44-.97c-2.75.24-7.77 2.94-7.52 5.69a2.51 2.51 0 0 0 .5 1.25 3.338 3.338 0 0 1 -1.5-2.25c-.25-2.75 4.77-5.45 7.52-5.69a4.989 4.989 0 0 1 4.44 1.97z" fill="#fdbfbc" /><path d="m43.95 4.01a5.025 5.025 0 0 0 -7.88 2.78 11 11 0 0 0 1.36 7.41c-2.13-1.35-2.9-6.04-2.36-8.41a4.96 4.96 0 0 1 5.97-3.66 5.017 5.017 0 0 1 2.91 1.88z" fill="#fdbfbc" /><path d="m36.1 7.9a7.555 7.555 0 0 0 -1.12-.82 5.045 5.045 0 0 0 -6.86 1.69 4.872 4.872 0 0 0 .27 5.45 4.884 4.884 0 0 1 -1.27-6.45 5.045 5.045 0 0 1 6.86-1.69 9.416 9.416 0 0 1 2.12 1.82z" fill="#fdbfbc" /><path d="m38.5 14.98c-2.23-1.19-6.76.37-8.61 1.97a4.94 4.94 0 0 0 -.67 6.75 5.5 5.5 0 0 1 -.79-.74 4.95 4.95 0 0 1 .46-7.01c2.07-1.79 7.47-3.52 9.29-1.45a2.01 2.01 0 0 1 .32.48z" fill="#fdbfbc" /><circle cx="38.278" cy="14.328" fill="#fbf1d6" r="3" /><path d="m40.67 12.51a3 3 0 0 0 -4.07 4.3 3 3 0 1 1 4.07-4.3z" fill="#fcf4de" /></svg>
  <section class="heading">
    <div>
      <h1>Hi! I'm Siri</h1>
      <h2>I'm a frontend developer</h2>
      <p class="description">Welcome to my frontend developer portfolio! I'm a skilled developer passionate about crafting engaging user experiences with clean code. With expertise in HTML, CSS, JavaScript, and front-end frameworks, I bring websites to life.</p>
    </div>
    <div class="button-container">
      <Button href="/projects" variant="secondary" class="projects-btn">Projects</Button>
      <Button href="/about" variant="primary">About me</Button>
    </div>
  </section>
  <section class="about">
    <ProfileCard src={siri} sticker={redFlower} caption={"Thats me!"} />
  </section>
</main>

<style>
  main {
    display: flex;
    justify-content: center;
    margin: 0 auto;
    margin-top: 7rem;
    width: 100%;
    margin-bottom: 4rem;
  }

  .main-sticker {
    position: absolute;
    z-index: -1;
    top: 200px;
    left: 150px;
    height: 200px;
    width: 200px;
  }
  .heading {
    width: 40%;
  }

  h1,
  h2 {
    font-family: "Bungee", cursive;
    text-shadow: var(--text-shadow);
    color: var(--dark-yellow);
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
    width: 50%;
  }

  @media screen and (max-width: 1180px) {
    main {
      flex-direction: column-reverse;
    }

    .about {
      margin: 0 auto;
      margin-bottom: 2rem;
    }

    .heading {
      margin: 0 auto;
      text-align: center;
      width: 100%;
    }

    .description {
      display: none;
    }
    .button-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      margin: 0 auto;
      gap: 1rem;
    }
  }
  @media screen and (max-width: 768px) {
    main {
      margin-top: -3rem;
    }
  }
</style>
