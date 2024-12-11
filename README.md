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
    <h1 class="floating-text">NGUYỄN HỒNG NGỌC XIN CHÀO</h1>
  </div>
</body>




<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trang Web Của Tôi</title>
  <link href="https://fonts.googleapis.com/css2?family=Lora&display=swap" rel="stylesheet"> <!-- Thêm link font Lora -->
  <style>
    body {
      font-family: 'Lora', serif; /* Sử dụng font Lora */
      margin: 0;
      padding: 0;
      background-color: #f8d7d7; /* Màu nền nhẹ */
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 20px;
    }

    .intro {
      font-size: 24px;
      color: #003366; /* Màu xanh dương đậm */
      font-weight: normal;
      text-align: center;
      margin-bottom: 40px;
    }

    .section {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
      margin-bottom: 40px;
      flex-wrap: wrap;
    }

    /* Nội dung chính đầu tiên */
    .first-section {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      width: 100%;
    }

    .first-section .image {
      flex: 1;
      text-align: center;
    }

    .first-section .text-container {
      flex: 1;
      text-align: left;
    }

    .first-section .title {
      font-size: 28px;
      font-weight: bold;
      color: red;
      text-align: left;
    }

    .first-section .text {
      font-size: 20px;
      font-weight: normal;
      color: #003366; /* Màu xanh dương đậm */
    }

    /* Nội dung chính thứ 2 */
    .second-section {
      display: flex;
      justify-content: flex-end;
      align-items: center;
      width: 100%;
    }

    .second-section .image {
      flex: 1;
      text-align: center;
    }

    .second-section .text-container {
      flex: 1;
      text-align: right;
    }

    .second-section .title {
      font-size: 28px;
      font-weight: bold;
      color: red;
      text-align: right;
    }

    .second-section .text {
      font-size: 20px;
      font-weight: normal;
      color: #003366; /* Màu xanh dương đậm */
    }

    /* Căn chỉnh ảnh cho khổ bằng nhau */
    .first-section .image img, .second-section .image img {
      width: 80%;
      height: auto;
      border-radius: 8px;
      display: none;
      animation: changeImage 16s infinite; /* Mỗi chu kỳ 16s cho 4 ảnh */
    }

    /* Chuyển đổi ảnh với hiệu ứng mờ dần */
    @keyframes changeImage {
      0% { opacity: 0; }
      25% { opacity: 1; }
      50% { opacity: 0; }
      75% { opacity: 1; }
      100% { opacity: 0; }
    }

    /* Đảm bảo các ảnh trong phần 1 thay đổi theo chu kỳ */
    .first-section .image img:nth-child(1) { animation-delay: 0s; }
    .first-section .image img:nth-child(2) { animation-delay: 4s; }
    .first-section .image img:nth-child(3) { animation-delay: 8s; }
    .first-section .image img:nth-child(4) { animation-delay: 12s; }

    /* Đảm bảo các ảnh trong phần 2 thay đổi theo chu kỳ */
    .second-section .image img:nth-child(1) { animation-delay: 0s; }
    .second-section .image img:nth-child(2) { animation-delay: 4s; }
    .second-section .image img:nth-child(3) { animation-delay: 8s; }
    .second-section .image img:nth-child(4) { animation-delay: 12s; }
  </style>
</head>
<body>

  <div class="container">
    <!-- Dòng giới thiệu khái quát bản thân -->
    <div class="intro">
      Xin chào, mình là Hồng Ngọc. Đây là trang web cá nhân của mình, nơi mình chia sẻ một chút về bản thân và những điều mình yêu thích.
    </div>

    <!-- Nội dung chính đầu tiên -->
    <div class="section first-section">
      <div class="image">
        <img src="1.jpg" alt="Ảnh 1">
        <img src="2.jpg" alt="Ảnh 2">
        <img src="3.jpg" alt="Ảnh 3">
        <img src="z6098482597170_f4cf723791d4f9219190285715e5820a.jpg" alt="Ảnh 4">
      </div>
      <div class="text-container">
        <div class="title">Sở Thích Của Tôi</div>
        <div class="text">Xin chào các bạn, mình tên là Hồng Ngọc. Sở thích của mình là xem phim, nghe nhạc và ngủ</div>
      </div>
    </div>

    <!-- Nội dung chính thứ 2 -->
    <div class="section second-section">
      <div class="text-container">
        <div class="title">Những Điều Tôi Thích Làm</div>
        <div class="text">Chữ bên trái, ảnh bên phải</div>
      </div>
      <div class="image">
        <img src="1.jpg" alt="Ảnh 1">
        <img src="2.jpg" alt="Ảnh 2">
        <img src="3.jpg" alt="Ảnh 3">
        <img src="z6098482597170_f4cf723791d4f9219190285715e5820a.jpg" alt="Ảnh 4">
      </div>
    </div>





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
