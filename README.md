<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday!</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      text-align: center;
      color: #333;
    }
    .container {
      padding: 40px 20px;
    }
    h1 {
      font-size: 3em;
      color: #ff4081;
    }
    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 20px auto;
    }
    .card {
      background: white;
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      display: inline-block;
    }
    .btn {
      margin-top: 20px;
      padding: 12px 25px;
      border: none;
      border-radius: 25px;
      background: #ff4081;
      color: white;
      font-size: 1em;
      cursor: pointer;
    }
    .btn:hover {
      background: #e73370;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <h1>Happy Birthday, Sis!</h1>
      <p>
        You are not just my little sister, you are my best friend, my happiness, and my biggest blessing.
        May your life be filled with love, laughter, and endless joy.
      </p>
      <p>
        Stay the same cute, crazy, and amazing person you are. I am always there for you!
      </p>
      <button class="btn" onclick="showMessage()">Click for Surprise</button>
      <p id="hiddenMessage" style="display:none; margin-top:20px; font-weight:bold; color:#ff4081;">
        I love you so much! Happy Birthday once again!
      </p>
    </div>
  </div>  <script>
    function showMessage() {
      document.getElementById('hiddenMessage').style.display = 'block';
    }
  </script></body>
</html>
