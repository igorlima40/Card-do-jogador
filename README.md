<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card de Jogador</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 300px;
            position: relative;
        }
        .player-image {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            position: absolute;
            top: -40px;
            left: 50%;
            transform: translateX(-50%);
            background: white;
            padding: 5px;
        }
        .player-name {
            font-size: 20px;
            font-weight: bold;
            margin-top: 50px;
        }
        .position {
            color: gray;
            margin-bottom: 10px;
        }
        .info {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
        }
        .info img {
            width: 40px;
            height: 40px;
        }
        .stats {
            display: flex;
            justify-content: space-around;
            font-size: 14px;
        }
        .transfer-history {
            text-align: left;
            font-size: 14px;
            margin-top: 10px;
        }
        .transfer-history h3 {
            font-size: 14px;
            margin-bottom: 5px;
        }
    </style>
</head>
<body>
    <div class="card">
        <img src="AddText_04-06-08.49.50.png" alt="Foto do Jogador" class="player-image">
        <div class="player-name">Igor Lima</div>
        <div class="position">Goleiro</div>
        <div class="info">
            <div>
                <img src="bandeira-brasil.png" alt="Brasil">
                <div>Brasil</div>
            </div>
            <div>
                <img src="team_logo.png" alt="Real Concordiense">
                <div>Real Concordiense</div>
            </div>
        </div>
        <div class="stats">
            <div><strong>15 anos</strong><br>24/12/2009</div>
            <div><strong>1,75m</strong><br>Altura</div>
            <div><strong>2</strong><br>N° Camisa</div>
        </div>
        <div class="transfer-history">
            <h3>Histórico de Transferências</h3>
            <ul>
                <li>2025 - Real Concordiense</li>
                <li>2024/2025 - Los Santos</li>
                <li>2024 - Sporting Sintrial</li>
            </ul>
        </div>
    </div>
</body>
</html>

