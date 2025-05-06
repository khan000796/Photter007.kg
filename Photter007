<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Photter Clone</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #121212;
      color: white;
      display: flex;
    }
    .sidebar {
      height: 100vh;
      width: 280px;
      background-color: #2c2c2c;
      padding: 20px;
      position: fixed;
    }
    .sidebar h1 {
      font-size: 28px;
      font-weight: normal;
      margin-bottom: 40px;
    }
    .menu-item {
      display: flex;
      align-items: center;
      margin: 15px 0;
      color: #ccc;
      cursor: pointer;
    }
    .menu-item:hover {
      color: white;
    }
    .menu-item span {
      margin-left: 10px;
    }
    .divider {
      margin: 30px 0;
      border-top: 1px solid #444;
    }
    .content {
      margin-left: 300px;
      padding: 40px;
      flex: 1;
    }
    .hidden {
      display: none;
    }
  </style>
</head>
<body>
  <div class="sidebar">
    <h1>Photter</h1>
    <div class="menu-item" onclick="showPage('albums')"><span>Альбомы в облаке</span></div>
    <div class="menu-item" onclick="showPage('profile')"><span>Пользователь</span></div>
    <div class="menu-item" onclick="showPage('contact')"><span>Связаться с нами</span></div>
    <div class="divider"></div>
    <div class="menu-item" onclick="showPage('visit')"><span>Посетить веб-сайт</span></div>
    <div class="menu-item" onclick="showPage('share')"><span>Поделиться</span></div>
    <div class="divider"></div>
    <div class="menu-item" onclick="showPage('login')"><span>Войти</span></div>
    <div class="menu-item" onclick="showPage('register')"><span>Зарегистрироваться</span></div>
  </div>

  <div class="content">
    <div id="albums">
      <h2>Альбомы</h2>
      <p>Здесь будут отображаться ваши фотографии.</p>
    </div>
    <div id="profile" class="hidden">
      <h2>Профиль</h2>
      <p>Данные пользователя.</p>
    </div>
    <div id="contact" class="hidden">
      <h2>Связь с нами</h2>
      <p>Форма обратной связи.</p>
    </div>
    <div id="visit" class="hidden">
      <h2>Веб-сайт</h2>
      <p><a href="#" style="color: #4fc3f7;">photter.example.com</a></p>
    </div>
    <div id="share" class="hidden">
      <h2>Поделиться</h2>
      <p>Скопируйте ссылку и отправьте друзьям.</p>
    </div>
    <div id="login" class="hidden">
      <h2>Вход</h2>
      <form>
        <label>Email:</label><br>
        <input type="email" required><br>
        <label>Пароль:</label><br>
        <input type="password" required><br><br>
        <button type="submit">Войти</button>
      </form>
    </div>
    <div id="register" class="hidden">
      <h2>Регистрация</h2>
      <form>
        <label>Email:</label><br>
        <input type="email" required><br>
        <label>Пароль:</label><br>
        <input type="password" required><br><br>
        <button type="submit">Зарегистрироваться</button>
      </form>
    </div>
  </div>

  <script>
    function showPage(id) {
      const sections = document.querySelectorAll('.content > div');
      sections.forEach(section => section.classList.add('hidden'));
      document.getElementById(id).classList.remove('hidden');
    }
  </script>
</body>
</html>
