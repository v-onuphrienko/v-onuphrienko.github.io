<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        /* Основные стили */
        * {
            box-sizing: border-box;
            scroll-behavior: smooth; /* Плавная прокрутка */
        }
        body {
            display: flex;
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f9;
            color: #333;
            overflow: hidden; /* Отключить прокрутку для тела, для настройки боковой панели */
        }
        
        /* Боковая панель */
        .sidebar {
            min-width: 250px;
            background: linear-gradient(180deg, #333, #575757);
            color: #fff;
            height: 100vh;
            position: fixed;
            top: 0;
            left: 0;
            padding: 20px;
            overflow-y: auto; /* Прокрутка внутри бокового меню */
            scrollbar-width: thin; /* Тонкий скроллбар для Firefox */
            scrollbar-color: #999 #333; /* Цвет скроллбара для Firefox */
        }
        .sidebar::-webkit-scrollbar {
            width: 8px; /* Ширина скроллбара */
        }
        .sidebar::-webkit-scrollbar-track {
            background: #333; /* Цвет фона скроллбара */
        }
        .sidebar::-webkit-scrollbar-thumb {
            background: #999; /* Цвет ползунка */
            border-radius: 10px; /* Скругленные края ползунка */
        }
        .sidebar h2 {
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        .sidebar a {
            display: block;
            color: #ddd;
            padding: 12px 18px;
            margin: 5px 0;
            text-decoration: none;
            border-radius: 4px;
            transition: background-color 0.3s ease;
        }
        .sidebar a:hover {
            background-color: #777; /* Изменение цвета при наведении */
        }

        /* Основное содержимое */
        .content {
            margin-left: 270px;
            padding: 20px;
            max-width: 800px;
            width: calc(100% - 270px);
            height: 100vh;
            overflow-y: auto; /* Прокрутка основного содержимого */
            scrollbar-width: thin;
            scrollbar-color: #ccc #f4f4f9;
        }
        .content::-webkit-scrollbar {
            width: 10px;
        }
        .content::-webkit-scrollbar-track {
            background: #f4f4f9;
        }
        .content::-webkit-scrollbar-thumb {
            background: #ccc;
            border-radius: 10px;
        }
        .content h1 {
            font-size: 2em;
            margin-top: 0;
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <h2>Навигация</h2>
        <a href="#portfolio">Портфолио</a>
        <a href="#webapps_docs">Документация WebApps</a>
        <a href="#projects">Проекты</a>
        <a href="#contacts">Контакты</a>
    </div>

    <div class="content">
        <h1>Добро пожаловать на мой сайт!</h1>
        <p>Здесь я размещу информацию о себе, моих проектах и документацию по WebApps.</p>
        <p>Выберите раздел слева, чтобы узнать больше.</p>
        
        <!-- Добавлены якоря для каждой секции -->
        <section id="portfolio">
            <h2>Портфолио</h2>
            <p>Здесь можно найти мои работы и примеры проектов.</p>
        </section>
        
        <section id="webapps_docs">
            <h2>Документация WebApps</h2>
            <p>Информация и инструкции по работе с Telegram WebApps.</p>
        </section>
        
        <section id="projects">
            <h2>Проекты</h2>
            <p>Проекты, над которыми я работал, и их описание.</p>
        </section>
        
        <section id="contacts">
            <h2>Контакты</h2>
            <!-- Вставь содержимое из contacts.md здесь -->
            <p>Вы можете связаться со мной через следующие платформы:</p>
            <a href="https://t.me/onuphrienko" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Telegram_logo.svg" alt="Telegram" style="width: 40px; height: 40px; margin-right: 10px;">
            </a>
            <a href="https://www.linkedin.com/in/onuphrienko/" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LinkedIn_Logo.svg" alt="LinkedIn" style="width: 40px; height: 40px; margin-right: 10px;">
            </a>
            <a href="https://github.com/v-onuphrienko" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub" style="width: 40px; height: 40px; margin-right: 10px;">
            </a>
        </section>
    </div>
</body>
</html>
