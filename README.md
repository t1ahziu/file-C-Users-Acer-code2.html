# file-C-Users-Acer-code2.html
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Giới thiệu bản thân</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #74ebd5, #9face6);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .card {
      background: white;
      width: 350px;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.2);
      text-align: center;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #6c63ff;
      margin-bottom: 15px;
    }

    h1 {
      font-size: 28px;
      color: #333;
      margin-bottom: 10px;
    }

    p {
      color: #666;
      font-size: 15px;
      margin-bottom: 20px;
    }

    .social a {
      display: block;
      text-decoration: none;
      color: white;
      padding: 12px;
      margin: 10px 0;
      border-radius: 10px;
      font-size: 16px;
      transition: 0.3s;
    }

    .facebook {
      background: #1877f2;
    }

    .tiktok {
      background: #000;
    }

    .zalo {
      background: #008fe5;
    }

    .social a:hover {
      transform: scale(1.05);
      opacity: 0.9;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="https://en.shop-t1.gg/web/product/big/202508/1aa18a6a7d45b955a8346d6c64cfcdc3.jpg" alt="Ảnh đại diện" class="avatar" />
    
    <h1>Trần Trọng Nguyên</h1>
    <p>Xin chào! Tôi là Trần Trọng Nguyên
    </p>
    <div class="social">
      <a href="https://www.facebook.com/trantrongnguyen1234/about/?fb_profile_edit_entry_point=%7B%22click_point%22%3A%22edit_profile_button%22%2C%22feature%22%3A%22profile_header%22%7D&id=100078893881121&sk=about" target="_blank" class="facebook">Facebook</a>
      <a href="https://www.tiktok.com/@thi.b00.27d?is_from_webapp=1&sender_device=pc" target="_blank" class="tiktok">TikTok</a>
      <a href="https://zalo.me/0369705860" target="_blank" class="zalo">Zalo</a>
    </div>
  </div>
</body>
</html>
