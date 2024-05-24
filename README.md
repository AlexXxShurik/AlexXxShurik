<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Резюме</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        .container {
            width: 80%;
            max-width: 900px;
            margin: 30px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }

        header {
            text-align: center;
            padding: 20px 0;
            border-bottom: 2px solid #00bfa5;
        }

        header h1 {
            margin: 10px 0;
            font-size: 2.5em;
            color: #00bfa5;
        }

        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 0 auto;
            display: block;
            border: 5px solid #00bfa5;
        }

        .contact-info {
            text-align: center;
            margin-top: 10px;
        }

        .contact-info p {
            margin: 5px 0;
        }

        .contact-info a {
            color: #00bfa5;
            text-decoration: none;
            font-weight: 500;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .contact-info i {
            margin-right: 8px;
        }

        .section {
            margin: 20px 0;
        }

        .section h2 {
            background: #00bfa5;
            color: #fff;
            padding: 10px;
            margin: 0 -20px 10px -20px;
            border-radius: 10px 10px 0 0;
        }

        .skills ul {
            list-style-type: none;
            padding: 0;
        }

        .skills ul li {
            background: #e4e4e4;
            padding: 10px 20px;
            border-radius: 50px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .skills ul li span {
            margin-left: 10px;
            flex-grow: 1;
        }

        .skills ul li .progress-bar {
            height: 10px;
            background: #00bfa5;
            border-radius: 5px;
            flex-basis: 70%;
            margin-left: 10px;
            transition: width 0.3s ease;
        }

        .skills ul li:hover .progress-bar {
            width: 100%;
        }

        .experience,
        .education,
        .certificates {
            padding: 0 20px;
        }

        .experience h3,
        .education h3 {
            margin: 10px 0;
        }

        .experience p,
        .education p {
            margin: 5px 0;
        }

        ul.responsibilities {
            list-style-type: disc;
            padding-left: 20px;
        }

        .social-icons {
            text-align: center;
            margin-top: 20px;
        }

        .social-icons a {
            color: #00bfa5;
            margin: 0 10px;
            font-size: 1.5em;
            transition: color 0.3s ease;
        }

        .social-icons a:hover {
            color: #00796b;
        }
    </style>
</head>

<body>
    <div class="container">
        <header>
            <img src="profile.jpg" alt="Фото профиля" class="profile-pic">
            <h1>Александр Петров</h1>
            <div class="contact-info">
                <p><i class="fas fa-envelope"></i> Email: <a
                        href="mailto:ap.web.design.pro@gmail.com">ap.web.design.pro@gmail.com</a></p>
                <p><i class="fas fa-phone"></i> Телефон: +7 (705) 150-66-13</p>
                <p><i class="fab fa-telegram"></i> Telegram: <a href="https://t.me/IIIAlexandrPetrovIII"
                        target="_blank">@IIIAlexandrPetrovIII</a></p>
            </div>
        </header>

        <div class="section">
            <h2>Обо мне</h2>
            <p>Я начинающий frontend разработчик, есть коммерческий опыт разработки в течение года. Изучал и применял:
                HTML, CSS, JavaScript, Python, Django, Git. Очень быстро обучаюсь и ответственно отношусь к работе.
                Люблю создавать сайты со сложным функционалом и нестандартным дизайном.
            </p>
        </div>

        <div class="section experience">
            <h2>Опыт работы</h2>
            <h3>Специалист по цифровизации</h3>
            <p>ТОО "Казцинк", 2022 - 2023 гг</p>
            <ul class="responsibilities">
                <li>Разработка и поддержка веб-приложений с использованием HTML, CSS, JavaScript и MySQL.</li>
                <li>Персональный проект, спланированный и разработанный мной</li>
                <li>Разрабатывал проект с группой интузиастов для изучения Git</li>
            </ul>
            <h3>Опыт вне IT</h3>
            <p>ТОО "Казцинк", горнодобывающие професии</p>
            <ul class="responsibilities">
                <li>Есть опыт работы на руководящих должностях.</li>
                <li>На данный момент повысили до начальника другой службы управления основыних фондов, не связанной с IT
                </li>
            </ul>
        </div>

        <div class="section skills">
            <h2>Навыки</h2>
            <ul>
                <li>HTML5 <div class="progress-bar" style="width: 90%;"></div>
                </li>
                <li>CSS3 <div class="progress-bar" style="width: 85%;"></div>
                </li>
                <li>JavaScript (ES6+) <div class="progress-bar" style="width: 80%;"></div>
                </li>
                <li>Git и GitHub <div class="progress-bar" style="width: 75%;"></div>
                </li>
                <li>Python <div class="progress-bar" style="width: 70%;"></div>
                </li>
                <li>Django <div class="progress-bar" style="width: 65%;"></div>
                </li>
                <li>SQL <div class="progress-bar" style="width: 60%;"></div>
                </li>
            </ul>
        </div>

        <div class="section education">
            <h2>Образование</h2>
            <h3>Бакалавр</h3>
            <p>Горное дело, 2006 - 2010 гг, ВКГТУ</p>
        </div>

        <div class="section certificates">
            <h2>Обучение IT</h2>
            <p>Самостоятельное изучение в домашних условиях</p>
        </div>
    </div>
</body>

</html>
