<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>С Днём Рождения, Мама!</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:linear-gradient(135deg,#ffe4ec,#fff5f8);
    color:#333;
}

header{
    text-align:center;
    padding:80px 20px;
}

h1{
    font-size:3rem;
    color:#d63384;
}

.subtitle{
    margin-top:15px;
    font-size:1.2rem;
}

.section{
    max-width:1000px;
    margin:auto;
    padding:60px 20px;
}

.card{
    background:white;
    padding:30px;
    border-radius:20px;
    box-shadow:0 5px 20px rgba(0,0,0,0.1);
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:15px;
    margin-top:20px;
}

.gallery img{
    width:100%;
    border-radius:15px;
    height:250px;
    object-fit:cover;
}

.video{
    width:100%;
    border-radius:15px;
    margin-top:20px;
}

footer{
    text-align:center;
    padding:40px;
    color:#777;
}
</style>
</head>
<body>

<header>
    <h1>🌹 С Днём Рождения, Мама! 🌹</h1>
    <p class="subtitle">39 лет красоты, заботы, любви и тепла ❤️</p>
</header>

<section class="section">
    <div class="card">
        <h2>💖 Поздравление</h2>
        <br>
        <p>
            Дорогая мама!
            <br><br>
            Сегодня особенный день — твой день рождения.
            Спасибо тебе за любовь, поддержку, доброту и бесконечную заботу.
            Ты самый дорогой и важный человек в нашей жизни.
            <br><br>
            Пусть каждый день приносит радость, счастье и улыбки.
            Желаем крепкого здоровья, исполнения всех желаний,
            семейного уюта и бесконечного тепла.
            <br><br>
            Мы очень любим тебя! ❤️
        </p>
    </div>
</section>

<section class="section">
    <div class="card">
        <h2>📸 Наши воспоминания</h2>

        <div class="gallery">
            <img src="photo1.jpg" alt="">
            <img src="photo2.jpg" alt="">
            <img src="photo3.jpg" alt="">
            <img src="photo4.jpg" alt="">
        </div>
    </div>
</section>

<section class="section">
    <div class="card">
        <h2>🎥 Видео-поздравление</h2>

        <video class="video" controls>
            <source src="video.mp4" type="video/mp4">
        </video>
    </div>
</section>

<section class="section">
    <div class="card">
        <h2>🌷 Пожелания</h2>
        <br>
        <p>
            ✨ Счастья каждый день<br>
            ✨ Крепкого здоровья<br>
            ✨ Улыбок и хорошего настроения<br>
            ✨ Исполнения всех мечтаний<br>
            ✨ Любви и семейного тепла
        </p>
    </div>
</section>

<footer>
    Сделано с любовью ❤️
</footer>

</body>
</html>
