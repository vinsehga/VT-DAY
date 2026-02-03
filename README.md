<!DOCTYPE html>
<html>
<head>
  <title>For You ❤️</title>
  <style>
    body {
      background-color: #ffe6e6;
      text-align: center;
      font-family: Arial, sans-serif;
      margin-top: 100px;
    }
    button {
      font-size: 20px;
      padding: 10px 25px;
      margin: 20px;
    }
    #no {
      position: absolute;
    }
  </style>
</head>

<body>
  <h1>Will you be my Valentine? 💖</h1>

  <button onclick="alert('Yayyy ❤️ I love you 😘')">
    Yes
  </button>

  <button id="no" onmouseover="moveNo()">
    No
  </button>

  <script>
    function moveNo() {
      const btn = document.getElementById("no");
      btn.style.left = Math.random() * 80 + "vw";
      btn.style.top = Math.random() * 80 + "vh";
    }
  </script>
</body>
</html>
