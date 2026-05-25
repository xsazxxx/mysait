[index.html](https://github.com/user-attachments/files/28219659/index.html)
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Мир Танца - Часть 1</title>
    <style>
        /* Основные стили для всего сайта */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #34495e;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #f1c40f;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            display: grid;
            grid-template-columns: 1fr 1fr; /* Две колонки */
            gap: 30px;
        }

        /* Стиль карточки танца */
        .dance-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .dance-card:hover {
            transform: translateY(-5px);
        }

        .dance-card img {
            width: 100%;
            height: 250px;
            object-fit: cover; /* Чтобы фото не растягивалось */
        }

        .dance-info {
            padding: 20px;
        }

        .dance-info h2 {
            margin-top: 0;
            color: #e74c3c;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Энциклопедия Танца</h1>
        <p>Путешествие в мир ритма и движения</p>
    </header>

    <nav>
        <a href="index.html">Главная страница</a>
        <a href="page2.html">Продолжение (Стр. 2)</a>
    </nav>

    <div class="container">
        <!-- Карточка 1 -->
        <div class="dance-card">
            <img src="images/ballet.jpg" alt="Балет">
            <div class="dance-info">
                <h2>Балет</h2>
                <p>Классический танец, зародившийся в Италии эпохи Возрождения. Характеризуется легкостью, точностью движений и особой техникой (например, пуанты). Это высшая форма сценического танца.</p>
            </div>
        </div>

        <!-- Карточка 2 -->
        <div class="dance-card">
            <img src="images/hiphop.jpg" alt="Хип-хоп">
            <div class="dance-info">
                <h2>Хип-хоп</h2>
                <p>Уличное направление, возникшее в Нью-Йорке в 70-х годах. Это не просто танец, а целая культура, включающая музыку, одежду и сленг. Движения часто резкие, ритмичные и свободные.</p>
            </div>
        </div>

        <!-- Карточка 3 -->
        <div class="dance-card">
            <img src="images/tango.jpg" alt="Танго">
            <div class="dance-info">
                <h2>Танго</h2>
                <p>Страстный парный танец родом из Аргентины. Это диалог между мужчиной и женщиной, полный драматизма, пауз и резких движений. Часто исполняется под музыку бандонеона.</p>
            </div>
        </div>

        <!-- Карточка 4 -->
        <div class="dance-card">
            <img src="images/salsa.jpg" alt="Сальса">
            <div class="dance-info">
                <h2>Сальса</h2>
                <p>Парный социальный танец латиноамериканского происхождения. Очень энергичный, веселый и ритмичный. Основа — работа бедер и быстрая смена позиций партнеров.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2026 Мой журнал о танцах Анастасия Злыднина</p>
    </footer>

</body>
</html>
