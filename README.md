<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chúc Mừng Giải Đặc Biệt</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      text-align: center;
      padding: 50px;
    }
    .gift-box {
      width: 300px;
      height: 300px;
      background-color: #ff80ab;
      color: white;
      font-size: 18px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      cursor: pointer;
      box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.2);
      transition: all 0.3s;
    }
    .gift-box:hover {
      transform: scale(1.1);
    }
    .message {
      display: none;
      font-size: 24px;
      font-weight: bold;
      color: #ff4081;
    }
  </style>
</head>
<body>

  <h1>Chào Anh Yêu, Đây Là Giải Đặc Biệt Dành Cho Anh!</h1>
  <p>Nhấn vào hộp quà để nhận quà bất ngờ!</p>

  <div class="gift-box" onclick="openGift()">
    <p>Hộp Quà!</p>
  </div>

  <div class="message" id="message">
    <p>Chúc Mừng Anh! Giải Đặc Biệt Chính Là... Em Luôn Ở Đây Và Tin Vào Anh! ❤️</p>
  </div>

  <script>
    function openGift() {
      document.querySelector('.gift-box').style.display = 'none';
      document.getElementById('message').style.display = 'block';
    }
  </script>

</body>
</html>
