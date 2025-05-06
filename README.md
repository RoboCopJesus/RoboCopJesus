<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Student Tools Dashboard</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #1e1e1e;
      color: #fff;
      padding: 1rem;
      text-align: center;
      font-size: 1.5rem;
    }
    .dashboard {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
      gap: 1rem;
      padding: 1rem;
    }
    .card {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }
    .card-header {
      background-color: #ececec;
      padding: 0.75rem;
      font-weight: bold;
      border-bottom: 1px solid #ddd;
    }
    iframe {
      width: 100%;
      height: 400px;
      border: none;
    }
    @media (max-width: 500px) {
      iframe {
        height: 300px;
      }
    }
  </style>
</head>
<body>
  <header>Student Tools Dashboard</header>
  <div class="dashboard">
    <div class="card">
      <div class="card-header">Physics Sim (Drive Mad)</div>
      <iframe src="https://poki.com/en/g/drive-mad"></iframe>
    </div>
    <div class="card">
      <div class="card-header">Historical Combat Sim (Gladihoppers)</div>
      <iframe src="https://poki.com/en/g/gladihoppers"></iframe>
    </div>
    <div class="card">
      <div class="card-header">Reaction Speed Tester (Shell Shockers)</div>
      <iframe src="https://shellshock.io"></iframe>
    </div>
    <div class="card">
      <div class="card-header">Logic Puzzle (2048)</div>
      <iframe src="https://play2048.co"></iframe>
    </div>
    <div class="card">
      <div class="card-header">Balance & Focus Game (Slope)</div>
      <iframe src="https://slopegame.io/fullscreen.html"></iframe>
    </div>
  </div>
</body>
</html>
