<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

# Actividad: Creando mi primer sitio web

Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

## Las páginas del sitio serán:

* Index o página de inicio
* Acerca
* Contacto

# index.html

```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="Content-Type">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primer Sitio</title>
</head>

<body>
    <header>
        <h1>Pgina Principal</h1>
        <h2>Actividad 1</h2>

        <nav>
            <a href="pagina2.html">acerca</a>
            <a href="pagina3.html">contacto</a>
        </nav>

        <main>
            <p>Bienvenidos a mi sitio sobre la actividad 1</p>
            <p>Aqui encontrarn infomacion esta primera actividad</p>
        </main>

        <footer>
            <p>copyrigh 2023 - Jero Granda</p>
            <p>0409jeronimo@gmai.com</p>
        </footer>



        
</body>

</html>

```

# about.html


```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>actividad 1</title>
</head>

<body>
    <header>
        <h1>Sobre nosotros</h1>
    </header>

    <nav>
        <a href="index.html">Principal</a>
        <a href="pagina3.html">contacto</a>
    </nav>

    <section>
        <h2>Historia</h2>
        <p>fundada en 2004</p>

        <article>
            <h3>>mision y vision</h3>
            <p>la mision es</p>
        </article>

    </section>

    <footer>
        <p>copyrigh 2023 - Jero Granda</p>
        <p>0409jeronimo@gmai.com</p>
    </footer>

</body>

</html>

```

# contact.html

```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad 1</title>
</head>

<body>
    <header>
        <h1>contacto</h1>
    </header>

    <nav>
        <a href="index.html">Principal</a>
        <a href="pagina2.html">acerca</a>
    </nav>

    <main>

        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="Nombre"><br>

            <label for="email">Email:</label>
            <input type="email" id="email"><br>

            <label for="mensaje">Mensaje</label>
            <textarea id="mensaje"></textarea>

            <input type="submit" value="enviar">
        </form>

    </main>

    <footer>
        <p>copyrigh 2023 - Jero Granda</p>
        <p>0409jeronimo@gmai.com</p>
    </footer>
</body>

</html>

```