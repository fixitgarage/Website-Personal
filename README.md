<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mr. Fix it Garage</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            position: relative;
            background: url('images/car-service.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5); /* Overlay warna gelap */
            z-index: 0;
        }
        header h1, header p {
            position: relative;
            z-index: 1; /* Pastikan teks berada di atas overlay */
        }
        header h1 {
            font-size: 2.5em;
            margin: 0;
        }
        nav {
            background-color: #333;
            padding: 10px;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            font-size: 1.1em;
        }
        nav ul li a:hover {
            color: #ff9800;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .service-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .service-card img {
            width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mr. Fix it Garage</h1>
        <p>Solusi Terbaik untuk Semua Permasalahan Kendaraan Anda</p>
    </header>
    <nav>
        <ul>
            <li><a href="#services">Layanan</a></li>
            <li><a href="#about">Tentang Kami</a></li>
            <li><a href="#contact">Hubungi Kami</a></li>
        </ul>
    </nav>
    <section id="services">
        <h2>Layanan Kami</h2>
        <div class="services">
            <div class="service-card">
                <a href="Perbaikan Engine.html">
                    <img src="https://img.freepik.com/premium-photo/hands-engine_960080-9394.jpg" alt="Perbaikan Mesin">
                    <h3>Perbaikan Mesin</h3>
                    <p>Layanan profesional untuk memastikan mesin mobil Anda tetap optimal.</p>
                </a>
            </div>
            <div class="service-card">
                <a href="Perbaikan Rem.html">
                    <img src="https://www.autocar.co.uk/sites/autocar.co.uk/files/styles/gallery_slide/public/images/car-reviews/first-drives/legacy/litchfield-bmw-m2-fitting-the-exhaust.jpg?itok=AEBh-FAo.jpg" alt="Perbaikan Rem">
                    <h3>Perbaikan Rem</h3>
                    <p>Pastikan keamanan Anda dengan perbaikan rem yang berkualitas.</p>
                </a>
            </div>
            <div class="service-card">
                <a href="penggantian oli.html">
                    <img src="https://th.bing.com/th/id/OIP.AQAWr6RN-4O7d7kttaLYJgHaE8?rs=1&pid=ImgDetMain.jpg" alt="Penggantian Oli">
                    <h3>Penggantian Oli</h3>
                    <p>Penggantian oli berkualitas untuk menjaga performa mesin kendaraan Anda.</p>
                </a>
            </div>
        </div>
    </section>
    <section id="about">
        <h2>Tentang Kami</h2>
        <p>Mr. Fix it Garage adalah bengkel terpercaya yang menawarkan layanan perbaikan kendaraan berkualitas tinggi dengan teknisi berpengalaman.</p>
    </section>
    <section id="contact">
        <h2>Hubungi Kami</h2>
        <p>Alamat: Griya Karangjati Permai RT.08 RW.10 Dusun Jetak Kec. Pandaan Kab. Pasuruan Jawa Timur 67156</p>
        <p>Email: am0052618@gmail.com</p>
        <p>Telepon: 081217069794</p>
    </section>
    <footer>
        <p>&copy; 2025 Mr. Fix it Garage. Hak Cipta Dilindungi.</p>
    </footer>
	 <form action="penggantian oli.html" method="post">

</body>
</html>
