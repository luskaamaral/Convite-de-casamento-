
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lucas & Deniene - Convite de Casamento</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Roboto&display=swap');

    * { box-sizing: border-box; }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      overflow-x: hidden;
    }

    body {
      font-family: 'Roboto', sans-serif;
      color: #001f3f;
      background-image: url('fundo-casamento.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }

    .envelope {
      width: 320px;
      height: 200px;
      background-color: #001f3f;
      position: relative;
      transform-style: preserve-3d;
      perspective: 1000px;
      border-radius: 8px;
      box-shadow: 0 0 25px rgba(0, 31, 63, 0.5);
      animation: openEnvelope 4s ease-out forwards;
      z-index: 2;
      transition: opacity 0.5s ease-out;
    }

    .flap {
      position: absolute;
      width: 100%;
      height: 100%;
      background-color: #001f3f;
      transform-origin: top;
      animation: flapOpen 4s ease-in-out forwards;
      z-index: 3;
      border-radius: 8px;
    }

    .seal {
      width: 40px;
      height: 40px;
      background-color: #c0392b;
      border-radius: 50%;
      position: absolute;
      top: 80px;
      left: calc(50% - 20px);
      z-index: 4;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 1.5em;
      color: white;
      box-shadow: 0 0 8px rgba(0,0,0,0.3);
      animation: fadeOutSeal 1s ease-in forwards;
      animation-delay: 1.5s;
    }

    @keyframes flapOpen {
      0% { transform: rotateX(0deg); }
      100% { transform: rotateX(-120deg); }
    }

    @keyframes openEnvelope {
      0% { transform: scale(1); }
      100% { transform: scale(1) translateY(-100px); }
    }

    @keyframes fadeOutSeal {
      0% { opacity: 1; }
      100% { opacity: 0; transform: scale(0.5); }
    }

    .container {
      opacity: 0;
      transform: translateY(50px);
      animation: showContent 1.5s ease-out 4s forwards;
      width: 600px;
      max-width: 90%;
      background-color: rgba(255, 255, 255, 0.95);
      padding: 40px 30px;
      border: 2px solid #001f3f;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      position: absolute;
      text-align: center;
      z-index: 1;
    }

    @keyframes showContent {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .monogram {
      font-family: 'Playfair Display', serif;
      font-size: 2em;
      color: #001f3f;
      margin-bottom: 10px;
      letter-spacing: 2px;
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5em;
      margin-bottom: 0.2em;
    }

    h2 {
      font-weight: normal;
      font-size: 1.2em;
      color: #333;
    }

    .message {
      font-style: italic;
      color: #444;
      margin: 25px 0;
    }

    .info {
      font-size: 1.1em;
      margin: 30px 0;
      color: #001f3f;
    }

    .rsvp-button {
      display: inline-block;
      padding: 12px 24px;
      font-size: 1em;
      background-color: #001f3f;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      transition: background 0.3s;
    }

    .rsvp-button:hover {
      background-color: #003366;
    }

    .footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #555;
    }

    .music-control {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #003366;
      color: white;
      padding: 12px 16px;
      border-radius: 30px;
      font-size: 16px;
      cursor: pointer;
      z-index: 10;
    }

    .countdown {
      font-size: 1.2em;
      margin-top: 20px;
      color: #003366;
    }
  </style>
</head>
<body>
  <audio id="openSound" src="https://app.filemail.com/d/rzwmuohatucwyvj" preload="auto"></audio>
  <audio id="bgMusic" src="https://app.filemail.com/d/qtvbfoedywftyes" loop preload="auto" muted></audio>

  <div class="music-control" onclick="toggleMusic()">Música: ▶️</div>

  <div class="envelope" id="envelope">
    <div class="flap"></div>
    <div class="seal">❤</div>
  </div>

  <div class="container">
    <div class="monogram">L & D</div>
    <h1>Lucas & Deniene</h1>
    <h2>Convidam você para um dia inesquecível</h2>
    <p class="message">"O amor é paciente, o amor é bondoso... jamais acaba."<br><em>1 Coríntios 13:4-8</em></p>
    <div class="info">
      <p><strong>Data:</strong> 07 de Junho de 2025</p>
      <p><strong>Hora:</strong> 19h</p>
      <p><strong>Local:</strong> Igreja Presbiteriana, Nova Ponte - MG</p>
    </div>
    <div class="countdown" id="countdown"></div>
    <a class="rsvp-button" href="https://nysyj9aq.forms.app/confirmacao-de-presenca-casamento" target="_blank">
      Confirmar Presença
    </a>
    <div class="footer">
      Aguardamos com alegria sua presença neste momento especial!
    </div>
  </div>

  <script>
    window.onload = function () {
      const openSound = document.getElementById("openSound");
      const bgMusic = document.getElementById("bgMusic");
      const envelope = document.getElementById("envelope");

      openSound.play();

      setTimeout(() => {
        envelope.style.opacity = 0;
        envelope.style.zIndex = -1;
      }, 3200);

      setTimeout(() => {
        bgMusic.volume = 0.3;
        bgMusic.play();
        document.querySelector('.music-control').textContent = 'Música: ⏸️';
      }, 4000);

      startCountdown();
    };

    function toggleMusic() {
      const music = document.getElementById("bgMusic");
      const button = document.querySelector(".music-control");
      if (music.paused) {
        music.play();
        button.textContent = 'Música: ⏸️';
      } else {
        music.pause();
        button.textContent = 'Música: ▶️';
      }
    }

    function startCountdown() {
      const targetDate = new Date("2025-06-07T19:00:00").getTime();
      const countdown = document.getElementById("countdown");

      setInterval(() => {
        const now = new Date().getTime();
        const distance = targetDate - now;

        if (distance <= 0) {
          countdown.innerHTML = "Chegou o grande dia!";
          return;
        }

        const days = Math.floor(distance / (1000 * 60 * 60 * 24));
        const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        const seconds = Math.floor((distance % (1000 * 60)) / 1000);

        countdown.innerHTML = `Faltam ${days} dias, ${hours}h ${minutes}m ${seconds}s`;
      }, 1000);
    }
  </script>
</body>
</html>
