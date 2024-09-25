<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avukat Nural Kılıç</title>
    <style>
        body {
            font-family: Garamond, serif;
            background-color: #000000;
            color: #C3B7EA;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #000080;
            color: #C3B7EA;
            padding: 10px;
            text-align: center;
            position: relative;
        }
        .header img {
            max-width: 100%;
            height: auto;
        }
        .language-selector {
            position: absolute;
            top: 10px;
            right: 10px;
        }
        .language-selector button {
            background: none;
            border: 1px solid #C3B7EA;
            color: #C3B7EA;
            padding: 5px 10px;
            margin-left: 5px;
            cursor: pointer;
        }
        section {
            padding: 20px;
        }
        .about, .specialties, .gallery, .application {
            margin-bottom: 20px;
        }
        .about .left-column, .specialties .column, .gallery .row, .application .contact-info {
            margin-bottom: 10px;
        }
        .about .left-column, .specialties .column, .gallery .row, .application .contact-info {
            display: flex;
            flex-direction: column;
        }
        .about .right-column, .specialties .column, .application .map {
            flex: 1;
        }
        .gallery .row img {
            width: 100%;
            height: auto;
        }
        .footer {
            background-color: #000080;
            color: #C3B7EA;
            text-align: center;
            padding: 10px;
        }
        .footer .social-media a {
            color: #C3B7EA;
            margin: 0 5px;
            text-decoration: none;
        }
        .footer .contact-details, .footer .copyright {
            margin-top: 10px;
        }
        .footer .copyright {
            font-size: 0.8em;
        }
        .application .appointment-form {
            display: none;
            background-color: #C3B7EA;
            color: #000080;
            padding: 10px;
            border: 1px solid #000080;
            margin-top: 10px;
        }
        .application .appointment-form input, .application .appointment-form textarea {
            width: 100%;
            margin-bottom: 10px;
        }
        .application .appointment-form button {
            background-color: #000080;
            color: #C3B7EA;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header class="header">
        <h1>Avukat Nural Kılıç</h1>
        <div class="language-selector">
            <button onclick="changeLanguage('tr')">Türkçe</button>
            <button onclick="changeLanguage('en')">English</button>
            <button onclick="changeLanguage('de')">Deutsch</button>
        </div>
        <img src="images/header.jpg" alt="Header Image">
    </header>

    <section class="about">
        <div class="left-column">
            <h2 id="about-title">Hakkımızda</h2>
            <p id="about-text">Bu kısımda şirketinize dair genel bilgiler yer alacak.</p>
        </div>
        <div class="right-column">
            <img src="images/about.jpg" alt="About Image">
        </div>
    </section>

    <section class="specialties">
        <h2 id="specialties-title">İhtisas Alanlarımız</h2>
        <div class="column">
            <img src="images/specialty1.jpg" alt="Specialty 1">
            <p id="specialty1-text">İhtisas Alanı 1 açıklaması</p>
        </div>
        <div class="column">
            <img src="images/specialty2.jpg" alt="Specialty 2">
            <p id="specialty2-text">İhtisas Alanı 2 açıklaması</p>
        </div>
        <div class="column">
            <img src="images/specialty3.jpg" alt="Specialty 3">
            <p id="specialty3-text">İhtisas Alanı 3 açıklaması</p>
        </div>
    </section>

    <section class="gallery">
        <h2 id="gallery-title">Diğer Çalışma Alanlarımız</h2>
        <div class="row">
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

    <section class="application">
        <div class="contact-info">
            <h2 id="contact-title">Müracaat</h2>
            <p id="contact-text">Telefon ve e-posta yoluyla ulaşabilir yahut büromuzda veya çevrimiçi yollarla yüz yüze görüşebilirsiniz.</p>
            <p id="contact-hours">Mesai saatlerimiz aşağıdaki gibidir. Vakti uymayacak danışanlarımız ortak müsait vaktin tayini için talepte bittabi bulunabilirler.</p>
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
        const translations = {
            tr: {
                aboutTitle: "Hakkımızda",
                aboutText: "Bu kısımda şirketinize dair genel bilgiler yer alacak.",
                specialtiesTitle: "İhtisas Alanlarımız",
                specialty1Text: "İhtisas Alanı 1 açıklaması",
                specialty2Text: "İhtisas Alanı 2 açıklaması",
                specialty3Text: "İhtisas Alanı 3 açıklaması",
                galleryTitle: "Diğer Çalışma Alanlarımız",
                contactTitle: "Müracaat",
                contactText: "Telefon ve e-posta yoluyla ulaşabilir yahut büromuzda veya çevrimiçi yollarla yüz yüze görüşebilirsiniz.",
                contactHours: "Mesai saatlerimiz aşağıdaki gibidir. Vakti uymayacak danışanlarımız ortak müsait vaktin tayini için talepte bittabi bulunabilirler."
            },
            en: {
                aboutTitle: "About Us",
                aboutText: "This section will contain general information about the company.",
                specialtiesTitle: "Our Specialties",
                specialty1Text: "Specialty Area 1 description",
                specialty2Text: "Specialty Area 2 description",
                specialty3Text: "Specialty Area 3 description",
                galleryTitle: "Other Areas of Work",
                contactTitle: "Contact",
                contactText: "You can reach us by phone or email, or meet us in person at our office or online.",
                contactHours: "Our working hours are as follows. Clients who cannot fit within these hours can request to arrange a suitable time."
            },
            de: {
                aboutTitle: "Über uns",
                aboutText: "In diesem Abschnitt finden Sie allgemeine Informationen über das Unternehmen.",
                specialtiesTitle: "Unsere Fachgebiete",
                specialty1Text: "Fachgebiet 1 Beschreibung",
                specialty2Text: "Fachgebiet 2 Beschreibung",
                specialty3Text: "Fachgebiet 3 Beschreibung",
                galleryTitle: "Weitere Arbeitsbereiche",
                contactTitle: "Kontakt",
                contactText: "Sie können uns telefonisch oder per E-Mail erreichen oder uns persönlich in unserem Büro oder online treffen.",
                contactHours: "Unsere Arbeitszeiten sind wie folgt. Kunden, die außerhalb dieser Zeiten keine Termine finden können, können einen geeigneten Zeitpunkt anfragen."
            }
        };

        function changeLanguage(lang) {
            document.getElementById('about-title').innerText = translations[lang].aboutTitle;
            document.getElementById('about-text').innerText = translations[lang].aboutText;
            document.getElementById('specialties-title').innerText = translations[lang].specialtiesTitle;
            document.getElementById('specialty1-text').innerText = translations[lang].specialty1Text;
            document.getElementById('specialty2-text').innerText = translations[lang].specialty2Text;
            document.getElementById('specialty3-text').innerText = translations[lang].specialty3Text;
            document.getElementById('gallery-title').innerText = translations[lang].galleryTitle;
            document.getElementById('contact-title').innerText = translations[lang].contactTitle;
            document.getElementById('contact-text').innerText = translations[lang].contactText;
            document.getElementById('contact-hours').innerText = translations[lang].contactHours;
        }

        function toggleForm() {
            const form = document.getElementById('appointmentForm');
            form.style.display = form.style.display === 'none' ? 'block' : 'none';
        }

        // Varsayılan dil Türkçe olarak ayarlama
        changeLanguage('tr');
    </script>

</body>
</html>
