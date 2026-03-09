<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>un pequeño mensaje</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #0f172a, #1e293b, #334155);
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .box {
      max-width: 700px;
      width: 100%;
      background: rgba(255, 255, 255, 0.08);
      border: 1px solid rgba(255, 255, 255, 0.12);
      backdrop-filter: blur(10px);
      padding: 40px 25px;
      border-radius: 24px;
      box-shadow: 0 10px 35px rgba(0, 0, 0, 0.35);
      animation: aparecer 1.2s ease;
    }

    h1 {
      font-size: 2.2rem;
      color: #ff7aa2;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.2rem;
      line-height: 1.8;
      color: #f8fafc;
    }

    .emoji {
      font-size: 1.5rem;
      margin-top: 18px;
    }

    @keyframes aparecer {
      from {
        opacity: 0;
        transform: translateY(20px) scale(0.98);
      }
      to {
        opacity: 1;
        transform: translateY(0) scale(1);
      }
    }

    @media (max-width: 600px) {
      .box {
        padding: 30px 20px;
      }

      h1 {
        font-size: 1.8rem;
      }

      p {
        font-size: 1.05rem;
      }
    }
  </style>
</head>
<body>
  <div class="box">
    <h1>hola 😊</h1>
    <p>
      no sé qué traerá el futuro,<br>
      pero me gusta el presente<br>
      cuando estoy hablando contigo.
    </p>
    <div class="emoji">💙✨</div>
  </div>
</body>
</html>
