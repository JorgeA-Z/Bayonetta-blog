<script>
    import NavBar from "./NavBar.svelte";
    import Imagen1 from "../Images/1.png";
    import Imagen2 from "../Images/2.png";
</script>


<header>
    <NavBar>

    </NavBar>
</header>

  <div class="sample-section-wrap">
    <div class="sample-section">
        <h1>Érase una vez, una joven bruja llamada Cereza...</h1>
        <p>
        Una aprendiz de bruja llamada Cereza que deseaba volverse fuerte y segura de sí misma.
        Un buen día, acompañada de su preciado peluche, se adentró en el bosque prohibido de Ávalon para salvar a su madre cautiva.
        Dice la leyenda que las brujas que se aventuran en este sinuoso y peculiar bosque desaparecen para siempre...
        </p>    
        <div class="card">
            <h2>¿Qué siniestras sorpresas aguardan en su interior?</h2>
            <div class="grid-container">
                <div class="grid-item">
                    <p>Mucho antes de que esta aprendiz de las artes ocultas fuera llamada Bayonetta, emprendió un funesto viaje hacia la región prohibida de Bosque Ávalon. A su lado se encontraba Cheshire, su primer demonio, que poseía a su peluche. Juega como ambos, Cereza y Cheshire, y explora el peligroso bosque en busca del poder para salvar a la madre de Cereza. </p>

                </div>
                <div class="grid-item">
                    <img class="ImagenContainer" src={Imagen1} alt="Girl in a jacket">
                </div>
            </div>
        </div>

        <p>
            Esta vez nos encontramos ante una historia de orígenes en la que encarnaremos a Bayonetta mucho antes de que se la conociese como tal, cuando tan solo era una niña repudiada por los suyos que entrenaba para ser bruja bajo la tutela de su maestra Morgana. Un día, por razones que no vamos a desvelar aquí, la joven Cereza se interna en el bosque de Ávalon, el hogar de las hadas, donde acaba atrapada, sola y perdida. Por suerte para ella, no tardará en conseguir invocar a su primer demonio, Cheshire, quien posee a su peluche favorito y decide ayudarla a cumplir su objetivo a cambio de que, al final, lo mande de vuelta a Inferno.
        </p>
            
      <div class="card">
        <div class="grid-container">
            <div class="grid-item">
                <img class="ImagenContainer2" src={Imagen2} alt="Girl in a jacket">
            </div>
            <div class="grid-item">
                <p>Esta joven solitaria nació de la unión entre los Lumen, sabios de la luz, y las Brujas de Umbra de la oscuridad. Debido a que las relaciones entre estos dos clanes están estrictamente prohibidas, Cereza es considerada como una chica marginada. Su mayor deseo es fortalecerse para que algún día pueda ayudar a Rosa, su madre encarcelada.</p>
            </div>
        </div>
    </div>
    <p>
        De esta forma, empieza un viaje repleto de aventuras y con un guion muy sencillo, pero que funciona sorprendentemente bien gracias a la peculiar forma en la que se nos narra la historia, como si de un cuento se tratase. Eso sí, su narrativa brilla, sobre todo, por sus dos protagonistas, una improbable y entrañable pareja con personalidades muy opuestas que se se ve obligada a superar sus diferencias para sobrevivir y salir al paso, lo que da pie a un buen número de situaciones interesantes, a riñas constantes y a una evolución muy satisfactoria que ha logrado que les pillemos cariño. Además, la trama está repleta de guiños y detallazos para los fans de la saga, aunque es perfectamente disfrutable por cualquier jugador, independientemente de que haya jugado o no a la trilogía original.
    </p>


    </div>
  </div>


<style>
.sample-section-wrap {
  position: relative;
  background-color: #CE8FA2;
}
.sample-section {
  position: relative;
  max-width: 640px;
  margin-left: auto;
  margin-right: auto;
  padding: 40px;
  background-color: white;
}
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}
.ImagenContainer
{
    width: 250px;
    height: 200px;

}
.ImagenContainer2
{
    width: 125px;
    height: 240px;

}
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto;
  padding: 10px;
}

.grid-item {
  background-color: rgba(255, 255, 255, 0.8);
  padding: 20px;
}
</style>