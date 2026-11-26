# Mon-premier-site-
Mon premier projet de création de site internet 

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Boutique Élégance</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #222;
      background: #f8f6f2;
    }
    header {
      background: #183b32;
      color: white;
      text-align: center;
      padding: 45px 20px;
    }
    header h1 { font-size: 32px; }
    section {
      max-width: 750px;
      margin: 30px auto;
      padding: 25px;
      background: white;
      border-radius: 12px;
    }
    h2 { color: #183b32; }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 15px;
    }
    .service {
      background: #edf2ed;
      padding: 18px;
      border-radius: 10px;
    }
    .contact {
      display: inline-block;
      background: #16864a;
      color: white;
      padding: 14px 22px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #666;
    }
  </style>
</head>
<body>

<header>
  <h1>Boutique Élégance</h1>
  <p>La qualité et le style à votre portée</p>
</header>

<section>
  <h2>Bienvenue chez nous</h2>
  <p>
    Découvrez notre boutique et nos produits.
    Nous vous proposons des articles de qualité
    à des prix accessibles.
  </p>
</section>

<section>
  <h2>Nos services</h2>
  <div class="services">
    <div class="service">
      <h3>Vêtements</h3>
      <p>Des vêtements pour tous les styles.</p>
    </div>
    <div class="service">
      <h3>Accessoires</h3>
      <p>Des accessoires pour compléter votre look.</p>
    </div>
    <div class="service">
      <h3>Commandes</h3>
      <p>Contactez-nous pour vos commandes.</p>
    </div>
  </div>
</section>

<section>
  <h2>Contactez-nous</h2>
  <p>Nous sommes disponibles pour répondre à vos questions.</p>
  <a class="contact"
     href="https://wa.me/228XXXXXXXXX">
     Nous contacter sur WhatsApp
  </a>
</section>

<footer>
  © 2026 Boutique Élégance - Tous droits réservés
</footer>

</body>
</html>
