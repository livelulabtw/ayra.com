<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>PARA AUDREY</title>
  </head>
  <style>
    body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;

      background-image: url("img.png");
      background-position: center center;
      background-size: cover;
    }

    .hearth {
      height: 150px;
      width: 150px;
      background-color: red;
      position: relative;
      transform: rotate(45deg);
      box-shadow: -20px 20px 150px #f20404;
      animation: palpitar 0.5s linear infinite alternate;
    }
    .contenido {
      position: fixed;
      margin-bottom: 50px;
      text-align: center;
    }

    h1 {
      color: white;
    }
    h2 {
      color: white;
    }

    @keyframes palpitar {
      0% {
        transform: rotate(45deg) scale(1.1);
      }
      80% {
        transform: rotate(45deg) scale(1);
      }
      100% {
        transform: rotate(45deg) scale(0.8);
      }
    }

    .hearth::before {
      content: "";
      position: absolute;
      height: 150px;
      width: 150px;
      background-color: red;
      right: 50%;
      border-radius: 50%;
      box-shadow: 20px 20px 150px #f20404;
    }

    .hearth::after {
      content: "";
      position: absolute;
      height: 150px;
      width: 150px;
      background-color: red;
      top: -50%;
      border-radius: 50%;
      box-shadow: 20px 20px 150px #f20404;
    }
  </style>
  <body>
    <div class="hearth"></div>
    <div class="contenido">
      <h1>La mejor estudiante , streamer y mujer</h1>
      <h2>Ayraflores</h2>
    </div>
  </body>
</html>
