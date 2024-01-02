- 👋 Hi, I’m @Imabdulbasith
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Imabdulbasith/Imabdulbasith is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ask Her Out</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
      margin: 50px;
    }

    h1 {
      color: #3498db;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #3498db;
      color: #fff;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <h1>Would you like to go out with me?</h1>
  <button onclick="displayMessage()">Yes</button>
  <button id="noButton" onclick="moveNoButton()">No</button>

  <script>
    function displayMessage() {
      alert("Great! I'll plan something special. 😊");
    }

    function moveNoButton() {
      var button = document.getElementById("noButton");
      var maxX = window.innerWidth - button.clientWidth;
      var maxY = window.innerHeight - button.clientHeight;

      var newX = Math.random() * maxX;
      var newY = Math.random() * maxY;

      button.style.position = "absolute";
      button.style.left = newX + "px";
      button.style.top = newY + "px";
    }
  </script>

</body>
</html>
