
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Indian Astrology Plugin</title>
  <link rel="stylesheet" href="dist/css/astrology-plugin.css" />
  <style>
    body {
      font-family: 'Noto Serif', serif;
      background: linear-gradient(to bottom right, #fef6e4, #fdf0d5);
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Mandala_art.svg/1024px-Mandala_art.svg.png');
      background-repeat: no-repeat;
      background-position: center;
      background-size: contain;
      color: #3e2f23;
      padding: 2rem;
    }
    header {
      text-align: center;
      padding-bottom: 1rem;
      border-bottom: 2px solid #d4a373;
    }
    h1 {
      font-size: 2.5rem;
      color: #6c584c;
    }
    .plugin-container {
      margin-top: 2rem;
      background: #fffef9;
      border: 1px solid #e2c275;
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    footer {
      margin-top: 3rem;
      text-align: center;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>हिंदु ज्योतिष - Indian Astrology</h1>
    <p>Ancient wisdom powered by modern tools</p>
  </header>  <div class="plugin-container" id="astrology-chart">
    <!-- The plugin will render chart here -->
  </div>  <footer>
    &copy; 2025 Indian Panchang Project
  </footer>  <script src="dist/js/astrology-plugin.js"></script>  <script src="dist/js/chart-visualizer.js"></script>  <script>
    // Initialize the plugin (assuming plugin exposes a global init method)
    document.addEventListener("DOMContentLoaded", function () {
      AstrologyPlugin.init({
        containerId: "astrology-chart",
        language: "en", // Change to "hi" or "ne" for Hindi or Nepali
        theme: "traditional",
      });
    });
  </script></body>
</html>
