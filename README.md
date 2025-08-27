<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>I LOVE YOU</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: black;
      overflow: hidden;
      font-family: Arial, sans-serif;
    }
    h1 {
      font-size: 4em;
      font-weight: bold;
      background: linear-gradient(45deg, #ffcc00, #ff0066, #ff0000);
      -webkit-background-clip: text;
      color: transparent;
      animation: glow 2s infinite alternate, pulse 2s infinite;
    }
    @keyframes glow {
      from { text-shadow: 0 0 10px #ff0066, 0 0 20px #ff0000; }
      to { text-shadow: 0 0 25px #ffcc00, 0 0 50px #ff0066; }
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
  </style>
</head>
<body>
  <h1>I LOVE YOU ❤️</h1>
</body>
</html>
