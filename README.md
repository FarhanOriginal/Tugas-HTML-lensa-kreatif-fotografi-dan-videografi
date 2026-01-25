<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Lensa Kreatif | Studio Fotografi & Videografi</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #111;
            color: #fff;
        }
        header {
            background: #000;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            color: #f5c542;
        }
        nav a {
            color: white;
            margin-left: 20px;
            text-decoration: none;
        }
        nav a:hover {
            color: #f5c542;
        }
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: linear-gradient(to right, #000, #222);
        }
        .hero h2 {
            font-size: 36px;
            margin-bottom: 10px;
        }
        .section {
            padding: 60px 20px;
            text-align: center;
        }
        .services {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            background: #222;
            padding: 20px;
            width: 250px;
            border-radius: 10px;
        }
        footer {
            background: #000;
            padding: 20px;
            text-align: center;
            font-size: 14px;
        }
        button {
            padding: 10px 20px;
            background: #f5c542;
            border: none;
            cursor: pointer;
            font-weight: bold;
        }
        button:hover {
            background: #ffd966;
        }
    </style>
</head>
<body>

<header>
    <h1>Lensa Kreatif</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Tentang</a>
        <a href="#services">Layanan</a>
        <a href="#contact">Kontak</a>
    </nav>
</header>

<section class="hero" id="home">
    <h2>Studio Fotografi & Videografi</h2>
    <p>Mengabadikan momen dengan sentuhan kreatif</p>
    <br>
    <button onclick="hubungi()">Hubungi Kami</button>
</section>

<section class="section" id="about">
    <h2>Tentang Kami</h2>
    <p>
        Lensa Kreatif adalah studio fotografi dan videografi profesional
        yang melayani foto produk, prewedding, event, dan video cinematic.
    </p>
</section>

<section class="section" id="services">
    <h2>Layanan Kami</h2>
    <div class="services">
        <div class="card">
            <h3>Fotografi</h3>
            <p>Foto produk, potret, event, dan dokumentasi</p>
        </div>
        <div class="card">
            <h3>Videografi</h3>
            <p>Video cinematic, promosi, dan dokumenter</p>
        </div>
        <div class="card">
            <h3>Editing</h3>
            <p>Photo retouch & video editing profesional</p>
        </div>
    </div>
</section>

<section class="section" id="contact">
    <h2>Kontak</h2>
    <p>Email: Far34537@gmail.com</p>
    <p>WhatsApp: 08xxxxxxxxxx</p>
</section>

<footer>
    © 2026 Lensa Kreatif Studio
</footer>

<script>
    function hubungi() {
        alert("Silakan hubungi kami melalui WhatsApp atau Email 😊");
    }
</script>

</body>
</html>
