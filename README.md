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
    <title>Hiệu Ứng Hình và Căn Chữ</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9; /* Nền trang nhạt */
        }

        .container {
            display: flex; /* Bố trí hình và chữ ngang hàng */
            justify-content: space-between; /* Đẩy hình sang trái và chữ sang phải */
            align-items: center; /* Căn giữa các phần tử theo chiều dọc */
            padding: 20px;
        }

        .image-container {
            position: relative; /* Đặt vị trí tương đối để tạo hiệu ứng */
            width: 200px; /* Kích thước cố định cho hình */
            height: 200px;
            overflow: hidden; /* Ẩn phần hình vượt ngoài khung */
        }

        .image-container img {
            position: absolute; /* Đặt vị trí hình ảnh */
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            transition: opacity 1.5s ease-in-out; /* Hiệu ứng mờ dần */
        }

        .image-container img:first-child {
            opacity: 1; /* Hình đầu tiên hiển thị */
            z-index: 1;
        }

        .image-container img:last-child {
            opacity: 0; /* Hình thứ hai ẩn ban đầu */
            z-index: 0;
        }

        /* Hiệu ứng chuyển đổi giữa các hình */
        .image-container:hover img:first-child {
            opacity: 0;
            z-index: 0;
        }

        .image-container:hover img:last-child {
            opacity: 1;
            z-index: 1;
        }

        .text {
            max-width: 50%; /* Giới hạn chiều rộng phần chữ */
            text-align: right; /* Căn lề phải */
            color: #007bff; /* Màu chữ xanh dương */
            line-height: 1.6; /* Tăng khoảng cách giữa các dòng */
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Phần hình ảnh -->
        <div class="image-container">
            <img src="1.jpg" alt="Hình 1">
            <img src="z6098482597170_f4cf723791d4f9219190285715e5820a.jpg" alt="Hình 2">
        </div>
        <!-- Phần chữ -->
        <div class="text">
            <h1>Đôi lời giới thiệu</h1>
            <p> Xin chào các bạn, mình tên là Hồng Ngọc. Sở thích của mình là xem phim, nghe nhạc và ngủ</p>
        </div>
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
