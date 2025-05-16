<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Helin'e Özel</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #fce4ec, #f3e5f5);
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
      text-align: center;
    }

    h1 {
      font-size: 4em;
      color: #4a004a;
      margin-bottom: 10px;
    }

    .hearts {
      font-size: 3em;
      color: purple; /* Kalplerin rengi */
      animation: float 2s infinite alternate ease-in-out;
    }

    .footer {
      font-size: 1.5em;
      color: #4a004a;
      margin-top: 20px;
      font-weight: bold;
    }

    @keyframes float {
      0% { transform: translateY(0); }
      100% { transform: translateY(-10px); }
    }
  </style>
</head>
<body>
  <h1>HELİN</h1>
  <div class="hearts">♥ ♥ ♥</div>
  <div class="footer">İyi ki varsın</div>
</body>
</html>