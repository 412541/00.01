
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Ulang Tahun!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #fce4ec;
            background-image: url('https://cdn.pixabay.com/photo/2017/12/15/12/32/birthday-3021077_1280.jpg');
            background-size: cover;
            background-position: center;
        }
        .container {
            padding: 50px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            width: 80%;
            max-width: 600px;
            margin: 50px auto;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: #ff4081;
            font-size: 28px;
        }
        .link-container {
            margin: 20px 0;
        }
        a {
            display: inline-block;
            padding: 10px 15px;
            text-decoration: none;
            color: white;
            background-color: #ff4081;
            border-radius: 5px;
            font-size: 18px;
        }
        a:hover {
            background-color: #d81b60;
        }
        .decorations {
            position: absolute;
            width: 100%;
            top: 0;
            left: 0;
            pointer-events: none;
        }
        .balloons {
            position: absolute;
            width: 100%;
            height: 100%;
            overflow: hidden;
        }
        .balloon {
            position: absolute;
            width: 50px;
            height: 70px;
            background-color: red;
            border-radius: 50%;
            animation: floatUp 5s infinite linear;
        }
        @keyframes floatUp {
            from { transform: translateY(100vh); opacity: 1; }
            to { transform: translateY(-10vh); opacity: 0; }
        }
    </style>
</head>
<body>

    <div class="decorations">
        <div class="balloons">
            <div class="balloon" style="left: 10%; background-color: red; animation-duration: 6s;"></div>
            <div class="balloon" style="left: 30%; background-color: blue; animation-duration: 5s;"></div>
            <div class="balloon" style="left: 50%; background-color: green; animation-duration: 4s;"></div>
            <div class="balloon" style="left: 70%; background-color: yellow; animation-duration: 7s;"></div>
            <div class="balloon" style="left: 90%; background-color: purple; animation-duration: 6s;"></div>
        </div>
    </div>

    <div class="container">
        <h1>Selamat Ulang Tahun! 🎂🎉</h1>
        <p>Silakan klik tautan di bawah ini:</p>
        <div class="link-container">
            <a href="https://412541.github.io/2025/" target="_blank">🎁 Buka Hadiah Pertama</a>
        </div>
        <div class="link-container">
            <a href="https://gifft.me/o/b/2wi9iksfwd8kkxww194twj68" target="_blank">🎁 Buka Hadiah Kedua</a>
        </div>
    </div>

</body>
</html>
