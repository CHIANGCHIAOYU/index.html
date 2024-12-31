<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>個人部落格</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTWvotngTrc08TvgIhtTP3n1tJVysh_IDO3Rg&s') no-repeat center center fixed;
      background-size: cover;
    }

    /* 頂部導航 */
    header {
      background: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      background: #444;
    }

    nav a {
      color: #fff;
      padding: 0.5rem 1rem;
      text-decoration: none;
    }

    nav a:hover {
      background: #555;
    }

    /* 主頁橫幅或介紹區 */
    .hero {
      background: url<img src="https://drive.google.com/file/d/13WIDpWQsQkEzI2ogYXR5YYUyU9PEb6pf/view?usp=sharing" alt="這是一張圖片"> no-repeat center center/cover;
      color: white;
      height: 300px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .hero h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    .hero p {
      font-size: 1.2rem;
    }

    /* 最新文章區 */
    .latest-posts {
      padding: 2rem;
    }

    .latest-posts h2 {
      text-align: center;
    }

    .post {
      margin-bottom: 1.5rem;
    }

    .post h3 {
      margin: 0;
    }

    /* 關於我 */
    .about {
      background: #f4f4f4;
      padding: 2rem;
      text-align: center;
    }

    .about img {
      border-radius: 50%;
      width: 150px;
      height: 150px;
    }

    /* 頁尾 */
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>

  <!-- 頂部導航 -->
  <header>
    <h1>逆風羽影，隨風築夢</h1>
      </header>
  <nav>
    <a href="#">首頁</a>
    <a href="#about">關於我</a>
    <a href="#posts">文章分類</a>
    <a href="#contact">聯絡我</a>
  </nav>

  <!-- 主頁橫幅 -->
  <section class="hero">
    <h1>平凡與不平凡的我</h1>
    <p>分享我的生活與經歷</p>
  </section>

  <!-- 最新文章區 -->
  <section class="latest-posts" id="posts">
    <h2>最新文章</h2>
    <div class="post">
      <h3>學前特教</h3>
      <p>這是一篇介紹的內容摘要。</p>
    </div>
    <div class="post">
      <h3>運動科學</h3>
      <p>這是一篇介紹的內容摘要。</p>
    </div>
    <div class="post">
      <h3>大腦認知神經心理學</h3>
      <p>這是一篇介紹的內容摘要。</p>
    </div>
  </section>

  <!-- 關於我 -->
  <section class="about" id="about">
    <img src="https://example.com/profile-pic.jpg" alt="我的照片">
    <h2>關於我</h2>
    <p>email:jiangyazhen1018@gmail.com</p>
  </section>

  <!-- 頁尾 -->
  <footer>
    <p>&copy; 2024 個人部落格. 版權所有。</p>
  </footer>

</body>
</html>
