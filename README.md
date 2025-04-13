
  <title>Twelve</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <div class="left-circle">🍷</div>
    <div class="right-circle">Notes AI</div>
    <h1>?</h1>What emotion do you feel?/>
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
body {
  font-family: Arial, sans-serif;
  text-align: center;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
}

.container {
  position: relative;
  padding: 20px;
}

.left-circle, .right-circle {
  position: absolute;
  top: 20px;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  background-color: #333;
  color: white;
}

.left-circle {
  left: 20px;
}

.right-circle {
  right: 20px;
}

h1 {
  margin-top: 100px;
  font-size: 24px;
}

.images {
  display: flex;
  justify-content: center;
  margin-top: 20px;
}

.image-container {
  margin: 0 20px;
}

.image-container img {
  width: 200px;
  height: 200px;
  object-fit: cover;
}

.image-container button {
  display: block;
  margin: 10px auto;
  padding: 5px 15px;
  font-size: 16px;
  cursor: pointer;
}

.image-container p {
  font-size: 16px;
  margin-top: 5px;
}<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
