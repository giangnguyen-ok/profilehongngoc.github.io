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


<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trang Web Của Tôi</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      margin: 20px;
    }

    .section {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
      margin-bottom: 20px;
    }

    /* Chữ bên phải, ảnh bên trái */
    .left-image-right-text {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 100%;
    }

    .left-image-right-text .text {
      flex: 1;
      text-align: right;
      font-size: 24px;
      font-weight: bold;
      color: #003366; /* Màu xanh dương đậm */
    }

    .left-image-right-text .image {
      flex: 1;
      text-align: left;
      max-width: 50%;
    }

    .left-image-right-text img {
      width: 100%;
      height: auto;
      transition: opacity 1s ease;
    }

    /* Chữ bên trái, ảnh bên phải */
    .right-image-left-text {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 100%;
    }

    .right-image-left-text .text {
      flex: 1;
      text-align: left;
      font-size: 24px;
      font-weight: bold;
      color: #003366; /* Màu xanh dương đậm */
    }

    .right-image-left-text .image {
      flex: 1;
      text-align: right;
      max-width: 50%;
    }

    .right-image-left-text img {
      width: 100%;
      height: auto;
      transition: opacity 1s ease;
    }

    /* Chuyển đổi ảnh */
    @keyframes changeImage {
      0% { opacity: 0; }
      25% { opacity: 1; }
      50% { opacity: 0; }
      75% { opacity: 1; }
      100% { opacity: 0; }
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="section left-image-right-text">
      <div class="image">
        <img src="1.jpg" id="image1" alt="Ảnh 1">
        <img src="2.jpg" id="image2" alt="Ảnh 2" style="display: none;">
        <img src="3.jpg" id="image3" alt="Ảnh 3" style="display: none;">
        <img src="z6098482597170_f4cf723791d4f9219190285715e5820a.jpg" id="image4" alt="Ảnh 4" style="display: none;">
      </div>
      <div class="text">Xin chào các bạn, mình tên là Hồng Ngọc. Sở thích của mình là xem phim, nghe nhạc và ngủ</div>
    </div>

    <div class="section right-image-left-text">
      <div class="text">Chữ bên trái, ảnh bên phải</div>
      <div class="image">
        <img src="1.jpg" id="image5" alt="Ảnh 1">
        <img src="2.jpg" id="image6" alt="Ảnh 2" style="display: none;">
        <img src="3.jpg" id="image7" alt="Ảnh 3" style="display: none;">
        <img src="z6098482597170_f4cf723791d4f9219190285715e5820a.jpg" id="image8" alt="Ảnh 4" style="display: none;">
      </div>
    </div>
  </div>

  <script>
    let imageIndex1 = 0;
    let imageIndex2 = 0;
    const images1 = ["#image1", "#image2", "#image3", "#image4"];
    const images2 = ["#image5", "#image6", "#image7", "#image8"];

    function changeImages() {
      // Thay đổi ảnh bên trái và bên phải
      images1.forEach((img, index) => {
        document.querySelector(img).style.display = (index === imageIndex1) ? "block" : "none";
      });
      images2.forEach((img, index) => {
        document.querySelector(img).style.display = (index === imageIndex2) ? "block" : "none";
      });

      imageIndex1 = (imageIndex1 + 1) % 4;
      imageIndex2 = (imageIndex2 + 1) % 4;
    }

    // Chuyển đổi ảnh mỗi giây
    setInterval(changeImages, 1000);
  </script>

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
