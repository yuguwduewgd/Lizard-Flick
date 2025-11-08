<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lizard Flick - README</title>
  <meta name="viewport" content="width=550">
  <style>
    @keyframes movingBg {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }
    body {
      font-family: 'Segoe UI', Verdana, Geneva, Tahoma, sans-serif;
      margin: 0;
      background: linear-gradient(135deg, #efffd6 0%, #b7e684 100%);
      color: #345d20;
      min-height: 100vh;
      font-size: 14px;
      padding: 0 2vw;
    }
    .heading-animated {
      text-align: center;
      font-size: 1.55em;
      font-weight: bold;
      margin-top: 26px;
      margin-bottom: 14px;
      padding: 8px 0;
      background: linear-gradient(90deg, #81c07d, #e1ea6e, #f7b66c, #81c07d);
      background-size: 200% 200%;
      color: #2c4a10;
      border-radius: 11px;
      border: 1px solid #81c07d;
      box-shadow: 0 2px 10px #bfb;
      letter-spacing: 2px;
      animation: movingBg 3s linear infinite;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-family: 'Segoe UI', Verdana, Geneva, Tahoma, sans-serif;
    }
    .container {
      max-width: 430px;
      margin: 0 auto;
      background: #f8fceccc;
      border-radius: 10px;
      box-shadow: 0 1px 7px #bddbbd60;
      padding: 18px 17px 13px 17px;
      margin-bottom: 24px;
    }
    h2 {
      color: #20983a;
      font-size: 1em;
      margin-bottom: 5px;
      margin-top: 16px;
    }
    ul, ol {
      margin-top: 4px;
      margin-bottom: 10px;
      padding-left: 17px;
    }
    li {
      font-size: 0.98em;
      padding: 1px 0;
    }
    .code-block {
      background: #eefbe0;
      color: #32530d;
      font-family: 'Fira Mono', 'Consolas', 'Menlo', monospace;
      font-size: 0.95em;
      border-radius: 7px;
      margin-bottom: 11px;
      margin-top: 4px;
      padding: 8px;
      border: 1px solid #cbeeb3;
      overflow-x: auto;
    }
    .license {
      background: #fbffeccc;
      padding: 5px 9px;
      border-radius: 7px;
      margin-bottom: 8px;
      font-weight: bold;
      font-size: 0.98em;
    }
    .thanks {
      color: #98b944;
      font-style: italic;
      margin-top: 8px;
      font-size: 0.98em;
      text-align: center;
    }
    @media (max-width: 500px) {
      .container { max-width: 96vw; padding: 4vw; }
    }
  </style>
</head>
<body>
  <div class="heading-animated">🦎 Lizard Flick</div>
  <div class="container">
    <h2>About</h2>
    <p><b>Lizard Flick</b> is a quick, fun flicking game! Flick the lizard, dodge obstacles, and collect bugs for points.</p>

    <h2>Features</h2>
    <ul>
      <li>Easy flick controls (touch, mouse, trackpad)</li>
      <li>Collect insects &amp; powerups</li>
      <li>Unlock lizard skins and upgrades</li>
      <li>Compete for high scores</li>
    </ul>

    <h2>Play (HTML Demo)</h2>
    <div class="code-block">
&lt;canvas id="gameCanvas" width="320" height="240"&gt;&lt;/canvas&gt;<br>
&lt;script src="game.js"&gt;&lt;/script&gt;
    </div>

    <h2>How to Run</h2>
    <ol>
      <li>Clone: <span class="code-block">git clone https://github.com/&lt;your-username&gt;/lizard-flick.git</span></li>
      <li>Open <b>index.html</b> in a browser</li>
    </ol>
    <h2>License</h2>
    <div class="license">MIT</div>
    <div class="thanks">
      Flick fast, be the best lizard!<br>
      <span style="font-size:0.92em;">Graphics: <a href="https://opengameart.org/">OpenGameArt</a></span>
    </div>
  </div>
</body>
</html>
