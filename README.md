<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>GartenAndBaumSerwis - Usługi ogrodnicze i pielęgnacja ogrodów</title>
<style>
  body {
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    background: #e9f1e7;
    color: #2f4f2f;
    margin: 0;
    padding: 0;
  }
  header {
    background-color: #3a6d3a;
    color: white;
    padding: 20px 10px;
    text-align: center;
    font-size: 2rem;
    letter-spacing: 1px;
  }
  nav {
    background: #2a512a;
    display: flex;
    justify-content: center;
    gap: 25px;
    padding: 12px 0;
  }
  nav a {
    color: #cde6cd;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1rem;
  }
  nav a:hover {
    color: #a4d5a4;
    border-bottom: 2px solid #a4d5a4;
  }
  main {
    max-width: 900px;
    margin: 30px auto;
    padding: 0 15px;
  }
  section {
    margin-bottom: 40px;
  }
  h2 {
    border-bottom: 2px solid #3a6d3a;
    padding-bottom: 8px;
    margin-bottom: 15px;
  }
  ul.services-list {
    list-style-type: disc;
    padding-left: 20px;
  }
  footer {
    background: #3a6d3a;
    color: white;
    text-align: center;
    padding: 15px 10px;
    font-size: 0.9rem;
  }
  @media (max-width: 600px) {
    header {
      font-size: 1.5rem;
      padding: 15px 5px;
    }
    nav {
      flex-direction: column;
      gap: 12px;
    }
  }
</style>
</head>
<body>
<header>
  GartenAndBaumSerwis
</header>
<nav>
  <a href="index.html">Strona główna</a>
  <a href="cennik.html">Cennik</a>
  <a href="#kontakt">Kontakt</a>
</nav>
<main>
  <section id="oferta">
    <h2>Nasza oferta</h2>
    <p>Profesjonalna pielęgnacja Twojego ogrodu i drzew – od przycinania po kompleksową opiekę przez cały rok.</p>
    <ul class="services-list">
      <li>Pielęgnacja trawników i rabat</li>
      <li>Przycinanie drzew i krzewów</li>
      <li>Odchwaszczanie i nawożenie</li>
      <li>Zakładanie nowych nasadzeń</li>
      <li>Sezonowe porządki ogrodowe</li>
      <li>Usuwanie suchych i chorych gałęzi</li>
    </ul>
  </section>
  <section id="o-nas">
    <h2>O nas</h2>
    <p>Jesteśmy zespołem doświadczonych ogrodników, którzy z pasją i szacunkiem dla natury dbają o każdy metr kwadratowy Twojego ogrodu. Tradycja i nowoczesne metody pielęgnacji łączą się u nas w harmonii, by Twój ogród zawsze prezentował się perfekcyjnie.</p>
  </section>
  <section id="kontakt">
    <h2>Kontakt</h2>
    <p>Masz pytania? Chcesz wycenę? Zadzwoń lub napisz:</p>
    <ul>
      <li>Telefon: <a href="tel:+491234567890">+49 123 456 7890</a></li>
      <li>Email: <a href="mailto:kontakt@gartenandbaumserwis.de">kontakt@gartenandbaumserwis.de</a></li>
    </ul>
  </section>
</main>
<footer>
  &copy; 2025 GartenAndBaumSerwis. Wszystkie prawa zastrzeżone.
</footer>
</body>
</html>
