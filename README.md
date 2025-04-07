<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cartão do Jogador</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #f3f3f3;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      max-width: 320px;
      width: 90%;
      text-align: center;
      position: relative;
    }

    .profile-img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
    }

    .position {
      color: #666;
      margin-top: -10px;
      margin-bottom: 20px;
    }

    .divider {
      display: flex;
      flex-direction: column;
      gap: 16px;
      margin-bottom: 20px;
    }

    .nationality-team {
      display: flex;
      justify-content: space-around;
    }

    .flag, .team-logo {
      display: flex;
      flex-direction: column;
      align-items: center;
      font-size: 14px;
    }

    .flag img,
    .team-logo img {
      width: 40px;
      height: 40px;
      margin-bottom: 4px;
    }

    .info {
      display: flex;
      justify-content: space-between;
      font-size: 14px;
      padding: 0 10px;
    }

    .history {
      text-align: left;
      font-size: 14px;
    }

    .history ul {
      list-style: none;
      padding: 0;
      margin-top: 8px;
    }

    .history li {
      display: flex;
      align-items: center;
      margin-bottom: 8px;
    }

    .history li img {
      width: 20px;
      height: 20px;
      margin-right: 8px;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="AddText_04-06-08.49.50.png" alt="Foto de Perfil" class="profile-img" />

    <h2>Igor Lima</h2>
    <p class="position">Goleiro</p>

    <div class="divider">
      <div class="nationality-team">
        <div class="flag">
          <img src="bandeira-brasil.png" alt="Brasil" />
          <span>Brasil</span>
        </div>
        <div class="team-logo">
          <img src="real-concordiense.png" alt="Real Concordiense" />
          <span>Real Concordiense</span>
        </div>
      </div>

      <div class="info">
        <div><strong>15 anos</strong><br><small>24/12/2009</small></div>
        <div><strong>1,75m</strong><br><small>Altura</small></div>
        <div><strong>2</strong><br><small>Nº Camisa</small></div>
      </div>
    </div>

    <hr>

    <div class="history">
      <p><strong>Histórico de Transferências</strong></p>
      <ul>
        <li>
          <img src="real-concordiense.png" alt="Real Concordiense" />
          2025 - Real Concordiense
        </li>
        <li>
          <img src="los-santos.png" alt="Los Santos" />
          2024/2025 - Los Santos
        </li>
        <li>
          <img src="sporting-sintrial.png" alt="Sporting Sintrial" />
          2024 - Sporting Sintrial
        </li>
      </ul>
    </div>
  </div>
</body>
</html>
