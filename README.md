# Para-ti-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>¿Quieres ser mi novia?</title>
  <style>
    body {
      background: linear-gradient(to bottom, #ffd1dc, #ffe6eb);
      font-family: 'Arial', sans-serif;
      text-align: center;
      padding-top: 80px;
      color: #333;
    }
    h1 {
      font-size: 2.8em;
      color: #d6336c;
    }
    .heart {
      font-size: 4em;
      animation: pulse 1.2s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
    .buttons {
      margin-top: 40px;
    }
    button {
      font-size: 1.3em;
      padding: 12px 30px;
      margin: 10px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    .yes {
      background-color: #ff4b5c;
      color: white;
    }
    .no {
      background-color: #cccccc;
    }
    .photo {
      margin-top: 25px;
      border-radius: 20px;
      width: 280px;
      height: auto;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }
    p {
      font-size: 1.2em;
      margin: 20px;
    }
    audio {
      display: none;
    }
  </style>
</head>
<body>
  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mp3">
    Tu navegador no soporta audio.
  </audio>

  <div class="heart">💖</div>
  <h1>¿Quieres ser mi novia?</h1>
  <p>Desde que te conocí, mi mundo cambió. <br> Hoy quiero dar un paso más contigo...<br><br><strong>Misael ❤️ [Tu nombre]</strong></p>

  <!-- Puedes cambiar la URL de la imagen por una tuya subida a internet -->
  <img src="https://i.imgur.com/zMZ8yFq.jpg" alt="Nuestra foto" class="photo">

  <div class="buttons">
    <button class="yes" onclick="alert('¡Gracias, mi amor! ¡Me haces muy feliz! ❤️')">Sí 💘</button>
    <button class="no" onclick="alert('¿Estás segura? Porque yo ya te elegí a ti 💔')">No 😢</button>
  </div>
</body> 
</html>
