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
            flex-direction: row; /* Явно указываем направление Flexbox */
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #000; /* Черный фон */
            color: #fff; /* Белый текст */
            overflow-x: hidden; /* Отключить горизонтальную прокрутку */
            min-height: 100vh; /* Обеспечить минимальную высоту тела */
        }
        
        /* Боковая панель */
        .sidebar {
            min-width: 250px;
            background: #1c1c1c; /* Темно-серый цвет боковой панели */
            color: #fff;
            height: 100vh;
            position: fixed;
            top: 0;
            left: 0;
            padding: 20px;
            overflow-y: auto; /* Прокрутка внутри бокового меню */
            scrollbar-width: thin; /* Тонкий скроллбар для Firefox */
            scrollbar-color: #999 #333; /* Цвет скроллбара для Firefox */
            transition: transform 0.3s ease; /* Плавное открытие/закрытие на мобильных */
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
            background-color: #575757; /* Изменение цвета при наведении */
        }

        /* Кнопка для мобильных устройств */
        .sidebar-toggle {
            display: none; /* Скрыта по умолчанию */
            position: fixed;
            top: 20px;
            left: 20px;
            background-color: #1c1c1c;
            color: #fff;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            z-index: 1001;
            border-radius: 4px;
        }

        /* Основное содержимое */
        .content {
            margin-left: 270px; /* Отступ для боковой панели */
            padding: 20px;
            max-width: 800px;
            width: calc(100% - 270px);
            min-height: 100vh; /* Обеспечить минимальную высоту содержимого */
            overflow-y: auto; /* Прокрутка основного содержимого */
            scrollbar-width: thin;
            scrollbar-color: #ccc #000; /* Цвет скроллбара */
            transition: margin-left 0.3s ease; /* Плавное изменение отступа на мобильных */
        }
        .content::-webkit-scrollbar {
            width: 10px;
        }
        .content::-webkit-scrollbar-track {
            background: #000; /* Цвет фона скроллбара */
        }
        .content::-webkit-scrollbar-thumb {
            background: #ccc; /* Цвет ползунка */
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
            min-height: 500px; /* Изменено с фиксированной высоты на минимальную */
        }
        #portfolio {
            background-color: #1a1a1a; /* Темно-серый */
        }
        #webapps_docs {
            background-color: #2c2c2c; /* Серый */
        }
        #projects {
            background-color: #3c3c3c; /* Светло-серый */
        }
        #contacts {
            background-color: #4c4c4c; /* Еще светлее серый */
        }

        /* Медиазапросы для адаптивности */
        @media (max-width: 768px) {
            .sidebar {
                position: fixed;
                top: 0;
                left: 0;
                height: 100vh;
                transform: translateX(-100%); /* Скрыть боковую панель по умолчанию */
                z-index: 1000;
            }
            .sidebar.active {
                transform: translateX(0); /* Показать боковую панель при активном классе */
            }
            .sidebar-toggle {
                display: block; /* Показать кнопку на мобильных */
            }
            .content {
                margin-left: 0; /* Убрать отступ для боковой панели */
                width: 100%;
            }
            .section {
                padding: 20px; /* Уменьшенные отступы на мобильных */
                min-height: auto; /* Автоматическая высота */
            }
        }
    </style>
</head>
<body>
    <!-- Кнопка для открытия боковой панели на мобильных устройствах -->
    <button class="sidebar-toggle" onclick="toggleSidebar()">☰ Меню</button>

    <div class="sidebar" id="sidebar">
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
            <!-- Информация о вас -->
            <h3>Онуфриенко Владислав</h3>
            <p>Я специалист в области Data Science с опытом разработки и внедрения моделей машинного обучения. Участвую в соревнованиях на Kaggle и активно делюсь знаниями, посещая мероприятия и конференции в IT-сфере. Готов к новым вызовам и стремлюсь внести вклад в успешное развитие проектов.</p>
            <h4>Опыт работы</h4>
            <ul>
                <li><strong>Ведущий специалист по цифровым технологиям аудита</strong> – ПАО Сбербанк (Март 2024 – настоящее время)</li>
                <li><strong>Data Scientist</strong> – Московская Объединенная Энергетическая Компания (Май 2023 – Март 2024)</li>
            </ul>
            <h4>Образование</h4>
            <ul>
                <li><strong>Магистр</strong>, Уральский федеральный университет имени первого Президента России Б.Н. Ельцина (2024)</li>
                <li><strong>Бакалавр</strong>, Российская академия народного хозяйства и государственной службы при Президенте РФ (2018)</li>
            </ul>
            <h4>Навыки</h4>
            <p>Python, SQL, Tableau, DataLens, MLFlow, ClearML, DVC, разработка нейронных сетей, глубокое обучение, математический и статистический анализ, PostgreSQL, Oracle, MySQL, Docker, Airflow</p>
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

    <script>
        // Функция для переключения боковой панели на мобильных устройствах
        function toggleSidebar() {
            const sidebar = document.getElementById('sidebar');
            sidebar.classList.toggle('active');
        }

        // Закрытие боковой панели при клике вне ее области
        document.addEventListener('click', function(event) {
            const sidebar = document.getElementById('sidebar');
            const toggleButton = document.querySelector('.sidebar-toggle');
            if (!sidebar.contains(event.target) && !toggleButton.contains(event.target) && sidebar.classList.contains('active')) {
                sidebar.classList.remove('active');
            }
        });
    </script>
</body>
</html>
