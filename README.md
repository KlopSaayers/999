<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Поздравление для мамы Анастасии</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Sacramento&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: #fff;
            text-align: center;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: rgba(255, 255, 255, 0.2);
            padding: 20px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            margin: 20px;
        }
        h1 {
            font-size: 2.5em;
            margin: 0;
            font-family: 'Sacramento', cursive;
            letter-spacing: 2px;
        }
        main {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 20px;
        }
        p {
            font-size: 1.2em;
            margin: 20px 0;
            line-height: 1.6;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            background: rgba(255, 255, 255, 0.1);
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }
        .heart {
            font-size: 4em;
            color: #ff4757;
            animation: heartbeat 1.5s infinite;
            margin: 40px 0;
        }
        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }
        footer {
            background-color: rgba(255, 255, 255, 0.2);
            padding: 10px;
            box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            margin: 20px;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 2em;
            }
            p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>С Днем Рождения, мама Анастасия!</h1>
    </header>
    <main>
        <p>Дорогая мама!</p>
        <p>Сегодня твой день, и я хочу, чтобы ты знала, как сильно я тебя люблю. Ты — источник вдохновения и радости в моей жизни.</p>
        <p>Твоя поддержка и забота делают каждый момент особенным. Спасибо за все уроки, которые ты мне дала, и за ту любовь, которую ты щедро даришь.</p>
        <div class="heart">❤️❤️❤️</div>
        <p>Пусть этот день будет полон счастья, улыбок и приятных сюрпризов. Желаю тебе здоровья, удачи и исполнения всех мечт!</p>
    </main>
    <footer>
        <p>С любовью, твой сын.</p>
    </footer>
</body>
</html>
