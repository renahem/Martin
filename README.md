<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Rena Hem – Städhjälp i Torrevieja</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f3fa;
      color: #1a1a1a;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #0d1b2a;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
      position: relative;
    }
    header img {
      max-width: 120px;
      margin-bottom: 20px;
      opacity: 0.2;
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -50%);
      z-index: 0;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      position: relative;
      z-index: 1;
    }
    header p {
      color: #d4af37;
      font-size: 1.2rem;
      margin-top: 10px;
      position: relative;
      z-index: 1;
    }
    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }
    h2 {
      color: #0d1b2a;
      margin-top: 0;
    }
    .services,
    .contact,
    .about,
    .form,
    .testimonials {
      background-color: #ffffff;
      padding: 20px;
      margin-top: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
    }
    footer {
      background-color: #0d1b2a;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
    input,
    textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      margin-bottom: 16px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }
    button {
      background-color: #0d1b2a;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1rem;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #162d50;
    }
    ul {
      padding-left: 20px;
    }
    a {
      color: #0d1b2a;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <img src="A_logo_design_for_a_cleaning_service_named_Rena_H.png" alt="Rena Hem logotyp" />
    <h1>Rena Hem</h1>
    <p>Din pålitliga städhjälp i Torrevieja</p>
  </header>

  <section>
    <div class="about">
      <h2>Om oss</h2>
      <p>Rena Hem är en svenskägd städfirma i Torrevieja som specialiserar sig på korttidsuthyrning och Airbnb-boenden. Vi levererar kvalitet, punktlighet och diskret service med skandinavisk standard.</p>
    </div>

    <div class="services">
      <h2>Våra tjänster</h2>
      <ul>
        <li>Airbnb-städning (inkl. bäddning och förbrukningspåfyllning) – 25€ / gång</li>
        <li>Veckostädning – 40€ / gång</li>
        <li>Inför- och efterbesiktning för uthyrning – 30€ / gång</li>
        <li>Fönsterputs och extra storstädning – 50€ och uppåt</li>
      </ul>
    </div>

    <div class="testimonials">
      <h2>Vad våra kunder säger</h2>
      <p><em>“Fantastisk service och alltid skinande rent. Våra gäster har aldrig varit nöjdare!”</em> – Anna L., fastighetsägare</p>
      <p><em>“Snabba, flexibla och mycket proffsiga. Rekommenderas varmt.”</em> – Erik M., Airbnb-värd</p>
    </div>

    <div class="form">
      <h2>Boka städning / Be om offert</h2>
      <form action="#" method="post">
        <label for="name">Namn</label>
        <input type="text" id="name" name="name" required />

        <label for="email">E-post</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Meddelande</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Skicka</button>
      </form>
    </div>

    <div class="contact">
      <h2>Kontakt</h2>
      <p>Kontakta oss via e-post: <a href="mailto:info@renahem.es">info@renahem.es</a></p>
      <p>Vi svarar alltid inom 24 timmar.</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Rena Hem – Städfirma i Torrevieja
  </footer>
</body>
</html>
