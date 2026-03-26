<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Web App</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
<header class="header">
    <div class="logo">
        <img src="img/html5-logo.png" alt="Logo HTML5">
        <div>
            <h1>HTML5</h1>
            <p>Base del desarrollo web moderno</p>
        </div>
    </div>
    <nav class="nav">
        <a href="#inicio">Inicio</a>
        <a href="#que-es">¿Qué es?</a>
        <a href="#estructura">Estructura</a>
        <a href="#etiquetas">Etiquetas</a>
        <a href="#semantica">Semántica</a>
        <a href="#formularios">Formularios</a>
        <a href="#multimedia">Multimedia</a>
        <a href="#conclusion">Conclusión</a>
    </nav>
</header>

<main>
<section id="inicio" class="hero">
    <div class="hero-texto">
        <span class="badge">Tema de la práctica</span>
        <h2>Aprendiendo HTML5</h2>
        <p>
            Esta página está dedicada a explicar qué es HTML5, su estructura, sus etiquetas
            y su importancia en el desarrollo web. El contenido será completado por el alumno.
        </p>
        <a href="#que-es" class="btn">Comenzar</a>
    </div>
    <div class="hero-imagen">
    </div>
</section>

<section id="que-es" class="seccion">
    <article class="card">
        <h2>¿Qué es HTML5?</h2>
        <img src="img/html5-logo.png" alt="Logo HTML5">
        <p>
            Aquí el alumno debe explicar qué es HTML5, para qué sirve y por qué es importante
            en la creación de páginas web.
        </p>
    </article>
</section>

<section id="estructura" class="seccion">
    <article class="card">
        <h2>Estructura básica de HTML5</h2>
        <img src="img/estructura.png" alt="Estructura HTML5">
        <div class="codigo">
            &lt;!DOCTYPE html&gt;
            &lt;html&gt;
            &lt;head&gt;
            &lt;title&gt;Mi página&lt;/title&gt;
            &lt;/head&gt;
            &lt;body&gt;
            &lt;/body&gt;
            &lt;/html&gt;
        </div>
        <p>
            En esta parte el alumno debe explicar la función de doctype, html, head y body.
        </p>
    </article>
</section>

<section id="etiquetas" class="seccion">
    <article class="card">
        <h2>Etiquetas principales</h2>
        <img src="img/etiquetas.png" alt="Etiquetas HTML5">
        <div class="grid">
            <div class="mini-card">
                <h3>h1 - h6</h3>
                <p>Aquí el alumno explica los títulos.</p>
            </div>
            <div class="mini-card">
                <h3>p</h3>
                <p>Aquí el alumno explica los párrafos.</p>
            </div>
            <div class="mini-card">
                <h3>img</h3>
                <p>Aquí el alumno explica las imágenes.</p>
            </div>
            <div class="mini-card">
                <h3>a</h3>
                <p>Aquí el alumno explica los enlaces.</p>
            </div>
            <div class="mini-card">
                <h3>button</h3>
                <p>Aquí el alumno explica los botones.</p>
            </div>
            <div class="mini-card">
                <h3>ul / ol / li</h3>
                <p>Aquí el alumno explica las listas.</p>
            </div>
        </div>
    </article>
</section>

<section id="semantica" class="seccion">
    <article class="card">
        <h2>HTML5 semántico</h2>
        <img src="img/semantica.png" alt="HTML5 semántico">
        <div class="grid">
            <div class="mini-card">
                <h3>header</h3>
                <p>Espacio para que el alumno describa el encabezado.</p>
            </div>
            <div class="mini-card">
                <h3>nav</h3>
                <p>Espacio para que el alumno describa la navegación.</p>
            </div>
            <div class="mini-card">
                <h3>main</h3>
                <p>Espacio para que el alumno describa el contenido principal.</p>
            </div>
            <div class="mini-card">
                <h3>section</h3>
                <p>Espacio para que el alumno describa las secciones.</p>
            </div>
            <div class="mini-card">
                <h3>article</h3>
                <p>Espacio para que el alumno describa los artículos.</p>
            </div>
            <div class="mini-card">
                <h3>footer</h3>
                <p>El pie de página, representado por la etiqueta <footer>, es una sección importante en una página web que generalmente contiene información complementaria o de cierre, como derechos de autor, enlaces legales, datos de contacto o créditos.</p>
            </div>
        </div>
    </article>
</section>

<section id="formularios" class="seccion">
    <article class="card">
        <h2>Formularios en HTML5</h2>
        <img src="img/formularios.png" alt="Formularios HTML5">
        <p>
            Aquí el alumno debe investigar y explicar qué son los formularios y cuáles son
            algunas etiquetas y elementos como form, label, input, textarea, select y button.
        </p>

        <form class="demo-form">
            <label for="nombre">Nombre</label>
            <input type="text" id="nombre" placeholder="Ejemplo">

            <label for="correo">Correo</label>
            <input type="email" id="correo" placeholder="ejemplo@email.com">

            <label for="comentario">Comentario</label>
            <textarea id="comentario" rows="4" placeholder="Escribe aquí..."></textarea>

            <button type="button">Enviar</button>
        </form>
    </article>
</section>

<section id="multimedia" class="seccion">
    <article class="card">
        <h2>Multimedia en HTML5</h2>
        <p>
            En esta sección el alumno puede investigar y explicar cómo HTML5 permite trabajar
            con imágenes, audio y video.
        </p>

        <div class="grid">
            <div class="mini-card">
                <h3>Imágenes</h3>
                <p>Explicar la etiqueta img y sus atributos.</p>
            </div>
            <div class="mini-card">
                <h3>Audio</h3>
                <p>    La etiqueta <video> en HTML5 es un elemento que permite incrustar contenido de video directamente en una página web sin necesidad de plugins externos como Flash. <div class="mini-card">
                <h3>Video</h3>
                <p>La etiqueta <video> en HTML5 es un elemento que permite incrustar contenido de video directamente en una página web sin necesidad de plugins externos como Flash.</p>
            </div>
            <div class="mini-card">
                <h3>Accesibilidad</h3>
                <p>El atributo alt proporciona una descripción textual de la imagen para personas con discapacidades visuales que utilizan lectores de pantalla.</p>
            </div>
        </div>
    </article>
</section>

<section id="conclusion" class="seccion">
    <article class="card">
        <h2>Conclusión</h2>
        <p>
            Aquí el alumno debe redactar una conclusión sobre la importancia de HTML5 en el
            desarrollo web.HTML5 es fundamental en el desarrollo web moderno porque proporciona una estructura clara y semántica para las páginas web, mejorando la accesibilidad y la compatibilidad entre diferentes dispositivos y navegadores. 
        </p>
        <p><strong>Alumno:</strong> Brandon Yair Rivera Ortega</p>
        <p><strong>Materia:</strong> Desarrollo de Aplicaciones Móviles</p>
    </article>
</section>
</main>

<footer class="footer">
    <p>Práctica HTML5 - Submódulo 2</p>
</footer>

<script src="js/app.js"></script>
</body>
</html>
