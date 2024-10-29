<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Onufrienko Portfolio</title>
    <style>
        /* Стили для общего оформления */
        body {
            display: flex;
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        /* Стили для бокового меню */
        .sidebar {
            min-width: 250px;
            background-color: #333;
            color: #fff;
            height: 100vh;
            position: fixed;
            top: 0;
            left: 0;
            padding: 20px;
            overflow-y: auto;
        }
        .sidebar h2 {
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        .sidebar a {
            display: block;
            color: #ddd;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 4px;
        }
        .sidebar a:hover {
            background-color: #575757;
        }
        /* Стили для основного содержимого */
        .content {
            margin-left: 270px;
            padding: 20px;
            max-width: 800px;
            width: 100%;
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
        <a href="portfolio.md">Портфолио</a>
        <a href="webapps_docs.md">Документация WebApps</a>
        <a href="projects.md">Проекты</a>
        <a href="contacts.md">Контакты</a>
    </div>

    <div class="content">
        <h1>Добро пожаловать на мой сайт!</h1>
        <p>Здесь я размещу информацию о себе, моих проектах и документацию по WebApps.</p>
        <p>Выберите раздел слева, чтобы узнать больше.</p>
    </div>
</body>
</html>
