# Divine-Hustle123<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Divine Hustle</title>
  <style>
    :root {
      --primary: #0d47a1;
      --dark: #000;
      --light: #f8f8f8;
      --text: #222;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Helvetica Neue', sans-serif;
      background-color: var(--light);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background-color: var(--dark);
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 1.5rem;
      letter-spacing: 1px;
      color: var(--primary);
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 1.5rem;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--primary);
    }

    .hero {
      background: url('https://via.placeholder.com/1600x600/0d47a1/ffffff?text=Divine+Hustle+Collection') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .hero button {
      background: var(--primary);
      color: white;
      padding: 0.8rem 2rem;
      border: none;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 5px;
      font-weight: bold;
    }

    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      color: var(--primary);
      margin-bottom: 1rem;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 2rem;
      margin-top: 1rem;
    }

    .product-card {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .product-card img {
      max-width: 100%;
      border-radius: 5px;
    }

    form {
      display: flex;
      flex-direction: column;
      margin-top: 1rem;
    }

    input, textarea {
      width: 100%;
      padding: 0.8rem;
      margin-bottom: 1rem;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    button {
      padding: 0.8rem 1.5rem;
      background: var(--primary);
      color: #fff;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    .contact-info a {
      color: var(--primary);
      text-decoration: underline;
    }

    footer {
      background: var(--dark);
      color: #fff;
      text-align: center;
      padding: 1rem 0;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Divine Hustle</h1>
    <nav>
      <a href="#shop">Shop</a>
      <a href="#about">Über uns</a>
      <a href="#order">Bestellen</a>
      <a href="#contact">Kontakt</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Bold Looks. Divine Vision.</h2>
    <button onclick="alert('Shop-Feature folgt bald!')">Jetzt shoppen</button>
  </section>

  <section id="shop" class="products">
    <h2>Unsere Produkte</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://via.placeholder.com/300x400?text=T-Shirt" alt="T-Shirt">
        <h3>Classic Hustle Tee</h3>
        <p>29,99 €</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/300x400?text=Hoodie" alt="Hoodie">
        <h3>Signature Hoodie</h3>
        <p>59,99 €</p>
      </div>
    </div>
  </section>

  <section id="about" class="about">
    <h2>Über Divine Hustle</h2>
    <p>Divine Hustle ist mehr als nur Mode – es ist eine Haltung. Für alle, die mit Stil, Mut und Vision ihren Weg gehen. Unsere Kollektionen kombinieren Streetwear mit spirituellem Antrieb und einem Hauch Luxus.</p>
  </section>

  <section id="order" class="order">
    <h2>Bestellung aufgeben</h2>
    <p>Fülle das Formular aus, um eine Produktanfrage zu senden. Wir melden uns schnellstmöglich per E-Mail bei dir.</p>
    <form>
      <input type="text" placeholder="Vollständiger Name" required />
      <input type="email" placeholder="E-Mail-Adresse" required />
      <input type="text" placeholder="Produktname (z. B. Classic Hustle Tee)" required />
      <input type="number" placeholder="Menge" min="1" required />
      <textarea rows="4" placeholder="Lieferadresse oder Wünsche"></textarea>
      <button type="submit">Bestellung senden</button>
    </form>
  </section>

  <section id="contact" class="contact-info">
    <h2>Kontakt</h2>
    <p><strong>E-Mail:</strong> kontakt@divinehustle.de</p>
    <p><strong>Instagram:</strong> <a href="https://instagram.com/divinehustle" target="_blank">@divinehustle</a></p>
    <p><strong>Telefon:</strong> +49 123 456 7890</p>
  </section>

  <footer>
    <p>&copy; 2025 Divine Hustle. Alle Rechte vorbehalten.</p>
  </footer>

</body>
</html>
