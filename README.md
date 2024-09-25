<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Avukat Nural Kılıç</title>
    <link href="https://fonts.googleapis.com/css2?family=Tarif:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Tarif', sans-serif; /* Tarif fontunu kullan */
            background-color: #333; /* Füme zemin */
            color: #000080; /* Metin rengi */
        }

        /* İnce bar ve başlık */
        .top-bar {
            background-color: #000;
            padding: 10px;
            color: #C3B7EA;
            font-size: 20px;
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
            font-size: 18px;
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
            font-size: 24px;
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
            font-size: 24px;
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

        /* Müracaat bölümü */
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
            font-size: 24px;
        }

        .contact-info p {
            font-size: 16px;
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
            font-size: 16px;
        }

        .contact-info .calendar p {
            font-size: 14px;
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
            font-size: 24px;
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
            font-size: 16px;
        }

        .show-form-button {
            padding: 10px;
            background-color: #000080;
            color: #C3B7EA;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 10px;
        }

        /* Footer ve alt kısımlar */
        .footer {
            background-color: #000;
            color: #C3B7EA;
            padding: 20px;
            text-align: center;
        }

        .footer a {
            color: #C3B7EA;
            margin: 0 10px;
        }

        .copyright {
            font-size: 12px;
            margin-top: 10px;
        }

        /* Harita için stil */
        .map {
            width: 45%;
            height: 300px; /* Yüksekliği ayarlayın */
            background-color: #fff; /* Harita için arka plan rengi */
            border-radius: 10px;
        }

        /* Buton ve form yüksekliği */
        .form-container {
            margin-top: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- Üstteki İnce Bar -->
    <div class="top-bar">
        AVUKAT NURAL KILIÇ
    </div>

    <!-- Header İmajı -->
    <div class="header">
        <img src="images/2.png" alt="Header">
    </div>

    <!-- Hakkımızda Bölümü -->
    <section class="about">
        <img src="images/about-image.jpg" alt="Hakkımızda Fotoğrafı">
        <div class="about-text">
            <h2>Hakkımızda</h2>
            <p>Bu kısma hakkınızda metni ekleyebilirsiniz. Avukatlık kariyeriniz, çalışma prensipleriniz ve diğer bilgileri buraya yazabilirsiniz.</p>
        </div>
    </section>

    <!-- İhtisas Alanlarımız Bölümü -->
    <section class="specialties">
        <h2>İhtisas Alanlarımız</h2>
        <div class="specialties-container">
            <div class="specialty-item">
                <img src="images/alan1.jpg" alt="Alan 1">
                <p>İhtisas Alanı 1 hakkında açıklama.</p>
            </div>
            <div class="specialty-item">
                <img src="images/alan2.jpg" alt="Alan 2">
                <p>İhtisas Alanı 2 hakkında açıklama.</p>
            </div>
            <div class="specialty-item">
                <img src="images/alan3.jpg" alt="Alan 3">
                <p>İhtisas Alanı 3 hakkında açıklama.</p>
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
            <p><strong>Adres:</strong> Örnek Mahalle, Örnek Cadde, No:1, İstanbul</p>
            <p><strong>E-posta:</strong> email@example.com</p>

            <div class="calendar">
                <h3>Mesai Saatleri</h3>
                <p>Pazartesi-Salı: 07:00-19:00</p>
                <p>Çarşamba-Perşembe: 07:00-17:00</p>
                <p>Cuma: 07:00-11:00</p>
            </div>
        </div>
        <div class="map">
            <!-- Harita kodu buraya eklenecek -->
        </div>
    </section>

    <!-- Randevu Talebi Butonu ve Formu -->
    <div class="form-container">
        <button class="show-form-button" onclick="toggleForm()">RANDEVU TALEBİ</button>
        <div class="appointment-form" id="appointment-form">
            <h2>Randevu Talebi</h2>
            <form action="mailto:email@example.com" method="post" enctype="text/plain">
                <label for="name">İsim:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">E-posta:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Mesaj:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                <button type="submit">Gönder</button>
            </form>
        </div>
    </div>

    <!-- Footer -->
    <div class="footer">
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">LinkedIn</a>
        </div>
        <div class="contact-details">
            <p>Avukat Nural Kılıç</p>
            <p>Adres: Örnek Mahalle, Örnek Cadde, No:1, İstanbul</p>
            <p>Telefon: +90 555 555 55 55</p>
        </div>
        <div class="copyright">
            TELİF HAKKI © 2024 AVUKAT NURAL KILIÇ - TÜM HAKLARI SAKLIDIR.
        </div>
    </div>

    <script>
        function toggleForm() {
            var form = document.getElementById('appointment-form');
            if (form.style.display === 'none' || form.style.display === '') {
                form.style.display = 'block';
            } else {
                form.style.display = 'none';
            }
        }
    </script>

</body>
</html>
