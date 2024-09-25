<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Avukat Nural Kılıç</title>
    <style>
        :root {
            --font-size-large: 16px;
            --font-size-medium: 14px;
            --font-size-small: 12px;
            --font-size-xsmall: 10px;
            --font-size-xxsmall: 18px;
        }
        body {
            margin: 0;
            font-family: 'Garamond', 'Times New Roman', serif; /* Garamond benzeri fontları kullan */
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

        /* Hakkımızda bölümü */
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

        /* İhtisas Alanlarımız bölümü */
        .specialties {
            background-color: #C3B7EA;
            padding: 50px;
            text-align: center;
        }

        .specialties h2 {
            color: #000080;
            font-size: var(--font-size-large);
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

        /* Diğer Çalışma Alanlarımız bölümü */
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

        /* Müracaat Bölümü */
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
            font-size: var(--font-size-xsmall);
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
        <img src="images/header.jpg" alt="Header Görseli">
    </div>

    <!-- Hakkımızda Bölümü -->
    <section class="about">
        <img src="images/about.jpg" alt="Hakkımızda Görseli">
        <div class="about-text">
            <h2>Hakkımızda</h2>
            <p>Bizimle iletişime geçmek ve daha fazla bilgi almak için lütfen bizimle iletişime geçin.</p>
            <p>Yılların tecrübesi ve profesyonelliği ile sizlere en iyi hizmeti sunmayı hedefliyoruz.</p>
        </div>
    </section>

    <!-- İhtisas Alanlarımız Bölümü -->
    <section class="specialties">
        <h2>İhtisas Alanlarımız</h2>
        <div class="specialties-container">
            <div class="specialty-item">
                <img src="images/specialty1.jpg" alt="İhtisas Alanı 1">
                <p>Alan 1 Açıklaması</p>
            </div>
            <div class="specialty-item">
                <img src="images/specialty2.jpg" alt="İhtisas Alanı 2">
                <p>Alan 2 Açıklaması</p>
            </div>
            <div class="specialty-item">
                <img src="images/specialty3.jpg" alt="İhtisas Alanı 3">
                <p>Alan 3 Açıklaması</p>
            </div>
        </div>
    </section>

    <!-- Diğer Çalışma Alanlarımız Bölümü -->
    <section class="gallery">
        <h2>Diğer Çalışma Alanlarımız</h2>
        <div class="gallery-container">
            <img src="images/galeri1.jpg" alt="Çalışma Alanı 1">
            <img src="images/galeri2.jpg" alt="Çalışma Alanı 2">
            <img src="images/galeri3.jpg" alt="Çalışma Alanı 3">
            <img src="images/galeri4.jpg" alt="Çalışma Alanı 4">
            <img src="images/galeri5.jpg" alt="Çalışma Alanı 5">
            <img src="images/galeri6.jpg" alt="Çalışma Alanı 6">
            <img src="images/galeri7.jpg" alt="Çalışma Alanı 7">
            <img src="images/galeri8.jpg" alt="Çalışma Alanı 8">
            <img src="images/galeri9.jpg" alt="Çalışma Alanı 9">
        </div>
    </section>

    <!-- Müracaat Bölümü -->
    <section class="application">
        <div class="contact-info">
            <h2>Müracaat</h2>
            <p>Telefon ve e-posta yoluyla ulaşabilir yahut büromuzda veya çevrimiçi yollarla yüz yüze görüşebilirsiniz.</p>
            <p>Mesai saatlerimiz aşağıdaki gibidir. Vakti uymayacak danışanlarımız ortak müsait vaktin tayini için talepte bittabi bulunabilirler.</p>
            <p><strong>Av. Nural Kılıç</strong></p>
            <p><strong>Adres:</strong> İstanbul, Türkiye</p>
            <p><strong>E-posta:</strong> example@example.com</p>
            <div class="calendar">
                <h3>Mesai Saatleri:</h3>
                <p>Pazartesi-Salı: 07:00-19:00</p>
                <p>Çarşamba-Perşembe: 07:00-17:00</p>
                <p>Cuma: 07:00-11:00</p>
            </div>
            <button class="show-form-button" onclick="toggleForm()">Randevu Talebi</button>
            <div class="appointment-form" id="appointmentForm">
                <h2>Randevu Talebi Formu</h2>
                <form action="mailto:example@example.com" method="post" enctype="text/plain">
                    <label for="name">Adınız:</label>
                    <input type="text" id="name" name="name" required>
                    <label for="email">E-posta:</label>
                    <input type="email" id="email" name="email" required>
                    <label for="message">Mesaj:</label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                    <button type="submit">Gönder</button>
                </form>
            </div>
        </div>
        <div class="map">
            <!-- Harita yerleştirilecek alan -->
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">LinkedIn</a>
            <a href="#">Instagram</a>
        </div>
        <div class="contact-details">
            <p>İstanbul, Türkiye</p>
            <p>Telefon: (123) 456-7890</p>
            <p>E-posta: example@example.com</p>
        </div>
        <div class="copyright">
            TELİF HAKKI © 2024 AVUKAT NURAL KILIÇ - TÜM HAKLARI SAKLIDIR.
        </div>
    </footer>

    <script>
        function toggleForm() {
            var form = document.getElementById('appointmentForm');
            form.style.display = form.style.display === 'none' || form.style.display === '' ? 'block' : 'none';
        }
    </script>

</body>
</html>
