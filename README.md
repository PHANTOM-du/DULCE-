# DULCE-
Amor 
`html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Dedicatoria Especial</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #ffe6f0, #d0f0ff);
      font-family: 'Segoe UI', sans-serif;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    .mensaje {
      font-size: 2em;
      text-align: center;
      animation: fadeInUp 2s ease-in-out;
      max-width: 80%;
    }

    @keyframes fadeInUp {
      0% {
        opacity: 0;
        transform: translateY(40px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .corazon {
      font-size: 4em;
      animation: latido 1.2s infinite ease-in-out;
      margin-top: 20px;
    }

    @keyframes latido {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.3);
      }
    }
  </style>
</head>
<body>
  <div class="mensaje">
    ✨ Esta dedicatoria es para ti, porque iluminas mi vida como nadie más. 💖
  </div>
  <div class="corazon">❤️</div>

  <!-- Música de fondo -->
  <audio autoplay loop>
    <source src="ruta-de-tu-musica.mp3" type="audio/mp3">
    Tu navegador no soporta audio HTML5.
  </audio>
</body>
</html>
`
