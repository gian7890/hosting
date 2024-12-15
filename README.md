<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #6200ea;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }
        section {
            padding: 20px;
        }
        .imagenes-principales {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        .imagenes-principales img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .imagen-proyecto {
            display: block;
            margin: 0 auto;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a Mi Página Personal</h1>
        <p>Hola, soy Gianfranco Aamir Hermoza Echarri y esta es mi página personal</p>
    </header>
    <section>
        <h2>Sobre Mí</h2>
        <p>Me gusta mucho el futbol, soy hincha del Club Universitario de Deportes y estudio la carrera de Ingeniería de sistemas</p>
        <div class="imagenes-principales">
            <img src="iman/img1.jpg" alt="Imagen 1">
            <img src="iman/img2.jpg" alt="Imagen 2">
        </div>
    </section>
    <section>
        <h2>Mis Proyectos</h2>
        <p>Mis proyectos son terminar mi carrera de manera exitosa y poder ejercerla.</p>
        <img src="iman/img3.jpg" alt="Imagen 3" width="350" height="250" class="imagen-proyecto">
    </section>
    <footer>
        <p>&copy; 2024 Gianfranco Aamir Hermoza Echarri</p>
    </footer>
</body>
</html>
