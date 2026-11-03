# pengenalan-diri

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Pengenalan Diri</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Halo, Saya Rais!</h1>
        <p>Selamat Datang di Website Pengenalan Diri Saya</p>
        <button onclick="sapa()">Kenali Saya</button>
    </header>

    <section class="container">
        <h2>Tentang Saya</h2>
        <p>
            Halo! Nama saya Rais. Saya adalah seorang pelajar
            yang senang belajar dan mencoba hal-hal baru.
        </p>

        <h2>Biodata</h2>
        <p>Nama: Rais Sugara</p>
        <p>Status: Pelajar</p>
        <p>Asal: Indonesia</p>

        <h2>Hobi Saya</h2>
        <p>Mendengarkan musik, bermain game, dan berolahraga.</p>

        <h2>Cita-Cita</h2>
        <p>Saya ingin menjadi orang sukses dan membanggakan orang tua.</p>

        <button onclick="tampilkanPesan()">
            Klik Pesan
        </button>
        <p id="pesan"></p>
    </section>

    <footer>
        <p>&copy; 2026 Website Pengenalan Diri</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
