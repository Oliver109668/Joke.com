# Joke.com
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Visit Joke.com for hilarious jokes, funny videos, and more!">
  <meta name="keywords" content="jokes, funny videos, comedy, humor, joke site">
  <meta name="author" content="Joke.com Team">
  <meta name="robots" content="index, follow">
  <title>Joke.com</title>
  <link rel="icon" href="content://media/external/downloads/14381" type="image/png">
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(45deg, black, black, black, white, white);
      background-size: 400% 400%;
      animation: bwAnimation 20s ease infinite;
      color: white;
      overflow: hidden;
    }

    @keyframes bwAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .container {
      text-align: center;
      padding: 20px;
      z-index: 1;
    }

    h1 {
      font-size: 4em;
      font-weight: bold;
      margin: 0 0 20px;
      background: -webkit-linear-gradient(white, black);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: textGlow 2s ease-in-out infinite alternate;
    }

    @keyframes textGlow {
      from { text-shadow: 0 0 10px white, 0 0 20px black; }
      to { text-shadow: 0 0 20px black 0 0 30px white; }
    }

    .button {
      display: inline-block;
      margin-top: 20px;
      padding: 15px 40px;
      font-size: 1.5em;
      color: black;
      background: linear-gradient(45deg, black, gray, white, black);
      border: none;
      border-radius: 50px;
      cursor: pointer;
      text-transform: uppercase;
      letter-spacing: 2px;
      text-decoration: none;
      transition: transform 0.3s ease, box-shadow 0.3s ease, color 0.3s ease;
      animation: buttonGlow 2.5s infinite ease alternate;
    }

    .button:hover {
      transform: scale(1.1);
      box-shadow: 0px 10px 20px rgba(255, 255, 255, 0.8);
      color: white;
      background: black;
    }

    @keyframes buttonGlow {
      from { box-shadow: 0 0 10px white; }
      to { box-shadow: 0 0 20px black; }
    }

    .button:active {
      transform: scale(0.95);
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>𝙳𝚘𝚗'𝚝 𝙲𝚕𝚒𝚌𝚔 𝙼𝚎!</h1>
    <a href="https://www.youtube.com/embed/HIcSWuKMwOw" class="button" target="_blank">Click Me!</a>
    <a href="http://NJYcSw6RhuiIIvV:Cdh5rsuNsQe0Bsu@localhost:29213/storage/emulated/0/1012/system.html" class="button" target="_blank">Share!</a>
 
  </div>
</body>
</html>
