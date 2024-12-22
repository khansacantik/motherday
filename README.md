<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Hari Ibu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Selamat Hari Ibu!</h1>
        </header>
        <section class="content">
            <div class="love-icon" id="love-icon">❤️</div>
            <p id="love-text">Klik love ini</p>
        </section>
    </div>
    <script src="script.js"></script>
</body>
</html>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: url('6.jpg') ;
    background-size: cover;
    text-align: center;
}

.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: rgba(255, 255, 255, 0.8);
    border-radius: 8px;
}

header {
    background-color: #ffcccc;
    padding: 20px 0;
    margin-bottom: 20px;
    border-radius: 8px;
}

h1 {
    color: #d9534f;
    font-size: 2.5em;
    margin: 0;
}

.love-icon {
    font-size: 3em;
    cursor: pointer;
    transition: transform 0.3s, color 0.3s;
}

.love-icon:hover {
    transform: scale(1.2);
    color: #d9534f;
}

#love-text {
    color: #333;
    font-size: 1.2em;
    margin-top: 10px;
}
</style>
