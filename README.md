# nuralkilic.github.io
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Avukat Nural Kılıç</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
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
        }

        .contact-form {
            width: 45%;
            background-color: #C3B7EA;
            padding: 20px;
            border-radius: 10px;
        }

        .contact-form h2 {
            color: #000080;
            font-size: 24px;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #000080;
        }

        .contact-form button {
            width: 100%;
            padding: 10px;
            background-color: #000080;
            color: #C3B7EA;
            border: none;
            border-radius: 5px;
            font-size: 16px;
        }

        .map {
            width: 45%;
            text-align: center;
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
    </style>
</head>
<body>

    <!-- Üstteki İnce Bar -->
    <div class="top-bar">
        AVUKAT NURAL KILIÇ
    </div>

    <!-- Header İmajı -->
    <div class="header">
        <img src="header-image.jpg" alt="Header" width="100%" height="300px">
    </div>

    <!-- Hakkımızda Bölümü -->
    <section class="about">
        <img src="about-image.jpg" alt="Hakkımızda Fotoğrafı">
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
                <img src="alan1.jpg" alt="Alan 1">
                <p>İhtisas Alanı 1 hakkında açıklama.</p>
            </div>
            <div class="specialty-item">
                <img src="alan2.jpg" alt="Alan 2">
                <p>İhtisas Alanı 2 hakkında açıklama.</p>
            </div>
            <div class="specialty-item">
                <img src="alan3.jpg" alt="Alan 3">
                <p>İhtisas Alanı 3 hakkında açıklama.</p>
            </div>
        </div>
    </section>

    <!-- Diğer Çalışma Alanlarımız Bölümü -->
    <section class="gallery">
        <h2>Diğer Çalışma Alanlarımız</h2>
        <div class="gallery-container">
            <img src="galeri1.jpg" alt="Çalışma Alanı 1">
            <img src="galeri2.jpg" alt="Çalışma Alanı 2">
            <img src="galeri3.jpg" alt="Çalışma Alanı 3">
            <img src="galeri4.jpg" alt="Çalışma Alanı 4">
            <img src="galeri5.jpg" alt="Çalışma Alanı 5">
            <img src="galeri6.jpg" alt="Çalışma Alanı 6">
            <img src="galeri7.jpg" alt="Çalışma Alanı 7">
            <img src="galeri8.jpg" alt="Çalışma Alanı 8">
            <img src="galeri9.jpg" alt="Çalışma Alanı 9">
        </div>
    </section>

    <!-- Müracaat Bölümü -->
    <section class="application">
        <div class="contact-form">
            <h2>Müracaat</h2>
            <input type="text" placeholder="İsim">
            <input type="text" placeholder="Adres">
            <input type="email" placeholder="E-posta">
            <input type="tel" placeholder="Telefon">
            <textarea rows="4" placeholder="Mesajınız"></textarea>
            <button>Randevu Talebi</button>
        </div>
        <div class="map">
            <!-- Harita burada yer alacak -->
            <h2>Konumumuz</h2>
            <iframe src="https://www.google.com/maps/embed" width="100%" height="300px" style="border:0;" allowfullscreen></iframe>
        </div>
    </section>

    <!-- Footer Bölümü -->
    <div class="footer">
        <a href="#">Facebook</a>
        <a href="#">Twitter</a>
        <a href="#">LinkedIn</a>
        <p>Avukat Nural Kılıç - Adres Bilgileri</p>
        <p>Telefon: +90 555 555 55 55</p>
        <div class="copyright">
            TELİF HAKKI © 2024 AVUKAT NURAL KILIÇ - TÜM HAKLARI SAKLIDIR.
        </div>
    </div>

</body>
</html>
