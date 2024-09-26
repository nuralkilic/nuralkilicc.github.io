<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Avukat Nural Kılıç</title>
    <style>
        :root {
            --font-size-large: 14px;
            --font-size-medium: 12px;
            --font-size-small: 10px;
            --font-size-xsmall: 8px;
            --font-size-xxsmall: 7px;
        }
        body {
            margin: 0;
            font-family: 'Garamond', 'Times New Roman', serif;
            background-color: #333; /* Füme zemin */
            color: #000080; /* Metin rengi */
            font-size: var(--font-size-small); /* Varsayılan yazı boyutu */
        }

        /* İnce bar ve başlık */
        .top-bar {
            background-color: #000;
            padding: 10px;
            color: #C3B7EA;
            font-size: var(--font-size-medium);
            text-align: left;
        }

        /* Header için */
        .header {
            text-align: center;
            margin-top: 20px;
        }

        .header img {
            width: 100%;
            height: auto; /* Görselin oranlarını korur */
            max-height: 300px; /* İsteğe bağlı, yüksekliği sınırlamak için */
        }

        /* HAKKIMIZDA bölümü */
        .about {
            background-color: #C3B7EA;
            padding: 50px;
            display: flex;
            justify-content: space-between;
        }

        .about img {
            width: 45%;
            border-radius: 10px;
        }

        .about-text {
            color: #000080;
            font-size: var(--font-size-medium);
            width: 45%;
        }

        /* İHTİSAS ALANLARIMIZ bölümü */
        .specialties {
            background-color: #C3B7EA;
            padding: 50px;
            text-align: center;
        }

        .specialties h2 {
            color: #000080;
            font-size: var(--font-size-medium);
        }

        .specialties-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .specialty-item {
            text-align: center;
        }

        .specialty-item img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        /* DİĞER ÇALIŞMA ALANLARIMIZ bölümü */
        .gallery {
            background-color: #C3B7EA;
            padding: 50px;
            text-align: center;
        }

        .gallery h2 {
            color: #000080;
            font-size: var(--font-size-large);
        }

        .gallery-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
        }

        .gallery-container img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
        }

        /* MÜRÂCAAT Bölümü */
        .application {
            background-color: #C3B7EA;
            padding: 50px;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }

        .contact-info {
            width: 45%;
            background-color: #C3B7EA;
            padding: 20px;
            border-radius: 10px;
            margin-right: 20px;
        }

        .contact-info h2 {
            color: #000080;
            font-size: var(--font-size-large);
        }

        .contact-info p {
            font-size: var(--font-size-small);
            margin: 10px 0;
        }

        .contact-info .contact-details {
            margin: 20px 0;
        }

        .contact-info .contact-details span {
            display: block;
            margin-bottom: 10px;
        }

        .contact-info .contact-details span strong {
            color: #000080;
        }

        .contact-info .calendar {
            background-color: #C3B7EA;
            padding: 10px;
            border-radius: 5px;
        }

        .contact-info .calendar h3 {
            color: #000080;
            font-size: var(--font-size-medium);
        }

        .contact-info .calendar p {
            font-size: var(--font-size-medium);
            margin: 5px 0;
        }

        /* Randevu talebi formu */
        .appointment-form {
            display: none; /* Form başlangıçta gizli */
            background-color: #C3B7EA;
            padding: 20px;
            border-radius: 10px;
            width: 100%;
            max-width: 600px;
            margin-top: 20px;
        }

        .appointment-form h2 {
            color: #000080;
            font-size: var(--font-size-large);
        }

        .appointment-form input, .appointment-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #000080;
        }

        .appointment-form button {
            width: 100%;
            padding: 10px;
            background-color: #000080;
            color: #C3B7EA;
            border: none;
            border-radius: 5px;
            font-size: var(--font-size-small);
        }

        .show-form-button {
            padding: 10px;
            background-color: #000080;
            color: #C3B7EA;
            border: none;
            border-radius: 5px;
            font-size: var(--font-size-small);
            cursor: pointer;
        }

        /* Footer */
        .footer {
            background-color: #000;
            color: #C3B7EA;
            padding: 20px;
            text-align: center;
        }

        .footer .social-media a {
            color: #C3B7EA;
            margin: 0 10px;
            text-decoration: none;
        }

        .footer .contact-details p {
            margin: 5px 0;
        }

        .footer .copyright {
            font-size: var(--font-size-xxsmall);
        }
    </style>
</head>
<body>

    <!-- İnce bar ve başlık -->
    <div class="top-bar">
        AVUKAT NURAL KILIÇ
    </div>

    <!-- Header -->
    <div class="header">
        <img src="assets/images/header.jpg" alt="Header Görseli">
    </div>

    <!-- Hakkımızda Bölümü -->
    <section class="about">
        <img src="assets/images/about.jpg" alt="Hakkımızda Görseli">
        <div class="about-text">
            <h2>Hakkımızda</h2>
            <p>Avukat Nural Kılıç ilk ve ortaöğrenimini Adana'da görmüş, İstanbul Üniversitesi Hukuk Fakültesi'nden mezun olmuştur...</p>
        </div>
    </section>

    <!-- İhtisas Alanlarımız Bölümü -->
    <section class="specialties">
        <h2>İhtisas Alanlarımız</h2>
        <div class="specialties-container">
            <div class="specialty-item">
                <img src="assets/images/specialty1.jpg" alt="İhtisas Alanı 1">
                <p>İdarî faaliyetler sebebiyle maruz kaldığınız haksızlıkların...</p>
            </div>
            <div class="specialty-item">
                <img src="assets/images/specialty2.jpg" alt="İhtisas Alanı 2">
                <p>Anayasa Mahkemesi, Kamu Denetçiliği Kurumu, TİHEK ve Avrupa İnsan Hakları...</p>
            </div>
            <div class="specialty-item">
                <img src="assets/images/specialty3.jpg" alt="İhtisas Alanı 3">
                <p>Hukuksal Danışmanlık Hizmetleri</p>
            </div>
        </div>
    </section>

    <!-- Diğer Çalışma Alanlarımız Bölümü -->
    <section class="gallery">
        <h2>Diğer Çalışma Alanlarımız</h2>
        <div class="gallery-container">
            <img src="assets/images/gallery1.jpg" alt="Gallery Image 1">
            <img src="assets/images/gallery2.jpg" alt="Gallery Image 2">
            <img src="assets/images/gallery3.jpg" alt="Gallery Image 3">
        </div>
    </section>

    <!-- Müracaat Bölümü -->
    <section class="application">
        <div class="contact-info">
            <h2>İletişim Bilgileri</h2>
            <div class="contact-details">
                <span><strong>Adres:</strong> Example Address</span>
                <span><strong>Telefon:</strong> +90 (216) 123 45 67</span>
                <span><strong>E-posta:</strong> example@example.com</span>
            </div>
            <div class="calendar">
                <h3>Çalışma Saatlerimiz</h3>
                <p>Pazartesi - Cuma: 09:00 - 18:00</p>
                <p>Cumartesi: 10:00 - 14:00</p>
            </div>
        </div>
        <div class="appointment">
            <button class="show-form-button" onclick="showForm()">RANDEVU TALEBİ</button>
            <div class="appointment-form" id="appointment-form">
                <h2>Randevu Talebi</h2>
                <form action="">
                    <input type="text" name="name" placeholder="Adınız" required>
                    <input type="email" name="email" placeholder="E-posta" required>
                    <textarea name="message" rows="4" placeholder="Mesajınız" required></textarea>
                    <button type="submit">Gönder</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="social-media">
            <a href="#">Twitter</a>
            <a href="#">LinkedIn</a>
        </div>
        <div class="contact-details">
            <p>Example Address</p>
            <p>Phone: +90 (216) 123 45 67</p>
        </div>
        <div class="copyright">
            &copy; 2024 Avukat Nural Kılıç - Tüm Hakları Saklıdır.
        </div>
    </footer>

    <script>
        function showForm() {
            var form = document.getElementById("appointment-form");
            if (form.style.display === "block") {
                form.style.display = "none";
            } else {
                form.style.display = "block";
            }
        }
    </script>
</body>
