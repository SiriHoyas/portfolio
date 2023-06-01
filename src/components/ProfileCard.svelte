<script>
  export let caption;
  export let src;
  export let sticker;
</script>

<div class="container">
  <div class="title">
    <div class="circle circle1" />
    <div class="circle circle2" />
    <div class="circle circle3" />
  </div>
  <div class="image-container">
    <img alt="Siri" {src} />
  </div>
  <div class="footer">{caption}</div>
  <span class="sticker">
    <img src={sticker} alt="sticker" />
  </span>
</div>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap");
  .container {
    height: 330px;
    width: 290px;
    display: flex;
    flex-direction: column;
    border-radius: 6px;
    border: 0.5px solid black;
    transform: rotate(4deg);
    box-shadow: 0px 0px 7px 0px rgba(107, 107, 107, 0.75);
  }
  .title {
    display: flex;
    background-color: #f4f4f4;
    border-radius: 10px 10px 0 0;
    padding: 0.7rem;
  }
  .circle {
    border-radius: 100%;
    width: 10px;
    height: 10px;
    margin-left: 0.3rem;
  }

  .circle1 {
    background-color: #e3beca;
  }

  .circle2 {
    background-color: #76ba91;
  }

  .circle3 {
    background-color: var(--dark-yellow);
  }

  .image-container {
    flex-grow: 1;
    height: 100%;
    width: 100%;
  }
  .image-container img {
    margin: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .footer {
    font-family: "Press Start 2P", cursive;
    background-color: #f4f4f4;
    border-radius: 0 0 10px 10px;
    padding: 1rem;
    font-size: 0.6rem;
  }
  .sticker {
    width: 59px;
    height: 59px;
    position: absolute;
    right: -10px;
    top: 245px;
  }
</style>
