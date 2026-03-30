<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Fondo de Fútbol</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            font-family: Arial, sans-serif;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            background-color: black;
        }

        h1 {
            background: rgba(0,0,0,0.5);
            padding: 20px;
            border-radius: 10px;
        }
    </style>
</head>
<body>

<h1>⚽ Bienvenido al mundo del fútbol ⚽</h1>

<script>
    const imagenes = [
        "https://images.unsplash.com/photo-1517927033932-b3d18e61fb3a",
        "https://images.unsplash.com/photo-1508098682722-e99c643e7f0b",
        "https://images.unsplash.com/photo-1518609878373-06d740f60d8b",
        "https://images.unsplash.com/photo-1522778119026-d647f0596c20",
        "https://images.unsplash.com/photo-1505842465776-3a8e8f5f1d74"
    ];

    const random = Math.floor(Math.random() * imagenes.length);
    document.body.style.backgroundImage = `url('${imagenes[random]}')`;
</script>

</body>
</html>
