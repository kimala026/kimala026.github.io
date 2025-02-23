<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Группа компаний 'Стройсервис' предлагает лучшие цены на квартиры. Добро пожаловать на наш сайт!">
    <meta name="keywords" content="стройсервис, квартиры, недвижимость, лучшие цены">
    <title>Добро пожаловать на наш сайт!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-image: url('https://via.placeholder.com/1920x1080'); /* Замените ссылку на ваше изображение новостройки */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            position: relative;
        }
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(255, 255, 255, 0.7); /* Полупрозрачный белый слой */
            z-index: -1;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: rgba(255, 255, 255, 0.9); /* Полупрозрачный белый фон контейнера */
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: relative;
            z-index: 1;
        }
        h1 {
            color: #333;
        }
        p {
            line-height: 1.6;
            color: #555;
        }
        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            color: white;
            background-color: #007BFF;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
            cursor: pointer;
        }
        .cta-button:hover {
            background-color: #0056b3;
        }
        .message {
            margin-top: 20px;
            display: none;
            color: #d9534f;
            font-size: 1.5em;
        }
    </style>
    <script>
        function showMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</head>
<body>
    <div class="container">
        <header>
            <h1>Группа компаний "Стройсервис" приветствует вас!</h1>
        </header>
        <main>
            <p>Наша цель - предоставить вам лучшие цены на квартиры.</p>
            <a href="#" class="cta-button" onclick="showMessage()">Узнать больше</a>
            <div id="message" class="message">
                Спасибо за ваш интерес! Мы свяжемся с вами в ближайшее время.
            </div>
        </main>
    </div>
</body>
</html>
