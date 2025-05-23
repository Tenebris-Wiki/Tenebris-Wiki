<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wiki de Quinques - Tenebris</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #0f0f0f;
      color: #e0e0e0;
      padding: 40px;
      margin: 0;
    }

    h1 {
      text-align: center;
      color: #ffffff;
      margin-bottom: 40px;
    }

    .quinque-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 24px;
    }

    .card {
      background: #1a1a1a;
      border: 1px solid #333;
      border-radius: 12px;
      padding: 20px;
      text-align: center;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.03);
      background: #222;
    }

    .card img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 12px;
    }

    .rank {
      font-weight: bold;
      color: #ffa500;
    }

    .type {
      font-size: 0.9em;
      opacity: 0.8;
    }

    .desc {
      font-size: 0.95em;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h1>Wiki de Quinques - Tenebris</h1>

  <div class="quinque-grid">
    <div class="card">
      <img src="https://i.imgur.com/J7R7wvI.png" alt="Narukami">
      <h2>Narukami ⚡</h2>
      <div class="rank">Rank: SS</div>
      <div class="type">Tipo: Ukaku</div>
      <p class="desc">Quinque elétrica de longo alcance. Ideal para combates táticos. Dispara relâmpagos teleguiados.</p>
    </div>

    <div class="card">
      <img src="https://i.imgur.com/dD2mRxr.png" alt="13's Jason">
      <h2>13's Jason 🪓</h2>
      <div class="rank">Rank: SS</div>
      <div class="type">Tipo: Rinkaku</div>
      <p class="desc">Brutal e poderosa. Baseada em Yamori. Especializada em dano pesado corpo-a-corpo.</p>
    </div>

    <div class="card">
      <img src="https://i.imgur.com/93pyC6O.png" alt="Arata">
      <h2>Arata ⚙️</h2>
      <div class="rank">Rank: S</div>
      <div class="type">Tipo: Koukaku</div>
      <p class="desc">Armadura de combate. Aumenta resistência e força física. Ideal para tanques.</p>
    </div>

    <div class="card">
      <img src="https://i.imgur.com/ClIQnTr.png" alt="Yamato">
      <h2>Yamato ⚔️</h2>
      <div class="rank">Rank: S</div>
      <div class="type">Tipo: Bikaku</div>
      <p class="desc">Espada equilibrada para PvE. Boa combinação de alcance, agilidade e poder.</p>
    </div>

    <div class="card">
      <img src="https://i.imgur.com/lpXpbcg.png" alt="Kuzen">
      <h2>Kuzen ☁️</h2>
      <div class="rank">Rank: SSS</div>
      <div class="type">Tipo: Ukaku</div>
      <p class="desc">Quinque lendária baseada em Yoshimura. Altíssimo dano, ideal para PvP avançado.</p>
    </div>
  </div>
</body>
</html>
