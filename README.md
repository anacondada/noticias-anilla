# noticias-anilla

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Página web de noticias de Anilla</title>
    <style>
        /* Estilos para el banner */
        .banner {
            background-color: #eaeaea;
            padding: 10px 0;
            text-align: center;
        }
        .title {
            font-size: 36px;
            margin: 0;
        }

        /* Estilos para el cuerpo de la página */
        body {
            background-color: #ffe58f;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .header-text {
            font-size: 28px;
            color: #555;
            margin: 10px 0;
        }
        .news-container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .news {
            width: 80%;
            max-width: 800px;
            margin: 20px 0;
            border: 1px solid #ccc;
            padding: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .news-image {
            max-width: 100%;
            height: auto;
        }
        .news-title {
            font-size: 20px;
            margin-bottom: 5px;
        }
        .news-text {
            font-size: 14px;
        }
        .footer {
            text-align: center;
            background-color: #eaeaea;
            padding: 10px 0;
            margin-top: 20px;
        }
        .small-text {
            font-size: 12px;
            color: #777;
            margin: 0;
        }
    </style>
</head>
<body>
    <div class="banner">
        <h1 class="title">✨ Página web de noticias de Anilla ✨</h1>
    </div>
    <section class="description">
        <p class="header-text">¡Bienvenidos a la página de noticias no oficial de Anilla! Aquí encontrarás las últimas novedades y curiosidades.</p>
    </section>
    <div class="news-container">

        <div class="news">
            <h2 class="news-title">La película de Barbie: ¡Una maravilla del cine!</h2>
            <img src="Imagen1.jpg" alt="Imagen 1" class="news-image">
            <p class="news-text">Descubre cómo la película de Barbie está dejando a todos impresionados con su mensaje y calidad cinematográfica.</p>
        </div>
        <div class="news">
            <h2 class="news-title">La canción "Siberia" de Natalia Lacunza es un temazo</h2>
            <img src="Imagen2.jpg" alt="Imagen 2" class="news-image">
            <p class="news-text">Natalia Lacunza nos sorprende con su última canción "Siberia". ¿Quieres saber por qué todos la están escuchando?</p>
        </div>
        <div class="news">
            <h2 class="news-title">Fiestas tradicionales de Oviedo: ¡Un viaje cultural en España!</h2>
            <img src="Imagen3.jpg" alt="Imagen 3" class="news-image">
            <p class="news-text">Sumérgete en la cultura española a través de las fiestas tradicionales de Oviedo. ¡Descubre la riqueza de estas celebraciones!</p>
        </div>
        <div class="news">
            <h2 class="news-title">Incendio asolador en Maui, Hawaii: ¿Qué ha sucedido?</h2>
            <img src="Imagen4.jpg" alt="Imagen 4" class="news-image">
            <p class="news-text">Un incendio devastador afecta a la hermosa isla de Maui en Hawaii. Conoce los detalles de este desastre y cómo está afectando a la comunidad local.</p>
        </div>
        <div class="news">
            <h2 class="news-title">"Culturalicio & Culturnews": La mejor web de arte y cultura</h2>
            <img src="Imagen5.jpg" alt="Imagen 5" class="news-image">
            <p class="news-text">Descubre por qué "Culturalicio & Culturnews" es la referencia en divulgación de arte y cultura. Explora sus contenidos y sumérgete en un mundo de conocimiento.</p>
        </div>
    </div>
    <section class="footer">
        <p class="small-text">Madrid, 2023</p>
    </section>
</body>
</html>
