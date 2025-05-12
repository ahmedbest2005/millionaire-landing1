j<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Millionaire Table de Nuit</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background: #ffffff;
      color: #000000;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 2rem 1rem;
    }
    .container {
      max-width: 800px;
      width: 100%;
      text-align: center;
    }
    h1 {
      font-size: 2.2rem;
      margin-bottom: 1rem;
      color: #bfa135;
    }
    .price {
      font-size: 2rem;
      color: #bfa135;
      margin: 1rem 0;
      font-weight: bold;
    }
    .description {
      font-size: 1.1rem;
      margin-bottom: 2rem;
      line-height: 1.6;
      padding: 0 1rem;
    }
    .gallery {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      margin-bottom: 2rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 16px;
      box-shadow: 0 0 15px rgba(191, 161, 53, 0.3);
    }
    .cta {
      margin-top: 2rem;
    }
    .btn {
      background-color: #bfa135;
      color: #fff;
      padding: 1rem 2rem;
      border: none;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 10px;
      text-transform: uppercase;
      text-decoration: none;
      display: inline-block;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background-color: #a48828;
    }
    .arabic {
      margin-top: 2rem;
      font-size: 1.1rem;
      direction: rtl;
      text-align: right;
      color: #4a4a4a;
      padding: 0 1rem;
    }
    @media (min-width: 768px) {
      h1 { font-size: 3rem; }
      .price { font-size: 2.5rem; }
      .description, .arabic { font-size: 1.3rem; }
      .gallery {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
      }
      .gallery img {
        width: 48%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Millionaire - Table de Nuit de Luxe</h1>
    <div class="gallery">
      <img src="https://i.imgur.com/1.jpg" alt="Vue principale de la table de nuit">
      <img src="https://i.imgur.com/2.jpg" alt="Table de nuit vue de côté">
      <img src="https://i.imgur.com/3.jpg" alt="Table de nuit en situation dans une chambre">
    </div>
    <div class="price">999 MAD</div>
    <div class="description">
      Transformez votre chambre en sanctuaire de succès. Cette table de nuit n'est pas un simple meuble — c'est une déclaration. Un design en verre rempli de billets factices de 100$, parfait pour les ambitieux, les rêveurs et les leaders en devenir. Offrez-vous une touche de luxe qui inspire chaque matin.
    </div>
    <div class="cta">
      <a class="btn" href="https://wa.me/212612195740?text=Bonjour%2C+je+suis+int%C3%A9ress%C3%A9+par+la+table+de+nuit+Millionaire+%C3%A0+999+MAD.+Est-elle+disponible+%3F" target="_blank">
        Commander via WhatsApp
      </a>
    </div>
    <div class="arabic">
      <h2>طاولة نوم المليونير - فخامة تليق بطموحك</h2>
      <p>
        حوّل غرفة نومك إلى ملاذ مليء بالطموح. هذه الطاولة ليست مجرد قطعة أثاث — إنها رسالة نجاح. تصميم زجاجي يحتوي على أوراق نقدية مزيفة من فئة 100 دولار، مثالية لأصحاب الأحلام الكبيرة. السعر: 999 درهم فقط.
      </p>
    </div>
  </div>
</body>
</html>
