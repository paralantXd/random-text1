<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random Text</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div id="random-text"></div>

    <script>
        // Массив текстов
        const texts = [
            "Добро пожаловать! Мы рады вас видеть!",
            "Привет! Надеемся, вы найдёте всё, что ищете!"
        ];

        // Выбор случайного текста
        const randomText = texts[Math.floor(Math.random() * texts.length)];

        // Вывод текста на страницу
        document.getElementById('random-text').innerText = randomText;
    </script>
</body>
</html>

