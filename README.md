<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trang Web Của Tôi</title>
  <style>
    body {
      background-color: #FAD0C4; /* Màu hồng nhạt */
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Pano đầu trang */
    .header {
      background-color: #000000; /* Màu đen */
      color: white;
      text-align: center;
      padding: 20px;
    }

    /* Chữ với hiệu ứng bay lơ lửng */
    .floating-text {
      font-size: 36px;
      font-weight: bold;
      background-image: linear-gradient(45deg, red, orange, yellow, green, cyan, blue, violet);
      background-size: 200% 200%;
      color: transparent;
      background-clip: text;
      display: inline-block;
      animation: rainbow 3s linear infinite, float 2s ease-in-out infinite;
    }

    /* Hiệu ứng chữ 7 màu chuyển động */
    @keyframes rainbow {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }

    /* Hiệu ứng bay lơ lửng */
    @keyframes float {
      0% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
      100% {
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="header">
    <h1 class="floating-text">Chào Mừng Đến Với Trang Web Của Tôi</h1>
  </div>
</body>
</html>

<h2>Profile các bạn nhóm 5</h2>
<ul>
<li> Xin chào các bạn, mình tên là Hồng Ngọc. Sở thích của mình là xem phim, nghe nhạc và ngủ
<image src="z6098482597170_f4cf723791d4f9219190285715e5820a.jpg">
<li> Thông tin cá nhân
    <ol>
    <li>Họ và tên: Nguyễn Hồng Ngọc</li>
    <li>Trường trung học phổ thông Chuyên Bến Tre</li>
    <li>Lớp: 12 Lý</li>
    <li>Giới tính: Nữ</li> 
    <li>Cân nặng: 41kg</li>
    <li>Chiều cao: 1,54m</li>
    </ol>
</li>
<li> Nguyện vọng tương lai 
    <ol>
    <li>Khối thi là Khoa học tự nhiên </li>
    <li>Nguyện vọng 1 là Đại học Ngoại Thương</li>
    </ol>
</li>
