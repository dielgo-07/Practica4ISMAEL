EL CINE INDEPENDIENTE QUE TU NECESITAS
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Películas de A24</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        
        header {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        
        .logo {
            max-width: 150px;
            margin-bottom: 10px;
        }
        
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        
        .movies {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 30px;
        }
        
        .movie-card {
            background-color: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: calc(33.333% - 20px);
            transition: transform 0.3s;
        }
        
        .movie-card:hover {
            transform: translateY(-10px);
        }
        
        .movie-poster {
            width: 100%;
            height: 400px;
            object-fit: cover;
        }
        
        .movie-info {
            padding: 20px;
        }
        
        .movie-title {
            margin-top: 0;
            color: #000;
            font-size: 1.5em;
        }
        
        .movie-year {
            color: #666;
            font-weight: bold;
        }
        
        .movie-director {
            margin: 10px 0;
            font-style: italic;
        }
        
        .movie-synopsis {
            line-height: 1.6;
        }
        
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        
        @media (max-width: 900px) {
            .movie-card {
                width: calc(50% - 15px);
            }
        }
        
        @media (max-width: 600px) {
            .movie-card {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0f/A24_%28company%29_logo.svg/1200px-A24_%28company%29_logo.svg.png" alt="Logo A24" class="logo">
        <h1>Películas Destacadas</h1>
    </header>
    
    <div class="container">
        <div class="movies">
            <!-- Película 1: Everything Everywhere All at Once -->
            <div class="movie-card">
                <img src="https://m.media-amazon.com/images/M/MV5BYTdiOTIyZTQtNmQ1OS00NjZlLWIyMTgtYzk5Y2M3ZDVmMDk1XkEyXkFqcGdeQXVyMTAzMDg4NzU0._V1_.jpg" alt="Everything Everywhere All at Once" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Everything Everywhere All at Once</h2>
                    <div class="movie-year">2022</div>
                    <div class="movie-director">Dirigida por Daniel Kwan y Daniel Scheinert</div>
                    <p class="movie-synopsis">Una inmigrante china se ve envuelta en una loca aventura, donde solo ella puede salvar el mundo explorando otros universos que se conectan con las vidas que podría haber llevado.</p>
                </div>
            </div>
            
            <!-- Película 2: Hereditary -->
            <div class="movie-card">
                <img src="https://m.media-amazon.com/images/M/MV5BOTU5MDg3OGItZWQ1Ny00ZGVmLTg2YTUtMzBkYzQ1YWIwZjlhXkEyXkFqcGdeQXVyNTAzMTY4MDA@._V1_.jpg" alt="Hereditary" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Hereditary</h2>
                    <div class="movie-year">2018</div>
                    <div class="movie-director">Dirigida por Ari Aster</div>
                    <p class="movie-synopsis">Después de la muerte de la matriarca secreta de su familia, la familia Graham comienza a desentrañar sus ancestros más oscuros. El destino que ellos heredaron podría ser la perdición de todos.</p>
                </div>
            </div>
            
            <!-- Película 3: Moonlight -->
            <div class="movie-card">
                <img src="https://m.media-amazon.com/images/M/MV5BNzQxNTIyODAxMV5BMl5BanBnXkFtZTgwNzQyMDA3OTE@._V1_.jpg" alt="Moonlight" class="movie-poster">
                <div class="movie-info">
                    <h2 class="movie-title">Moonlight</h2>
                    <div class="movie-year">2016</div>
                    <div class="movie-director">Dirigida por Barry Jenkins</div>
                    <p class="movie-synopsis">Un joven afroamericano lucha por encontrar su lugar en el mundo mientras crece en un vecindario difícil de Miami. Una historia íntima y conmovedora de humanidad y autodescubrimiento.</p>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2023 Página de películas de A24. Todos los derechos reservados.</p>
        <p>Las imágenes y sinopsis son utilizadas con fines educativos.</p>
    </footer>
</body>
</html>
