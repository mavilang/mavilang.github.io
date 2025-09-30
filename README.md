<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Exclusive Tech Preview</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>🚀 Welcome to Project Quantum</h1>
    <p>You've been invited to preview the next-gen AI breakthrough. Click below to access the demo:</p>
    <button onclick="rickRoll()">Launch Demo</button>
  </div>
  <script src="script.js"></script>
</body>
</html>
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #121212;
  color: #f0f0f0;
  text-align: center;
  padding: 50px;
}

.container {
  max-width: 600px;
  margin: auto;
  background: #1e1e1e;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 0 15px rgba(255,255,255,0.1);
}

button {
  padding: 12px 24px;
  font-size: 16px;
  background-color: #00bcd4;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
function rickRoll() {
  window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
}
