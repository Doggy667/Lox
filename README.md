<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моя веб-страница</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background: #35424a;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background: #e8491d;
            padding: 10px;
        }
        nav ul {
            padding: 0;
            list-style: none;
            text-align: center;
        }
        nav li {
            display: inline;
            margin: 0 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background: white;
        }
        footer {
            background: #35424a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать на мой сайт</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#">Главная</a></li>
            <li><a href="#">О нас</a></li>
            <li><a href="#">Услуги</a></li>
            <li><a href="#">Контакты</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <h2>О нашем сайте</h2>
        <p>Это простая веб-страница, созданная с помощью HTML и CSS. Вы можете изменить этот текст и добавить свой собственный контент.</p>
        
        <h3>Наши преимущества</h3>
        <ul>
            <li>Простота использования</li>
            <li>Чистый код</li>
            <li>Адаптивный дизайн</li>
        </ul>
    </div>
    
    <footer>
        <p>&copy; 2023 Мой сайт. Все права защищены.</p>
    </footer>
</body>
</html>
