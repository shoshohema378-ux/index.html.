# index.html.
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>صدقة جارية على روح بشرى مختار جمعة</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #f0f8ff;
      padding-top: 60px;
    }
    h1 {
      color: #2c3e50;
    }
    p {
      font-size: 20px;
      color: #34495e;
    }
    button {
      font-size: 24px;
      padding: 15px 40px;
      margin-top: 20px;
      cursor: pointer;
      border-radius: 10px;
      border: none;
      background-color: #3498db;
      color: white;
    }
    .count {
      font-size: 40px;
      margin: 20px 0;
      color: #e74c3c;
    }
  </style>
</head>
<body>

  <h1>صدقة جارية على روح بشرى مختار جمعة</h1>
  <p>سبحان الله وبحمده</p>

  <div class="count" id="count">0</div>

  <button onclick="tasbeeh()">سبّح</button>

  <script>
    let count = 0;
    function tasbeeh() {
      count++;
      document.getElementById("count").innerText = count;
    }
  </script>

</body>
</html>
