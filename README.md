<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lizard Flick - Small README</title>
  <meta name="viewport" content="width=400">
  <style>
    @keyframes bgmove {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }
    body {
      font-family: 'Segoe UI', Verdana, Geneva, Tahoma, sans-serif;
      margin: 0;
      background: linear-gradient(90deg, #8fd576, #53fba3, #f3f25b, #f68949, #8fd576);
      background-size: 300% 300%;
      animation: bgmove 5s linear infinite;
      color: #1e3d19;
      min-height: 100vh;
    }
    .container {
      max-width: 330px;
      background: #f8fceccc;
      padding: 16px 12px 12px 12px;
      border-radius: 10px;
      margin: 40px auto;
      box-shadow: 0 2px 18px #b7e68444;
    }
    .heading-animated {
      text-align: center;
      font-size: 1.5em;
      font-weight: bold;
      margin-bottom: 16px;
      padding: 11px 0;
      background: linear-gradient(90deg, #8fd576, #f3f25b, #f68949, #8fd576);
      background-size: 200% 200%;
      border-radius: 8px;
      border: 1.5px solid #8fd576;
      box-shadow: 0 2px 10px #8fd57633;
      color: #1e3d19;
      letter-spacing: 2px;
      animation: bgmove 5s linear infinite;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    ul {
      margin: 6px 0 10px 18px;
      font-size: 0.99em;
    }
    li {
      margin: 3px 0;
    }
    .license {
      background: #eff8ce;
      padding: 4px 10px;
      border-radius: 6px;
      font-size: 0.93em;
      display: inline-block;
      margin-top: 8px;
      margin-bottom: 2px;
    }
    .thanks {
      text-align: center;
      color: #91b944;
      font-size: 0.96em;
      margin-top: 6px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="heading-animated">Lizard Flick</div>
    <ul>
      <li>Fun flicking game!</li>
      <li>Drag/flick your lizard.</li>
      <li>Collect bugs & powerups.</li>
      <li>Simple controls, quick play.</li>
    </ul>
    <div class="license"> GNU License</div>
    <div class="thanks">Flick fast. Be the best lizard!</div>
  </div>
</body>
</html>
