<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joyeux Anniversaire Graciella</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4e1d2;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #6a1b9a;
            color: white;
            padding: 2rem;
        }
        h1 {
            font-size: 3rem;
            margin: 0;
            font-family: 'Georgia', serif;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem;
            gap: 1rem;
        }
        .gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #6a1b9a;
            color: white;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Joyeux Anniversaire Graciella !</h1>
    </header>
    <div class="gallery">
        <img src="images/balloons_flowers_graciella.jpg" alt="Ballons et Fleurs">
        <img src="images/canvas_painting_joyeux_anniversaire.jpg" alt="Tableau Joyeux Anniversaire">
        <img src="images/balloons_flowers_no_character.jpg" alt="Fleurs et Ballons">
        <img src="images/canvas_floral_graciella.jpg" alt="Tableau Floral Graciella">
    </div>
    <footer>
        <p>© 2025 - Créé avec amour pour Graciella</p>
    </footer>
</body>
</html>
