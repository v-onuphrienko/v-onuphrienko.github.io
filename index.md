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

        /* Цвета для секций */
        .section {
            padding: 40px; /* Увеличенные отступы */
            border-radius: 8px;
            margin-bottom: 20px;
            height: 500px; /* Увеличенная высота секций для тестирования прокрутки */
        }
        #portfolio {
            background-color: #e0f7fa; /* Светло-голубой */
        }
        #webapps_docs {
            background-color: #ffe0b2; /* Светло-оранжевый */
        }
        #projects {
            background-color: #f1f8e9; /* Светло-зеленый */
        }
        #contacts {
            background-color: #fce4ec; /* Светло-розовый */
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
        
        <!-- Секции с разными цветами -->
        <section id="portfolio" class="section">
            <h2>Портфолио</h2>
            <p>Здесь можно найти мои работы и примеры проектов.</p>
        </section>
        
        <section id="webapps_docs" class="section">
            <h2>Документация WebApps</h2>
            <p>Информация и инструкции по работе с Telegram WebApps.</p>
        </section>
        
        <section id="projects" class="section">
            <h2>Проекты</h2>
            <p>Проекты, над которыми я работал, и их описание.</p>
        </section>
        
        <section id="contacts" class="section">
            <h2>Контакты</h2>
            <p>Связаться со мной можно через следующие платформы:</p>
            <a href="https://github.com/v-onuphrienko" target="_blank">
                <img src="https://img.shields.io/badge/GitHub-Onufrienko_V.I.-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
            </a>
            <a href="https://t.me/onuphrienko" target="_blank">
                <img src="https://img.shields.io/badge/Telegram-@onuphrienko-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
            </a>
            <a href="https://www.linkedin.com/in/onuphrienko/" target="_blank">
                <img src="https://img.shields.io/badge/LinkedIn-Vladislav_Onuphrienko-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
            </a>
        </section>
    </div>
</body>
</html>
