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
        <!-- Секции с разными цветами -->
        <section id="portfolio" class="section">
            <h2 class="lang-ru lang-active">Портфолио</h2>
            <h2 class="lang-en">Portfolio</h2>
        </section>
        
        <section id="webapps_docs" class="section">
            <h2 class="lang-ru lang-active">Документация WebApps</h2>
            <h2 class="lang-en">WebApps Documentation</h2>
        </section>
        
        <section id="projects" class="section">
            <h2 class="lang-ru lang-active">Проекты</h2>
            <h2 class="lang-en">Projects</h2>
        </section>
        
        <section id="contacts" class="section">
            <h2 class="lang-ru lang-active">Контакты</h2>
            <h2 class="lang-en">Contacts</h2>
        </section>
    </div>

    <script>
        // Функция для переключения языка
        function switchLanguage() {
            const currentLang = localStorage.getItem('language') || 'ru';
            const languageSwitcher = document.querySelector('.language-switcher');
        
            if (currentLang === 'ru') {
                document.querySelectorAll('.lang-ru').forEach(el => el.style.display = 'none');
                document.querySelectorAll('.lang-en').forEach(el => el.style.display = 'block');
                localStorage.setItem('language', 'en');
                languageSwitcher.textContent = 'RU / EN';
            } else {
                document.querySelectorAll('.lang-en').forEach(el => el.style.display = 'none');
                document.querySelectorAll('.lang-ru').forEach(el => el.style.display = 'block');
                localStorage.setItem('language', 'ru');
                languageSwitcher.textContent = 'EN / RU';
            }
        }

        // Плавное появление секций при скролле
        function handleScroll() {
            const sections = document.querySelectorAll('.section');
            sections.forEach(section => {
                const sectionTop = section.getBoundingClientRect().top;
                if (sectionTop < window.innerHeight - 100) {
                    section.classList.add('active');
                }
            });
        }
        
        window.addEventListener('scroll', handleScroll);

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

            // Запускаем анимацию для первой секции
            handleScroll();
        });
    </script>
</body>
</html>
