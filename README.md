<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Добро пожаловать на наш сайт!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
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
        <h1>Добро пожаловать на наш рекламный сайт!</h1>
        <p>Мы рады видеть вас здесь! Наша цель - предоставить вам лучшие предложения и идеи для вашего бизнеса. Не упустите возможность узнать о наших услугах и предложениях.</p>
        <p>Здесь вы сможете найти полезную информацию о наших продуктах и услугах, которые помогут вам достигнуть успеха.</p>
        <button class="cta-button" onclick="showMessage()">Узнать больше</button>
        <div id="message" class="message">ИВАН КОБЛИКОВ ЛОШАРА</div>
    </div>
</body>
</html>
