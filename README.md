<!DOCTYPE html>
<html>
<head>
  <title>System Update</title>
  <style>
    body {
      background-color: #111;
      color: #0f0;
      font-family: monospace;
      text-align: center;
      padding-top: 100px;
    }
    .loader {
      font-size: 24px;
      animation: blink 1s infinite;
    }
    @keyframes blink {
      0% { opacity: 1; }
      50% { opacity: 0.3; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>
  <h1>🔄 Installing Critical System Update...</h1>
  <div class="loader">Loading ██████████ 99%</div>
  <p>Please do not turn off your phone.</p>

  <script>
    let dots = 0;
    setInterval(() => {
      dots = (dots + 1) % 4;
      document.querySelector('.loader').textContent = "Loading ██████████ 99%" + ".".repeat(dots);
    }, 1000);
  </script>
</body>
</html>
