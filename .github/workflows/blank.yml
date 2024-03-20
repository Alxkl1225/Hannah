<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pide perdón a Hannah</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      text-align: center;
    }
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .button {
      font-size: 20px;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.15);
    }
    .button-green {
      background-color: #4caf50;
      color: white;
    }
    .button-red {
      background-color: #f44336;
      color: white;
    }
    .button-red.small {
      width: 100px;
    }
    .confetti {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100vh;
      z-index: 1;
    }
    .confetti-piece {
      position: absolute;
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background-color: #f44336;
      animation: confetti-fall 2s linear infinite;
    }
    @keyframes confetti-fall {
      0% {
        top: 0;
      }
      100% {
        top: 100vh;
      }
    }
    .message {
      font-size: 30px;
      font-weight: bold;
      margin-top: 20px;
    }
    .heart {
      color: #f44336;
      font-size: 40px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div id="buttons">
      <button class="button button-green" id="yes">Sí</button>
      <button class="button button-red" id="no">No</button>
    </div>
    <div id="confetti" class="confetti">
      <div class="confetti-piece"></div>
      <div class="confetti-piece"></div>
      <div class="confetti-piece"></div>
      <div class="confetti-piece"></div>
      <div class="confetti-piece"></div>
      </div>
    <div id="message" class="message">
      Gracias por perdonarmeeee nanaaaa 
    </div>
  </div>
  <script>
    const yesButton = document.getElementById("yes");
    const noButton = document.getElementById("no");
    const confetti = document.getElementById("confetti");
    const message = document.getElementById("message");
    
    let buttonClicks = 0;
    
    yesButton.addEventListener("click", () => {
      confetti.classList.add("active");
      message.classList.add("active");
      setTimeout(() => {
        window.location.href = "https://www.google.com/"; // Redirigir a otra página
      }, 3000);
    });
    
    noButton.addEventListener("click", () => {
      buttonClicks++;
      if (buttonClicks === 1) {
        noButton.classList.add("small");
        noButton.textContent = "Perdóname Hannah, yo te amo ";
      } else {
        // Redirigir a otra página
        window.location.href = "https://www.youtube.com/";
      }
    });
  </script>
</body>
</html
