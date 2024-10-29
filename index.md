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
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #000; /* Черный фон */
            color: #fff; /* Белый текст */
            overflow-x: hidden; /* Отключить горизонтальную прокрутку */
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
        }
        
        /* Основное содержимое */
        .content {
            margin-left: 270px; /* Отступ для боковой панели */
            padding: 20px;
            min-height: 100vh; /* Обеспечить минимальную высоту содержимого */
        }
        
        /* Стили для секций */
        .section {
            padding: 40px;
            margin-bottom: 20px;
            min-height: 100vh; /* Каждая секция занимает весь экран */
            opacity: 0;
            transform: translateY(50px);
            transition: opacity 0.6s ease, transform 0.6s ease;
        }
        .section.active {
            opacity: 1;
            transform: translateY(0);
        }

        /* Цвета для секций */
        #portfolio { background-color: #1a1a1a; }
        #webapps_docs { background-color: #2c2c2c; }
        #projects { background-color: #3c3c3c; }
        #contacts { background-color: #4c4c4c; }

        /* Кнопка переключения языка */
        .language-switcher {
            position: absolute;
            top: 20px;
            right: 20px;
            background-color: #1c1c1c;
            color: #fff;
            border: none;
            padding: 8px 12px;
            cursor: pointer;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <!-- Кнопка для открытия боковой панели на мобильных устройствах -->
    <button class="sidebar-toggle" onclick="toggleSidebar()">☰ Меню</button>

    <!-- Кнопка переключения языка -->
    <button class="language-switcher" onclick="switchLanguage()">EN / RU</button>

    <div class="sidebar" id="sidebar">
        <!-- Дублирование заголовка навигации для обоих языков -->
        <h2 class="lang-ru lang-active">Навигация</h2>
        <h2 class="lang-en">Navigation</h2>

        <!-- Навигационные ссылки -->
        <a href="#portfolio" class="lang-ru lang-active">Портфолио</a>
        <a href="#webapps_docs" class="lang-ru">Документация WebApps</a>
        <a href="#projects" class="lang-ru">Проекты</a>
        <a href="#contacts" class="lang-ru">Контакты</a>

        <a href="#portfolio" class="lang-en">Portfolio</a>
        <a href="#webapps_docs" class="lang-en">WebApps Documentation</a>
        <a href="#projects" class="lang-en">Projects</a>
        <a href="#contacts" class="lang-en">Contacts</a>
    </div>

    <div class="content">
        <!-- Заголовки и параграфы для обоих языков -->
        <h1 class="lang-ru lang-active">Добро пожаловать на мой сайт!</h1>
        <h1 class="lang-en">Welcome to my website!</h1>

        <p class="lang-ru lang-active">Здесь я размещу информацию о себе, моих проектах и документацию по WebApps.</p>
        <p class="lang-en">Here I will provide information about myself, my projects, and WebApps documentation.</p>

        <p class="lang-ru lang-active">Выберите раздел слева, чтобы узнать больше.</p>
        <p class="lang-en">Select a section on the left to learn more.</p>
        
        <!-- Секции с разными цветами -->
        <section id="portfolio" class="section">
            <h2 class="lang-ru lang-active">Портфолио</h2>
            <h2 class="lang-en">Portfolio</h2>
            <p class="lang-ru lang-active">Здесь можно найти мои работы и примеры проектов.</p>
            <p class="lang-en">Here you can find my work and project examples.</p>

            <!-- Информация о вас -->
            <h3 class="lang-ru lang-active">Онуфриенко Владислав</h3>
            <h3 class="lang-en">Vladislav Onufrienko</h3>

            <p class="lang-ru lang-active">
                Я специалист в области Data Science с опытом разработки и внедрения моделей машинного обучения.
                Участвую в соревнованиях на Kaggle и активно делюсь знаниями, посещая мероприятия и конференции
                в IT-сфере. Готов к новым вызовам и стремлюсь внести вклад в успешное развитие проектов.
            </p>
            <p class="lang-en">
                I am a Data Science specialist with experience in developing and implementing machine learning models.
                I participate in competitions on Kaggle and actively share knowledge by attending events and conferences
                in the IT field. I am ready for new challenges and strive to contribute to the successful development of projects.
            </p>

            <h4 class="lang-ru lang-active">Опыт работы</h4>
            <h4 class="lang-en">Work Experience</h4>
            <ul>
                <li class="lang-ru lang-active">
                    <strong>Ведущий специалист по цифровым технологиям аудита</strong> – ПАО Сбербанк (Март 2024 – настоящее время)
                </li>
                <li class="lang-en">
                    <strong>Lead Specialist in Digital Audit Technologies</strong> – Sberbank (March 2024 – Present)
                </li>
                <li class="lang-ru lang-active">
                    <strong>Data Scientist</strong> – Московская Объединенная Энергетическая Компания (Май 2023 – Март 2024)
                </li>
                <li class="lang-en">
                    <strong>Data Scientist</strong> – Moscow United Energy Company (May 2023 – March 2024)
                </li>
                <li class="lang-ru lang-active">
                    <strong>Специалист по восстановлению документации и планированию</strong> – Полюс Магадан (Июль 2021 – Ноябрь 2021)
                </li>
                <li class="lang-en">
                    <strong>Documentation and Planning Specialist</strong> – Polyus Magadan (July 2021 – November 2021)
                </li>
                <li class="lang-ru lang-active">
                    <strong>Специалист участка подготовки непрофильных деталей и компонентов</strong> – Модерн Машинери Фар Ист (Сентябрь 2018 – Апрель 2021)
                </li>
                <li class="lang-en">
                    <strong>Non-profile Parts and Components Preparation Specialist</strong> – Modern Machinery Far East (September 2018 – April 2021)
                </li>
            </ul>

            <h4 class="lang-ru lang-active">Образование</h4>
            <h4 class="lang-en">Education</h4>
            <ul>
                <li class="lang-ru lang-active">
                    <strong>Магистр</strong>, Уральский федеральный университет имени первого Президента России Б.Н. Ельцина (2024)
                </li>
                <li class="lang-en">
                    <strong>Master's Degree</strong>, Ural Federal University named after the first President of Russia B.N. Yeltsin (2024)
                </li>
                <li class="lang-ru lang-active">
                    <strong>Бакалавр</strong>, Российская академия народного хозяйства и государственной службы при Президенте РФ (2018)
                </li>
                <li class="lang-en">
                    <strong>Bachelor's Degree</strong>, Russian Academy of National Economy and Public Administration under the President of the Russian Federation (2018)
                </li>
            </ul>

            <h4 class="lang-ru lang-active">Навыки</h4>
            <h4 class="lang-en">Skills</h4>
            <p class="lang-ru lang-active">
                Python, SQL, Tableau, DataLens, MLFlow, ClearML, DVC, разработка нейронных сетей,
                глубокое обучение, математический и статистический анализ, PostgreSQL, Oracle, MySQL, Docker, Airflow
            </p>
            <p class="lang-en">
                Python, SQL, Tableau, DataLens, MLFlow, ClearML, DVC, neural network development,
                deep learning, mathematical and statistical analysis, PostgreSQL, Oracle, MySQL, Docker, Airflow
            </p>
        </section>
        
        <section id="webapps_docs" class="section">
            <h2 class="lang-ru lang-active">Документация WebApps</h2>
            <h2 class="lang-en">WebApps Documentation</h2>
            <p class="lang-ru lang-active">Информация и инструкции по работе с Telegram WebApps.</p>
            <p class="lang-en">Information and instructions for working with Telegram WebApps.</p>
        </section>
        
        <section id="projects" class="section">
            <h2 class="lang-ru lang-active">Проекты</h2>
            <h2 class="lang-en">Projects</h2>
            <p class="lang-ru lang-active">Проекты, над которыми я работал, и их описание.</p>
            <p class="lang-en">Projects I have worked on and their descriptions.</p>
        </section>
        
        <section id="contacts" class="section">
            <h2 class="lang-ru lang-active">Контакты</h2>
            <h2 class="lang-en">Contacts</h2>
            <p class="lang-ru lang-active">Связаться со мной можно через следующие платформы:</p>
            <p class="lang-en">You can contact me through the following platforms:</p>
            <a href="https://github.com/v-onuphrienko" target="_blank">
                <img src="https://img.shields.io/badge/GitHub-Onufrienko_V.I.-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" class="lang-ru lang-active">
                <img src="https://img.shields.io/badge/GitHub-Onufrienko_V.I.-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" class="lang-en">
            </a>
            <a href="https://t.me/onuphrienko" target="_blank">
                <img src="https://img.shields.io/badge/Telegram-@onuphrienko-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" class="lang-ru lang-active">
                <img src="https://img.shields.io/badge/Telegram-@onuphrienko-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" class="lang-en">
            </a>
            <a href="https://www.linkedin.com/in/onuphrienko/" target="_blank">
                <img src="https://img.shields.io/badge/LinkedIn-Vladislav_Onuphrienko-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" class="lang-ru lang-active">
                <img src="https://img.shields.io/badge/LinkedIn-Vladislav_Onuphrienko-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" class="lang-en">
            </a>
        </section>
    </div>

    <script>
        // Функция для переключения боковой панели на мобильных устройствах
        function toggleSidebar() {
            const sidebar = document.getElementById('sidebar');
            sidebar.classList.toggle('active');
        }

        // Закрытие боковой панели при клике вне её области
        document.addEventListener('click', function(event) {
            const sidebar = document.getElementById('sidebar');
            const toggleButton = document.querySelector('.sidebar-toggle');
            if (!sidebar.contains(event.target) && !toggleButton.contains(event.target) && sidebar.classList.contains('active')) {
                sidebar.classList.remove('active');
            }
        });

        // Функция для переключения языка
        function switchLanguage() {
            const currentLang = localStorage.getItem('language') || 'ru';
            const languageSwitcher = document.querySelector('.language-switcher');
        
            if (currentLang === 'ru') {
                // Переключение на английский
                document.querySelectorAll('.lang-ru').forEach(el => el.style.display = 'none');
                document.querySelectorAll('.lang-en').forEach(el => el.style.display = 'block');
                localStorage.setItem('language', 'en');
                languageSwitcher.textContent = 'RU / EN';
            } else {
                // Переключение на русский
                document.querySelectorAll('.lang-en').forEach(el => el.style.display = 'none');
                document.querySelectorAll('.lang-ru').forEach(el => el.style.display = 'block');
                localStorage.setItem('language', 'ru');
                languageSwitcher.textContent = 'EN / RU';
            }
        }
        
        // Инициализация языка при загрузке страницы
        document.addEventListener('DOMContentLoaded', () => {
            const savedLang = localStorage.getItem('language') || 'ru';
            const languageSwitcher = document.querySelector('.language-switcher');
        
            if (savedLang === 'ru') {
                document.querySelectorAll('.lang-ru').forEach(el => el.style.display = 'block');
                document.querySelectorAll('.lang-en').forEach(el => el.style.display = 'none');
                languageSwitcher.textContent = 'EN / RU';
            } else {
                document.querySelectorAll('.lang-en').forEach(el => el.style.display = 'block');
                document.querySelectorAll('.lang-ru').forEach(el => el.style.display = 'none');
                languageSwitcher.textContent = 'RU / EN';
            }
        });
    </script>
</body>
</html>