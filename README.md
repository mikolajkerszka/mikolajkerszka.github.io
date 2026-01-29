<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MIG-TOP - Profesjonalne usługi spawalnicze</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <script>
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth'});
            document.getElementById(sectionId).style.backgroundColor = 'rgba(0, 0, 0, 0.2)';
            document.getElementById(sectionId).style.transition = 'background-color 0.5s ease';
            setTimeout(function() {
                document.getElementById(sectionId).style.backgroundColor = 'transparent';
                document.getElementById(sectionId).style.transition = 'all 0.2s';
            }, 1000);
        }
    </script>
</head>
<body>
    <div class="nav">
        <div class="nav-btn">
            <div class="btn" onclick="scrollToSection('about')">O NAS</div>
            <div class="btn" onclick="scrollToSection('skills')">UMIEJĘTNOŚCI</div>
            <div class="btn" onclick="scrollToSection('certificates')">CERTYFIKATY</div>
            <div class="btn" onclick="scrollToSection('contact')">KONTAKT</div>
        </div>
        <div class="nav-logo">MIG-TOP</div>
    </div>
    <div class="ellipse">
        <div class="about" id="about">
            <div class="title">O NAS</div>
            <div class="text">
                Oferujemy kompleksowe spawanie metodami MIG/MAG oraz TIG. Specjalizujemy się w łączeniu stali czarnej, nierdzewnej i aluminium, gwarantując najwyższą precyzję oraz trwałość spoin dla przemysłu i klientów indywidualnych. Łączymy wieloletnie doświadczenie z nowoczesną technologią. Realizujemy zarówno skomplikowane konstrukcje stalowe, jak i precyzyjne naprawy
            </div>
        </div>
    </div>
    <div class="image">
        <img src="images/welder.png" alt=""></img>
    </div>
    <div class="skills" id="skills">
        <div class="title">UMIEJĘTNOŚCI</div>
        <div class="text">
            <ul>
                <li>Biegłośc w spawaniu metodami MIG/MAG oraz TIG</li>
                <li>Czytanie rysunku technicznego</li>
                <li>Przygotowanie materiałów i obróbka wykończeniowa</li>
                <li>Znajomość materiałoznawstwa</li>
                <li>Kontrola jakości i przestrzeganie norm BHP</li>
            </ul>
        </div>
    </div>
    <div class="certificates" id="certificates">
        <div class="title">CERTYFIKATY</div>
        <div class="text">
            <ul>
                <li>Świadectwo Egzaminu Spawacza wg EN ISO 9606-1</li>
                <li>Certyfikat ASME Section IX</li>
                <li>Uprawnienia Ciśnieniowe PED</li>
                <li>Certyfikat Kompetencji NDT</li>
                <li>Certyfikat Bezpieczeństwa SCC / VCA</li>
            </ul>
        </div>
    </div>
    </div>
    <div class="footer">
        <div class="contact" id="contact">
            <div class="c-title">KONTAKT</div>
            <div class="text">
                <a href="tel:+48123456789"><p><span class="material-symbols-outlined">phone_in_talk</span> +48 123 456 789</p></a>
                <a href="mailto:mig-top@gmail.com"><p><span class="material-symbols-outlined">mail</span> mig-top@gmail.com</p></a>
            </div>
        </div>
        <div class="copyright">© Wszystkie prawa zastrzeżone.</div>
    </div>
</body>
</html>
