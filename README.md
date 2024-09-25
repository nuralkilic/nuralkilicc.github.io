<!DOCTYPE html>
<html lang="tr">
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
        <img src="images/2.png" alt="Header Görseli">
    </div>

    <!-- Hakkımızda Bölümü -->
    <section class="about">
        <img src="images/1726756804715.jpg" alt="Hakkımızda Görseli">
        <div class="about-text">
            <h2>Hakkımızda</h2>
            <p>Avukat Nural Kılıç ilk ve ortaöğrenimini Adana'da görmüş, İstanbul Üniversitesi Hukuk Fakültesi'nden mezun olmuştur. Yasal stajını tamamlayıp avukatlık ruhsatnamesini alarak kıdemli meslektaşlarının hukuk bürolarında tecrübe kazandıktan sonra vekillik mesleğini kendi namına yapmaya başlamıştır. Mesleğinin ilk yıllarından itibaren hak odaklı çalışmalarda da yer almaya çabalayan Kılıç, gerek Baro bünyesinde, gerek meslekî temsiliyetle kamu kurum ve kuruluşları, sivil toplum örgütleri ve özel hukuk kişileri ile bir arada, birçok çalışmada bulunmuştur. Halihazırda Türk Alman Üniversitesi Sosyal Bilimler Enstitüsü'nde Kamu Hukuku Yüksek Lisans Programı'nın tez aşamasındaki öğrencilerinden biridir. Almanca ve İngilizce bilir. İstanbul Barosu'nda 5 yıllık kıdemini tamamladıktan sonra, 7255 sicil numarasıyla naklolduğu Adana Barosu'nda, mesleğini, benimsediği değerlerden taviz vermemeye ve her gün kendini geliştirmeye çabalayarak sürdürür.</p>
        </div>
    </section>

    <!-- İhtisas Alanlarımız Bölümü -->
    <section class="specialties">
        <h2>İhtisas Alanlarımız</h2>
        <div class="specialties-container">
            <div class="specialty-item">
                <img src="images/idare.png" alt="İhtisas Alanı 1">
                <p>İdarî faaliyetler sebebiyle maruz kaldığınız haksızlıkların durdurulması, iptali ve bu bağlamda uğradığınız zararların tazmini için gerekli işleri, idârî başvurularınızın ilgili İdâre'ye (kamu kurum ve kuruluşları) yöneltilmesinden, iptal davalarına ve tam yargı davalarına kadar her aşamasını yürütüyoruz.</p>
            </div>
            <div class="specialty-item">
                <img src="images/bireyselbaşvuru.png" alt="İhtisas Alanı 2">
                <p>Bireysel başvuru olarak adlandırılan Anayasa Mahkemesi başvuruları, Avrupa İnsan Hakları Mahkemesi başvuruları ve İçtihatların denetlenmesi hizmetini de vermekteyiz.</p>
            </div>
            <div class="specialty-item">
                <img src="images/önleme.png" alt="İhtisas Alanı 3">
                <p>Sözleşmelerin hukuka uygun olarak hazırlanması, mahkemelerden ihtiyati tedbir kararlarının alınması ve uygulanması gibi hukuki önlemleri almakta, müvekkillerimizi en iyi şekilde temsil etmekteyiz.</p>
            </div>
        </div>
    </section>

    <!-- Diğer Çalışma Alanlarımız Bölümü -->
    <section class="gallery">
        <h2>DİĞER ÇALIŞMA ALANLARIMIZ</h2>
        <div class="gallery-container">
            <img src="images/1bilişim.png" alt="Çalışma Alanı 1">
            <img src="images/2imar.png" alt="Çalışma Alanı 2">
            <img src="images/3iş.png" alt="Çalışma Alanı 3">
            <img src="images/4kamuihale.png" alt="Çalışma Alanı 4">
            <img src="images/5ekonomiceza.png" alt="Çalışma Alanı 5">
            <img src="images/6çocuk.png" alt="Çalışma Alanı 6">
            <img src="images/7gayrimenkul.png" alt="Çalışma Alanı 7">
            <img src="images/8tazminat.png" alt="Çalışma Alanı 8">
            <img src="images/9sağlık.png" alt="Çalışma Alanı 9">
        </div>
    </section>

    <!-- Müracaat Bölümü -->
    <section class="application">
        <div class="contact-info">
            <h2>MÜRÂCAAT</h2>
            <p>Adana, Türkiye</p>
            <div class="contact-details">
                <span><strong>Adres:</strong> Örnek Mahalle, Örnek Sokak No: 1, Adana</span>
                <span><strong>Telefon:</strong> (0322) 000 00 00</span>
                <span><strong>Email:</strong> info@avukatnuralkilic.com</span>
            </div>
            <div class="calendar">
                <h3>Randevu Talebi</h3>
                <p>Randevu almak için lütfen <button class="show-form-button" onclick="document.querySelector('.appointment-form').style.display='block'">buraya tıklayın</button>.</p>
            </div>
            <div id="map" style="width: 100%; height: 300px;">
                <iframe src="https://maps.app.goo.gl/Su5JMy5Dwyz5Monn9" style="border:0; width: 100%; height: 100%;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>

        <!-- Randevu Talebi Formu -->
        <div class="appointment-form">
            <h2>Randevu Talebi Formu</h2>
            <form>
                <input type="text" name="name" placeholder="Adınız ve Soyadınız" required>
                <input type="text" name="address" placeholder="Adresiniz" required>
                <input type="tel" name="phone" placeholder="Telefon Numaranız" required>
                <textarea name="message" placeholder="Mesajınız" rows="4" required></textarea>
                <button type="submit">Gönder</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="social-media">
            <a href="#">Facebook</a> |
            <a href="#">Twitter</a> |
            <a href="#">LinkedIn</a>
        </div>
        <div class="contact-details">
            <p>Adana, Türkiye</p>
            <p>Email: info@avukatnuralkilic.com</p>
            <p>Telefon: (0322) 000 00 00</p>
        </div>
        <div class="copyright">
            &copy; 2024 Avukat Nural Kılıç. Tüm hakları saklıdır.
        </div>
    </footer>
    
</body>
</html>
