<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Biblioteca Virtual de Tesis y Proyectos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eef2f7;
            margin: 0;
        }

        header {
            background: #1e3a5f;
            color: white;
            text-align: center;
            padding: 20px;
        }

        h1 {
            margin: 0;
        }

        .contenedor {
            padding: 20px;
        }

        .documento {
            background: white;
            padding: 15px;
            margin-bottom: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .documento h2 {
            margin-bottom: 5px;
        }

        iframe {
            width: 100%;
            height: 500px;
            border: none;
            margin-top: 10px;
        }

        .boton {
            display: inline-block;
            margin-top: 10px;
            padding: 8px 12px;
            background: #2b7de9;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>

<body>

<header>
    <h1>📚 Biblioteca Virtual de Tesis y Proyectos</h1>
    <p>Repositorio académico digital</p>
</header>

<div class="contenedor">

    <div class="documento">
        <h2>Tesis: Implementación de Biblioteca Virtual</h2>
        <p>Proyecto enfocado en el uso de tecnologías web para acceso a recursos educativos.</p>

        <!-- DOCUMENTO VISIBLE -->
        <iframe src="tesis1.pdf"></iframe>

        <a href="tesis1.pdf" target="_blank" class="boton">Abrir en pantalla completa</a>
    </div>

    <div class="documento">
        <h2>Proyecto: Recursos Digitales en Educación</h2>
        <p>Estudio sobre el impacto de plataformas virtuales en el aprendizaje.</p>

        <iframe src="proyecto2.pdf"></iframe>

        <a href="proyecto2.pdf" target="_blank" class="boton">Abrir en pantalla completa</a>
    </div>

    <div class="documento">
        <h2>Tesis: Integración de TIC en Bibliotecas</h2>
        <p>Análisis de la transformación de bibliotecas tradicionales a virtuales.</p>

        <iframe src="tesis3.pdf"></iframe>

        <a href="tesis3.pdf" target="_blank" class="boton">Abrir en pantalla completa</a>
    </div>

</div>

</body>
</html>
