<!DOCTYPE html>
<html lang="tr">
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
            --font-size-xxsmall: 8px;
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
            display: none; /* Başlık kısmını kaldırdık */
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

        .about h2 {
            font-size: var(--font-size-large);
            text-transform: uppercase;
        }

        /* İHTİSAS ALANLARIMIZ bölümü */
        .specialties {
            background-color: #C3B7EA;
            padding: 50px;
            text-align: center;
        }

        .specialties h2 {
            color: #000080;
            font-size: var(--font-size-large);
            text-transform: uppercase;
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

        .specialty-item p {
            font-size: var(--font-size-small);
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
            text-transform: uppercase;
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
            text-transform: uppercase;
        }

        .contact-info p {
            font-size: var(--font-size-medium);
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
            font-size: var(--font-size-small);
        }

        .map {
            width: 45%;
            background-color: #C3B7EA;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <!-- İnce bar ve başlık -->
    <div class="top-bar">
        <!-- AVUKAT NURAL KILIÇ yazısı kaldırıldı -->
    </div>

    <!-- Header -->
    <div class="header">
        <img src="images/header.jpg" alt="Header Görseli">
    </div>

    <!-- Hakkımızda Bölümü -->
    <section class="about">
        <img src="images/about.jpg" alt="Hakkımızda Görseli">
        <div class="about-text">
            <h2>HAKKIMIZDA</h2>
            <p>Avukat Nural Kılıç ilk ve ortaöğrenimini Adana'da görmüş, İstanbul Üniversitesi Hukuk Fakültesi'nden mezun olmuştur. Yasal stajını tamamlayıp avukatlık ruhsatnamesini alarak kıdemli meslektaşlarının hukuk bürolarında tecrübe kazandıktan sonra vekillik mesleğini kendi namına yapmaya başlamıştır. Mesleğinin ilk yıllarından itibaren hak odaklı çalışmalarda da yer almaya çabalayan Kılıç, gerek Baro bünyesinde, gerek meslekî temsiliyetle kamu kurum ve kuruluşları, sivil toplum örgütleri ve özel hukuk kişileri ile bir arada, birçok çalışmada bulunmuştur. Halihazırda Türk Alman Üniversitesi Sosyal Bilimler Enstitüsü'nde Kamu Hukuku Yüksek Lisans Programı'nın tez aşamasındaki öğrencilerinden biridir. Almanca ve İngilizce bilir. İstanbul Barosu'nda 5 yıllık kıdemini tamamladıktan sonra, 7255 sicil numarasıyla naklolduğu Adana Barosu'nda, mesleğini, benimsediği değerlerden taviz vermemeye ve her gün kendini geliştirmeye çabalayarak sürdürür.</p>
        </div>
    </section>

    <!-- İhtisas Alanlarımız Bölümü -->
    <section class="specialties">
        <h2>İHTİSAS ALANLARIMIZ</h2>
        <div class="specialties-container">
            <div class="specialty-item">
                <img src="images/specialty1
