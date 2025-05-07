# VEKTOR-CORPORATION-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vektor Corporation - Confidencial</title>
  <style>
    body {
      background-color: #000;
      color: #00ff9f;
      font-family: 'Courier New', monospace;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 30px;
    }

    header img {
      width: 120px;
    }

    main {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      display: none;
      animation: fadeIn 2s forwards;
    }

    .intro {
      text-align: center;
      font-size: 1.2em;
      padding: 50px 20px;
      color: #0f0;
      animation: typing 3s steps(50) 1;
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid #0f0;
      font-family: monospace;
    }

    button {
      background: #ff0000;
      border: none;
      color: white;
      font-size: 1.1em;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      margin: 20px auto;
      display: block;
    }

    .hidden-info {
      display: none;
      margin-top: 20px;
      background: #111;
      padding: 15px;
      border: 1px solid #444;
      border-radius: 10px;
    }

    footer {
      text-align: center;
      font-size: 0.8em;
      color: #888;
      margin-top: 40px;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <audio autoplay>
    <source src="https://www.myinstants.com/media/sounds/system-failure.mp3" type="audio/mpeg">
    Tu navegador no soporta el audio.
  </audio>

  <header>
    <img src="logo.png" alt="Logo Vektor Corporation">
  </header>

  <div class="intro">Estableciendo conexión con Vektor Corporation...</div>

  <main id="mainContent">
    <h1>Vektor Corporation - Archivo Clasificado</h1>
    <p>El gobierno de los Estados Unidos ha estado colaborando en secreto con <strong>Vektor Corporation</strong>, una empresa dedicada al desarrollo de armamento nuclear y nanotecnología médica.</p>
    <p>Esta alianza permanece no revelada al público. Vektor planea instalar laboratorios en múltiples países y formar alianzas globales con empresas de armamento tecnológico.</p>
    <p>Vektor también mantiene conexión directa con el <strong>Área 51</strong>, intercambiando recursos y tecnología avanzada.</p>

    <button onclick="revealInfo()">Acceder a archivos clasificados</button>
    <div class="hidden-info" id="hiddenInfo">
      <p><strong>ADVERTENCIA:</strong> No se han detectado instalaciones oficiales aún. Su red de expansión podría convertirla en una de las corporaciones más poderosas del mundo.</p>
      <p>Monitoreo satelital indica patrones inusuales cerca de antiguas bases militares.</p>
    </div>
  </main>

  <footer>
    Información clasificada - Fuente anónima | Vektor Corp. 2025
  </footer>

  <script>
    // Mostrar contenido tras animación
    setTimeout(() => {
      document.querySelector('.intro').style.display = 'none';
      document.getElementById('mainContent').style.display = 'block';
    }, 3500);

    // Mostrar info secreta
    function revealInfo() {
      const info = document.getElementById('hiddenInfo');
      info.style.display = 'block';
    }
  </script>

</body>
</html>
