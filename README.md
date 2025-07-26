<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ASRUL</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #000;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      font-family: 'Arial', sans-serif;
    }

    h1 {
      font-size: 5em;
      font-weight: bold;
      text-transform: uppercase;
      background: linear-gradient(270deg, red, orange, yellow, green, blue, indigo, violet, red);
      background-size: 1400% 1400%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: rgbFlow 5s ease infinite;
    }

    @keyframes rgbFlow {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
  </style>
</head>
<body>
  <h1>ASRUL</h1>
</body>
</html>
