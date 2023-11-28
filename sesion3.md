<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

* 4 Imagenes
* 2 Videos
* 4 Audios
* 2 Inline Frame

Utiliza encabezados para títulos en cada elemento (```<h1>...<h6>```).

Crea una descripción para cada elemento utilizando párrafos (``<p>``).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

* Usa ``<strong>`` para resaltar texto importante.
* Utiliza ``<br>`` para insertar saltos de línea si es necesario.
* Agrega ``<span>`` para aplicar estilos específicos a porciones de texto.
* Emplea ``<i>`` para enfatizar o dar énfasis a palabras o frases.
* Utiliza ``<u>`` para subrayar texto cuando sea necesario.
* Considera el uso de ``<div>`` para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

# Plantilla Inicial

````html

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #500606;
            color: rgba(255, 255, 255, 0.587);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(0, 255, 60);
        }

        h1 {
            color: rgb(255, 0, 0);
        }

        h3 {
            color: rgb(0, 0, 0);
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <div>

        <section>
            <h1>Imágenes</h1>
            <h2>Naturaleza</h2>
            <h3>Sakura</h3>

            <p>El cerezo florece durante la primavera. En Japón se realiza <strong>el festival del hanami<span
                        style="color: rgb(247, 0, 255);">(花見?) .</span></strong>
                en su honor puesto
                que es su flor más significativa<br> (pero no la oficial, que es el crisantemo); durante este los
                familiares
                y
                amigos se reúnen en los parques con cerezos bajo la sombra de los<br> mismos y, a modo de pícnic,
                comparten
                alimentos mientras celebran la aparición de las flores. El curso académico de Japón empieza justo<br>
                después
                del final de la festividad.<a href="https://es.wikipedia.org/wiki/Sakura_(cerezo)" target="_blank">Mas
                    informacion...</a></p>
            <img src="sakura.jpg" alt="arbol de sakura" width="250">


            <h3>Tormenta</h3>
            <p>Una tormenta es un fenómeno meteorológico asociado al desarrollo vertical de <a
                    href="https://es.wikipedia.org/wiki/Nubosidad" target="_blank"><u><i>nubosidad</i></u></a></p>
            acompañado de descargas eléctricas o rayos y, habitualmente, precipitación y rachas de viento intensas en
            superficie.
            Las descargas eléctricas<br>pueden ser nube-nube, nube-tierra y nube-ionosfera.
            Aunque científicamente se define como tormenta a aquella nube capaz de producir un trueno<br>o rayo
            audible, también se denominan tormentas en general a los fenómenos atmosféricos violentos que, en la
            superficie de la tierra están<br> asociados a lluvia, hielo, granizo, electricidad, nieve o vientos fuertes,
            que pueden transportar partículas en suspensión como la tormenta de<br> arena o incluso pequeños objetos o
            seres vivos.<a href="https://es.wikipedia.org/wiki/Tormenta" target="_blank">Mas
                informacion...</a></p>
            <img src="tormenta.jpg" alt="Tormenta" width="450">




            <h3>Noche</h3>

            <p>Noche (del latín: Nox, noctis) es el periodo durante el cual una parte de la Tierra, por acción de la
                rotación, deja de recibir la luz solar y, por ende, permanece<br>en oscuridad. Está comprendido entre
                atardecer del Sol y amanecer del día siguiente. Sigue por lo tanto a la tarde y antecede a la madrugada.

                Una actividad<br> de la noche se le conoce como actividad nocturna.<a
                    href="https://es.wikipedia.org/wiki/Noche" target="_blank">Mas
                    informacion...</a></p>
            </p>
            <img src="noche.jpg" alt="noche" width="250">

            <h3>volcan</h3>

            Un volcán (del nombre del dios mitológico romano Vulcano) es una estructura geológica por la que emerge el
            magma que se divide en lava y gases provenientes<br> del interior de la Tierra. El ascenso del magma ocurre
            en
            episodios de actividad violenta denominados erupciones, que pueden variar en intensidad, duración y<br>
            frecuencia, desde suaves corrientes de lava hasta explosiones extremadamente destructivas. En ocasiones, los
            volcanes adquieren una forma cónica por la<br> acumulación de material de erupciones anteriores. En la
            cumbre se
            encuentra su cráter o caldera.<a href="https://es.wikipedia.org/wiki/Volc%C3%A1n" target="_blank">Mas
                informacion...</a></p>
            <img src="volcan.jpg" alt="volcan" width="450">

        </section>

    </div>
    <div>

        <section>
            <!-- video -->
            <h2>Naturaleza</h2>
            <h3>Noche</h3>
            <p>Entre los hebreos, griegos y algunas otras naciones la noche se dividía en cuatro partes que se llamaban
                velas o guardias vigiliae, custodiae porque durante ellas velaban tanto los que estaban de guardia
                militar
                como los pastores que guardaban los rebaños y duraban unas tres horas cada una. La primera comenzaba
                luego
                de puesto el sol y se llamaba tarde, vespere, y duraba más o menos hasta las nueve; la segunda, desde
                esta
                hora a las doce y se llamaba media noche; la tercera, de las doce a las tres y solían llamarla canto del
                gallo y la cuarta, desde las tres hasta las seis o salida del sol a la cual llamaban mañana, mane o
                custodia
                matutina.<a href="https://es.wikipedia.org/wiki/Noche" target="_blank">Mas
                    informacion...</a>></p>
            <video src="noche.mp4" controls width="450"></video>
            <h3>Sakura</h3>
            <p>En Japón, los árboles de cerezo son denominados sakura. Las recepciones solemnes, conocidas como Hanami,
                generalmente son excursiones en donde las personas se juntan para reflexionar sobre la naturaleza
                efímera de la vida y la mortalidad, debido a que la vida útil de las flores de cerezos es corta. La
                cultura samurái de Japón también admiraba mucho a esta flor ya que se consideraba que los samuráis (al
                igual que las flores de los cerezos) tenían una vida corta y además porque se creía que la flor
                representaba las gotas de sangre derramadas en sus batallas. En la actualidad, la flor representa
                inocencia, la sencillez, la belleza de la naturaleza y el renacimiento que trae la primavera.<a
                    href="https://es.wikipedia.org/wiki/Sakura_(cerezo)" target="_blank">Mas
                    informacion...</a>></p>
            <video src="sakura.mp4" controls width="450"></video>

        </section>
    </div>

    <section>
        <h2>Musica</h2>
        <h3>Metal</h3>
        <p>El heavy metal, o simplemente metal (pronunciado en ocasiones como métal)​ —en español traducido como
            «metal pesado»—, es un subgénero musical que nació a finales de los años sesenta y principios de los setenta
            tanto en el Reino Unido como en los Estados Unidos, cuyos orígenes provienen del hard rock, blues rock y del
            rock psicodélico. Se caracteriza principalmente por sus guitarras fuertes y distorsionadas, ritmos
            enfáticos, los sonidos del bajo y la batería son más densos de lo habitual y la voz es generalmente aguda o
            gutural.</p>
            <audio src="metal.mp3" controls></audio>


    </section>

    <section>
        <h2>Naturaleza</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Granda Zea Jeronimo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>

````

# Semántica y Estructura de la Plantilla

El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

``<!DOCTYPE html>``: Esto define el tipo de documento como HTML5.

``<html>``: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

``<head>:`` Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque ``<style>`` para agregar reglas de estilo CSS.

``<title>``: Establece el título de la página en la pestaña del navegador.

``<style>``: Contiene reglas de estilo CSS que afectan al diseño y la apariencia del sitio.

``<body>``: Aquí se coloca el contenido principal visible de la página.

``<header>``: Sección de encabezado que contiene el título principal y un subtítulo.

``<h1> y <h3>``: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

``<section>``: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

``<h2>``: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

``<p>``: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

``<footer>``: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea ``<br>`` para separar las líneas de texto.

En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

* La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.
* El encabezado (``<header>``) tiene un fondo oscuro, texto blanco y un espacio de relleno.
* Cada sección (``<section>``) tiene un borde, un espacio de relleno y un margen inferior.
* Los encabezados de nivel 1 y 3 están centrados.
* Los encabezados de nivel 2 (``<h2>``) tienen color azul.
* El pie de página (``<footer>``) tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.

Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido. El estilo CSS proporciona una apariencia visual coherente y agradable.
