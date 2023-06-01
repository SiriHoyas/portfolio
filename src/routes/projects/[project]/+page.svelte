<script>
  import { projects } from "./../../../data/projects.js";

  export let data;

  const filteredArray = projects.filter((project) => project.id === parseInt(data.project));
  const project = filteredArray[0];
</script>

<main>
  <section class="image-container">
    <div class="dot-container">
      <div class="circle circle1" />
      <div class="circle circle2" />
      <div class="circle circle3" />
    </div>
    <img src={project.media} alt="wee" />
    <footer><h1>{project.title}</h1></footer>
  </section>
  <section class="info-container">
    <div class="quick-info">
      <h2>Info</h2>
      <span class="quick-info-container">
        <p>Subject:</p>
        <h3 class="quick-info-data">{project.subject}</h3>
      </span>
      <span>
        <p>Made with:</p>
        <ul>
          {#each project.madeWidth as tech}
            <li>{tech}</li>
          {/each}
        </ul>
      </span>
      <span class="quick-info-container grade">
        <p>Grade:</p>
        <h3 class="quick-info-data">{project.grade}</h3>
      </span>
      <span class="links">
        <a href={project.liveDemo}>
          <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 473.654 473.654" style="enable-background:new 0 0 473.654 473.654;" xml:space="preserve">
            <circle style="fill:#4ABC96;" cx="236.827" cy="236.827" r="236.827" />
            <path
              style="fill:#E0E4E3;"
              d="M420.81,157.331c0-22.426-18.182-40.608-40.612-40.608H107.763
            c-22.426,0-40.608,18.182-40.608,40.608v168.935c0,22.422,18.182,40.608,40.608,40.608h272.435c22.43,0,40.612-18.186,40.612-40.608
            V157.331z"
            />
            <path
              style="fill:#D1D3D3;"
              d="M420.541,152.806c-2.255-20.295-19.446-36.083-40.346-36.083H107.763
            c-22.426,0-40.608,18.182-40.608,40.608v8.212h353.39v-12.737H420.541z"
            />
            <circle style="fill:#E84849;" cx="99.559" cy="140.391" r="8.881" />
            <circle style="fill:#EFC849;" cx="133.215" cy="140.391" r="8.881" />
            <circle style="fill:#37B34C;" cx="166.871" cy="140.391" r="8.881" />
            <path
              style="fill:#9ED8D8;"
              d="M343.816,333.275h-0.711c-1.687-5.146-3.758-10.112-6.174-14.88l0.509-0.505
            c8.997-8.994,21.817-34.939,8.837-47.915l-7.909-7.909c-12.98-12.976-38.207-0.879-47.915,8.833l-0.509,0.509
            c-4.764-2.416-9.738-4.484-14.88-6.17v-0.707c0-12.722-9.282-40.126-27.639-40.126h-11.181c-18.346,0-27.639,26.39-27.639,40.126
            v0.711c-5.142,1.683-10.108,3.755-14.872,6.167l-0.509-0.512c-7.558-7.558-34.943-21.809-47.915-8.829l-7.909,7.905
            c-12.98,12.976,0.553,39.639,8.829,47.915l0.512,0.512c-2.416,4.764-4.484,9.73-6.17,14.876h-0.707
            c-10.691,0-40.126,9.285-40.126,27.639v5.164c2.595,0.52,5.277,0.8,8.025,0.8h72.391c0-0.123-0.019-0.243-0.019-0.374
            c0-34.079,27.624-61.703,61.703-61.703s61.703,27.624,61.703,61.703c0,0.127-0.019,0.247-0.019,0.374h76.672
            c1.264,0,2.513-0.079,3.747-0.191v-5.774C383.942,342.56,357.556,333.275,343.816,333.275z"
            />
          </svg>
        </a>
        <a href={project.github}>
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
          </svg></a
        >
      </span>
    </div>
    <div class="description">
      <h2>Description</h2>
      <p>{project.description}</p>
    </div>
  </section>
</main>

<style>
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
    background-color: #94ded3;
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
    background-color: #94ded3;
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
    background-color: var(--poison-green);
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
    text-shadow: var(--text-shadow);
    color: var(--poison-green);
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
    background-color: #94ded3;
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
  }

  .grade {
    margin-bottom: 1.4rem;
  }

  svg {
    width: 40px;
    height: 40px;
    margin-right: 1rem;
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
