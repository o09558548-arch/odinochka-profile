<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>odinochka ☁ - Player Profile</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #0f1720;
        color: #e6edf3;
    }

    .container {
        width: 1100px;
        margin: 40px auto;
    }

    .header {
        display: flex;
        align-items: center;
        background: #161f2b;
        padding: 20px;
        border-radius: 10px;
    }

    .avatar {
        width: 120px;
        height: 120px;
        background: #2b3647;
        border-radius: 10px;
        margin-right: 20px;
    }

    .player-info h1 {
        margin: 0;
        font-size: 28px;
    }

    .player-info p {
        margin: 5px 0;
        color: #9fb3c8;
    }

    .stats-grid {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 15px;
        margin-top: 20px;
    }

    .card {
        background: #161f2b;
        padding: 15px;
        border-radius: 10px;
        text-align: center;
    }

    .card h2 {
        margin: 0;
        font-size: 20px;
        color: #4da3ff;
    }

    .card p {
        margin: 5px 0 0;
        font-size: 13px;
        color: #9fb3c8;
    }

    .section {
        margin-top: 25px;
        background: #161f2b;
        padding: 20px;
        border-radius: 10px;
    }

    table {
        width: 100%;
        border-collapse: collapse;
    }

    th, td {
        padding: 10px;
        text-align: left;
        border-bottom: 1px solid #222c3a;
    }

    th {
        color: #9fb3c8;
        font-weight: normal;
    }

    .win {
        color: #4caf50;
    }

    .lose {
        color: #ff5c5c;
    }
</style>
</head>
<body>

<div class="container">

    <div class="header">
        <div class="avatar"></div>
        <div class="player-info">
            <h1>odinochka ☁</h1>
            <p>Role: Support / Rifler</p>
            <p>Country: UA</p>
            <p>Team: Free Agent</p>
        </div>
    </div>

    <div class="stats-grid">
        <div class="card">
            <h2>1.05</h2>
            <p>Rating 2.0</p>
        </div>
        <div class="card">
            <h2>0.67</h2>
            <p>Kills / Round</p>
        </div>
        <div class="card">
            <h2>74.8%</h2>
            <p>KAST</p>
        </div>
        <div class="card">
            <h2>68.5</h2>
            <p>ADR</p>
        </div>
    </div>

    <div class="section">
        <h3>Recent Matches</h3>
        <table>
            <tr>
                <th>Score</th>
                <th>Opponent</th>
                <th>Rating</th>
            </tr>
            <tr>
                <td class="win">16 - 10</td>
                <td>Team Alpha</td>
                <td>1.21</td>
            </tr>
            <tr>
                <td class="lose">12 - 16</td>
                <td>Team Beta</td>
                <td>0.98</td>
            </tr>
            <tr>
                <td class="win">16 - 8</td>
                <td>Team Gamma</td>
                <td>1.15</td>
            </tr>
        </table>
    </div>

    <div class="section">
        <h3>Best Maps</h3>
        <table>
            <tr>
                <th>Map</th>
                <th>Rating</th>
                <th>Winrate</th>
            </tr>
            <tr>
                <td>Mirage</td>
                <td>1.12</td>
                <td>61%</td>
            </tr>
            <tr>
                <td>Inferno</td>
                <td>1.08</td>
                <td>59%</td>
            </tr>
            <tr>
                <td>Nuke</td>
                <td>1.05</td>
                <td>57%</td>
            </tr>
        </table>
    </div>

</div>

</body>
</html>
