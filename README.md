<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>NEP - New Electric Planet</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0b1120;
      color: white;
      text-align: center;
    }

    /* Навигация */
    nav {
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 20px;
      font-size: 18px;
    }

    nav a {
      color: white;
      text-decoration: none;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffd54f;
    }

    /* Логотип */
    .logo {
      margin-top: 40px;
    }

    /* Слоган */
    .slogan {
      font-size: 26px;
      font-weight: bold;
      margin: 20px 0;
      font-family: "Trebuchet MS", sans-serif;
      text-transform: uppercase;
      color: #ffd54f;
      text-shadow: 0 0 10px rgba(255,213,79,0.7);
    }

    /* Кнопка */
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 15px 30px;
      background: #ffd54f;
      color: black;
      border-radius: 10px;
      font-weight: bold;
      text-decoration: none;
      transition: all 0.3s ease;
      position: relative;
    }

    /* Подсветка лампочки */
    .btn:hover {
      background: #ffeb3b;
      box-shadow: 0 0 20px #ffeb3b;
    }

    .logo img {
      width: 200px;
      transition: filter 0.3s ease, box-shadow 0.3s ease;
    }

    .btn:hover ~ .logo img {
      filter: brightness(1.3);
      box-shadow: 0 0 40px #ffeb3b;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#">Каталог</a>
    <a href="#">О компании</a>
    <a href="#">Контакты</a>
  </nav>

  <div class="logo">
    <img src="logo.png" alt="NEP Logo">
  </div>

  <h1>NEP</h1>
  <p>NEW ELECTRIC PLANET</p>

  <div class="slogan">ЭНЕРГИЯ БУДУЩЕГО В ВАШИХ РУКАХ</div>

  <a href="#" class="btn">ПЕРЕЙТИ В КАТАЛОГ</a>
</body>
</html>
