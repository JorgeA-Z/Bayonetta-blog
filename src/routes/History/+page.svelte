<script>
    import NavBar from "../NavBar.svelte";
    import Imagen1 from "../../Images/Sc.jpg";
    import Imagen2 from "../../Images/CR.jpeg";
</script>

<header>
    <NavBar />
</header>

<div class="sample-section-wrap">
    <div class="sample-section">
        <h1>
            ¿Qué pasaría si Bayonetta fuese la protagonista de Alicia en el país
            de las Maravillas?
        </h1>
        <p>
            Si la muy querida y descarada bruja de Umbra se adentrase en lo
            desconocido y afrontase lo imposible a través de la mirada de una
            jóven de corazón puro. No como lo plasmó Disney, ni como lo haría
            Tim Burton. Ni tampoco como la imaginó Lewis Carroll. Ni siquiera al
            estilo PlatinumGames. La respuesta tiene nombre propio: Bayonetta
            Origins: Cereza and the Lost Demon, y el resultado es uno de los
            caramelitos más dulces y disfrutables de Nintendo Switch. Los
            creadores de algunos de los hack'n slash más potentes jamás hechos
            le dan un giro completo a su estrella abanderada. No para
            recordarnos quién es Bayonetta o lo que puede hacer, sino para
            enamorar a sus fans y aquellos que desconocen al personaje a través
            de la historia jamás contada de cómo una simple niña acabó siendo la
            bruja más poderosa de los videojuegos. Tomando prestada, con mucho
            acierto, la estética y la magia propia de los cuentos de hadas.
        </p>
        <div class="card">
            <div class="grid-container">
                <div class="grid-item">
                    <p>
                        Una historia que Bayonetta Origins: Cereza and the Lost
                        Demon no aborda a través de esa acción a destajo marca
                        de la casa, sino en clave de aventura. Un viaje
                        emocional, de crecimiento y de superación. Con sus
                        tramos divertidos y sus partes melancólicas, como
                        prácticamente cualquier cuento de hadas. Siendo, entre
                        otras muchas cosas, una aventura realmente exquisita de
                        principio a fin.
                    </p>
                </div>
                <div class="grid-item">
                    <img
                        class="ImagenContainer"
                        src={Imagen1}
                        alt="Girl in a jacket"
                    />
                </div>
            </div>
        </div>

        <p>
            Eso no quiere decir ni que el viaje de Cereza, nuestra protagonista,
            sea un paseo, ni que esté carente de acción, magia y esos épicos
            encontronazos con jefazos finales. Las hadas que nos saldrán al paso
            no son como las de las fábulas: son crueles, violentas y mezquinas.
            Son un verdadero peligro. Y, no lo vamos a negar, si las hadas no
            fuesen así, la dulce aprendiz de bruja llamada Cereza jamás habría
            llegado a ser Bayonetta. Sin embargo, lo verdaderamente interesante
            de Bayonetta Origins: Cereza and the Lost Demon no es lo que Cereza
            es o lo que está destinada a ser. Sino su motivación de cara a
            emprender la aventura: ayudar a un demonio a regresar a un infierno.
            Recuperando esa temática recurrente de la saga en la que se
            cuestiona lo que consideramos bueno y la naturaleza del mal. Con su
            misterio, su fantasía y ese puntito tan característico de locura.
            Logrando que esa PlatinumGames que se desvive por los detalles y el
            cariño hacia sus propios personajes vuelva a brillar. Una suma de
            aciertos que, de manera irremediable, nos llevan a responder a la
            primera pregunta de paso obligado: qué se le ha perdido a una joven
            aprendiz de bruja en el peligrosísimo bosque de las hadas.
        </p>

        <div class="card">
            <div class="grid-container">
                <div class="grid-item">
                    <img
                        class="ImagenContainer"
                        src={Imagen2}
                        alt="Girl in a jacket"
                    />
                </div>
                <div class="grid-item">
                    <p>
                        PlatinumGames cambia completamente de registro con
                        Bayonetta Origins: Cereza and the Lost Demon, y lo hacen
                        conservando su estilo y todo aquello con lo que nos
                        fascinó en el pasado.  Aventura sí, y con mayúsculas. El desarrollo del juego transcurre en
                        el bosque de Ávalon, el cual es un enorme y muy colorido mapeado que
                        pide ser descubierto sorbito a sorbito. 
                    </p>
                </div>
            </div>
        </div>
        <p>
            Con montones de secretos
            que, de manera genuina, nos invitan a dirigirnos en la dirección
            opuesta al curso de la historia para ver si encontramos algo. Y lo
            mejor es que, por lo general, casi siempre suele haber algo. Ávalon
            es un entorno de juego enorme que se abre ante nosotros como si
            fuese un metroidvania, de modo que conforme progresamos vamos
            adquiriendo habilidades que le dan una nueva capa de interés a
            aquellos sitios por los que ya hemos pasado. Invitándonos de manera
            proactiva llegar a lo profundo del bosque y, desde ahí, fomentamos
            que redescubramos cada trocito de mapeado mientras somos testigos de
            cómo una joven con sus propios ideales acaba convirtiéndose en la
            bruja más descarada de los videojuegos
        </p>
    </div>
</div>

<style>
    .sample-section-wrap {
        position: relative;
        background-color: #C2CE8F;
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
    .ImagenContainer {
        width: 250px;
        height: 200px;
    }
    .ImagenContainer2 {
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
