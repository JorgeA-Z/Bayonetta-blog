<script>
  import NavBar from "../NavBar.svelte";
  import b1 from "../../Images/B1.jpg.webp";

  import b2 from "../../Images/B2.jpg";
  import b3 from "../../Images/B3.jpg";
  import b4 from "../../Images/B4.jpg";
</script>

<header>
  <NavBar />
</header>

<div class="sample-section-wrap">
  <div class="sample-section">
    <div>
      <h1>Juegos de la franquicia</h1>
      <p>
        Bayonetta (nombre real Cereza) es el personaje principal y la
        protagonista de la serie del mismo nombre Bayonetta. Ella es una Bruja
        de Umbra coqueta y misteriosa, que posee un notable talento para las
        artes del disparo y es la portadora del Ojo Izquierdo, que supervisa la
        oscuridad.
      </p>
    </div>

    <div class="Timeline">
      <div class="Card">
        <h1>Bayonetta</h1>
        <img class="ImageContainer" src={b1} alt="" />
      </div>
      <div class="Card">
        <h1>Bayonetta 2</h1>
        <img class="ImageContainer2" src={b2} alt="" />
      </div>
      <div class="Card">
        <h1>Bayonetta 3</h1>
        <img class="ImageContainer2" src={b3} alt="" />
      </div>
      <div class="Card">
        <h1>Cereza and the lost demon</h1>
        <img class="ImageContainer" src={b4} alt="" />
      </div>
    </div>
  </div>
</div>

<style>
  h1 {
    text-align: center;
  }
  .sample-section-wrap {
    position: relative;
    background-color: #bb8fce;
  }
  .ImageContainer {
    width: 200px;
    height: 200px;
  }
  .ImageContainer2 {
    width: 130px;
    height: 200px;
  }
  .sample-section {
    position: relative;
    max-width: 640px;
    margin-left: auto;
    margin-right: auto;
    padding: 40px;
    background-color: white;
  }
  .Timeline {
    width: 300px;
    margin: auto;
  }

  .Card {
    border-top: 2px dashed;
    border-color: #bb8fce !important;
    margin: 0;
    padding: 30px;
  }

  .Card:nth-child(even) {
    border-left: 2px dashed;
    border-top-left-radius: 30px;
    border-bottom-left-radius: 30px;
    margin-right: 30px;
    padding-right: 0;
  }

  .Card:nth-child(odd) {
    border-right: 2px dashed;
    border-top-right-radius: 30px;
    border-bottom-right-radius: 30px;
    margin-left: 30px;
    padding-left: 0;
  }

  .Card:first-child {
    border-top: 0;
    border-top-right-radius: 0;
    border-top-left-radius: 0;
  }

  .Card:last-child {
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0;
  }
</style>
