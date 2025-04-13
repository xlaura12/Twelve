<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Twelve</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <div class="left-circle">🍷</div>
    <div class="right-circle">Notes AI</div>
    <h1>Which image do you prefer?</h1>
    <div class="images">
      <div class="image-container">
        <img id="image1" src="image1.jpg" alt="Image 1">
        <button onclick="vote('image1')">Vote</button>
        <p id="score1">Score: 0</p>
      </div>
      <div class="image-container">
        <img id="image2" src="image2.jpg" alt="Image 2">
        <button onclick="vote('image2')">Vote</button>
        <p id="score2">Score: 0</p>
      </div>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html># Twelve
