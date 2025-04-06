<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Card do Jogador</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      display: flex;
      justify-content: center;
      padding: 20px;
    }

    .card {
      background-color: white;
      width: 350px;
      border-radius: 15px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
      text-align: center;
    }

    .profile-img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
    }

    .player-name {
      font-size: 22px;
      font-weight: bold;
    }

    .position {
      font-size: 16px;
      margin-bottom: 15px;
      color: #555;
    }

    .divider {
      height: 1px;
      background-color: #ddd;
      margin: 15px 0;
    }

    .info-row {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin: 10px 0;
    }

    .info-col {
      text-align: center;
    }

    .flag,
    .club-logo {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 5px;
    }

    .label {
      font-size: 14px;
      color: #777;
    }

    .value {
      font-weight: bold;
      font-size: 16px;
    }

    .history-title {
      font-weight: bold;
      margin-top: 15px;
      font-size: 16px;
    }

    .transfer-list {
      list-style: none;
      padding: 0;
      margin-top: 10px;
      font-size: 14px;
    }

    .transfer-list li {
      margin-bottom: 5px;
    }
  </style>
</head>
<body>
  <div class="card">
    <img class="profile-img" src="perfil.png" alt="Foto do jogador">
    <div class="player-name">Igor Lima</div>
    <div class="position">Goleiro</div>

    <div class="info-row">
      <div class="info-col">
        <img class="flag" src="bandeira-brasil.png" alt="Brasil">
        <div class="label">Brasil</div>
      </div>
      <div class="divider" style="width: 1px; height: 50px;"></div>
      <div class="info-col">
        <img class="club-logo" src="logo-clube.png" alt="Clube">
        <div class="label">Real Concordiense</div>
      </div>
    </div>

    <div class="divider"></div>

    <div class="info-row">
      <div class="info-col">
        <div class="value">15 anos</div>
        <div class="label">24/12/2009</div>
      </div>
      <div class="info-col">
        <div class="value">1,75m</div>
        <div class="label">Altura</div>
      </div>
      <div class="info-col">
        <div class="value">2</div>
        <div class="label">N° Camisa</div>
      </div>
    </div>

    <div class="history-title">Histórico de Transferências</div>
    <ul class="transfer-list">
      <li>2025 - Real Concordiense</li>
      <li>2024/2025 - Los Santos</li>
      <li>2024 - Sporting Sintrial</li>
    </ul>
  </div>
</body>
</html>
