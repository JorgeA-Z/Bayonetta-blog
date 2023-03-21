<script>
    import NavBar from "../NavBar.svelte";
    import Imagen1 from "../../Images/1.png";
    
    import cereza from "../../Images/Cereza.jpg"
    import Chesire from "../../Images/Cheshire.png"
    import Morgana from "../../Images/Morgana.jpg"

    import arrowF from "../../Images/arrow_forward_FILL0_wght400_GRAD0_opsz48.svg";
    import arrowB from "../../Images/arrow_back_FILL0_wght400_GRAD0_opsz48.svg";

    var index = 0;

    let Personajes = [cereza, Chesire, Morgana];

    let Nombres = ["Cereza", "Cheshire", "Morgana"];

    function Backward()
    {
        index = index - 1;

        if(index < 0)
        {
            index = 2;
        }
    }



    function Foward()
    {
        index = index + 1;

        if(index > 2)
        {
            index = 0;
        }
    }

</script>


<header>
    <NavBar>

    </NavBar>
</header>
      
<div class="sample-section-wrap">
    <div class="sample-section">
        <h1>Personajes</h1>
        <div class="card">
            <div class="grid-container">
                <div class="grid-item">
                    <button on:click={Backward}>
                        <img src={arrowB} alt="">
                    </button>
                </div>
                <div class="grid-item">
                    <h2>{Nombres[index]}</h2>
                    <img id= "carro" class="ImagenContainer" src={Personajes[index]} alt="Girl in a jacket">
                    {#if index == 0}
                    <p>Esta joven solitaria nació de la unión entre los Lumen, sabios de la luz, y las Brujas de Umbra de la oscuridad. Debido a que las relaciones entre estos dos clanes están estrictamente prohibidas, Cereza es considerada como una chica marginada. Su mayor deseo es fortalecerse para que algún día pueda ayudar a Rosa, su madre encarcelada</p>
                    {/if}
                    {#if index == 1}
                    <p>Es un demonio invocado por Cereza en una noche de luna llena, que de algún modo fue canalizado a través de su peluche. A regañadientes, acepta acompañarla hasta que ambos encuentren una manera de enviarlo de nuevo a Inferno.</p>
                    {/if}
                    {#if index == 2}
                    <p>Es una Bruja de Umbra solitaria que lleva una vida ordinaria y alejada del resto del clan, cerca de los confines de Bosque Ávalon. Morgana invitó a Cereza a vivir con ella y, desde entonces, Cereza se convirtió en su aprendiz.                         
                    </p>
                    {/if}
                </div>
                <div class="grid-item">
                    <button on:click={Foward}>
                        <img src={arrowF} alt="">
                    </button>
                </div>
            </div>
        </div>
      
    </div>
  </div>
<style>
    
.sample-section-wrap {
  position: relative;
  background-color: #CEBB8F;
  height: 765px;
}
.sample-section {
  position: relative;
  max-width: 640px;
  margin-left: auto;
  margin-right: auto;
  padding: 40px;
  background-color: white;
  height: 685px;
}
h1
{
    text-align: center; 
}
h2{
    text-align: center;
}
.card {
  background-color: #CEBB8F;
  padding: 20px;
  margin-top: 20px;
}
.ImagenContainer
{
    width: 300px;
    height: 200px;

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
button{
    border: none;
    background-color: #CEBB8F;
    border-radius: 12px

}
</style>