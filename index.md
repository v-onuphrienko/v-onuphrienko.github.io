<style>
    /* Стили для раскрывающегося меню */
    .dropdown {
        position: relative;
        display: inline-block;
    }
    .dropdown-content {
        display: none;
        position: absolute;
        background-color: #f9f9f9;
        min-width: 160px;
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
        z-index: 1;
    }
    .dropdown-content a {
        color: black;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
    }
    .dropdown-content a:hover {background-color: #f1f1f1;}
    .dropdown:hover .dropdown-content {
        display: block;
    }
</style>

<body>
    <header>
        <h1>Добро пожаловать на мой сайт!</h1>
        <nav>
            <div class="dropdown">
                <a href="#">Разделы</a>
                <div class="dropdown-content">
                    <a href="portfolio.md">Портфолио</a>
                    <a href="webapps_docs.md">Документация WebApps</a>
                    <a href="another_topic.md">Ещё один раздел</a>
                </div>
            </div>
        </nav>
    </header>
</body>
