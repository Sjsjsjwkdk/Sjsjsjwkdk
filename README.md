<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Портфолио художника. Галерея работ, информация и контакты.">
    <title>Портфолио Художника</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Портфолио Художника</h1>
        <nav>
            <ul>
                <li><a href="#about">Обо мне</a></li>
                <li><a href="#gallery">Галерея</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>Обо мне</h2>
        <p>Меня зовут [Ваше Имя], я художник с опытом работы в различных техниках и стилях. Я стремлюсь создать уникальные произведения искусства, которые находят отклик в сердцах зрителей.</p>
    </section>

    <section id="gallery">
        <h2>Галерея</h2>
        <div class="gallery">
            <img src="art1.jpg" alt="Работа 1">
            <img src="art2.jpg" alt="Работа 2">
            <img src="art3.jpg" alt="Работа 3">
            <img src="art4.jpg" alt="Работа 4">
        </div>
    </section>

    <section id="contact">
        <h2>Контакты</h2>
        <p>Свяжитесь со мной по почте или через социальные сети.</p>
        <form action="submit_form.php" method="post">
            <label for="name">Имя:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Сообщение:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Отправить</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Портфолио Художника. Все права защищены.</p>
    </footer>
</body>
</html>
