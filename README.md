```html
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KURAIDJU</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Orbitron',sans-serif;
    background:#050505;
    color:white;
    overflow-x:hidden;
}

body::before{
    content:"";
    position:fixed;
    inset:0;
    background:
    radial-gradient(circle at 20% 20%, rgba(255,0,90,.18), transparent 35%),
    radial-gradient(circle at 80% 30%, rgba(255,0,150,.12), transparent 35%),
    radial-gradient(circle at 50% 80%, rgba(120,0,255,.12), transparent 40%);
    z-index:-1;
}

.container{
    max-width:1100px;
    margin:auto;
    padding:40px 20px;
}

.hero{
    text-align:center;
    padding:60px 0;
}

.hero h1{
    font-size:72px;
    color:#ff0055;
    text-shadow:
        0 0 10px #ff0055,
        0 0 30px #ff0055,
        0 0 60px #ff0055;
}

.hero p{
    margin-top:15px;
    color:#d0d0d0;
}

.buttons{
    margin-top:30px;
}

.btn{
    display:inline-block;
    margin:8px;
    padding:14px 28px;
    text-decoration:none;
    color:white;
    border-radius:12px;
    background:rgba(255,255,255,.05);
    border:1px solid rgba(255,255,255,.1);
    backdrop-filter:blur(10px);
    transition:.25s;
}

.btn:hover{
    transform:translateY(-3px);
}

.donate{
    background:linear-gradient(45deg,#ff003c,#ff5aa5);
    box-shadow:0 0 20px #ff0055;
    animation:pulse 1.6s infinite;
}

@keyframes pulse{
    0%{box-shadow:0 0 10px #ff0055;}
    50%{box-shadow:0 0 35px #ff3388;}
    100%{box-shadow:0 0 10px #ff0055;}
}

.card{
    margin-top:25px;
    padding:25px;
    border-radius:20px;
    background:rgba(255,255,255,.05);
    border:1px solid rgba(255,255,255,.08);
    backdrop-filter:blur(15px);
}

.card h2{
    color:#ff4d8d;
    margin-bottom:15px;
}

.track-table{
    width:100%;
    border-collapse:collapse;
    margin-top:15px;
}

.track-table th,
.track-table td{
    padding:12px;
    border-bottom:1px solid rgba(255,255,255,.1);
    text-align:left;
}

.track-table th{
    color:#ff4d8d;
}

.footer{
    text-align:center;
    padding:40px 0;
    opacity:.6;
}
</style>
</head>
<body>

<div class="container">

    <section class="hero">
        <h1>KURAIDJU</h1>
        <p>Реакции • Стримы • Общение</p>

        <div class="buttons">
            <a class="btn" href="https://www.youtube.com/@kuraidju" target="_blank">YouTube</a>
            <a class="btn" href="https://www.twitch.tv/kuraidju" target="_blank">Twitch</a>
            <a class="btn" href="https://t.me/kuraidju" target="_blank">Telegram</a>
            <a class="btn donate" href="https://www.donationalerts.com/r/kuraidju" target="_blank">💸 Donate</a>
        </div>
    </section>

    <div class="card">
        <h2>О проекте</h2>
        <p>
            Контент про реакции, стримы, игры и живое общение.
            Здесь собираются лучшие моменты эфиров, оценки треков
            и мнение зрителей.
        </p>
    </div>

    <div class="card">
        <h2>🎧 Оценка треков</h2>

        <table class="track-table">
            <thead>
                <tr>
                    <th>Исполнитель</th>
                    <th>Трек</th>
                    <th>KURAIDJU</th>
                    <th>Зрители</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>WarVoid</td>
                    <td>—</td>
                    <td>—</td>
                    <td>—</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div class="footer">
        © KURAIDJU
    </div>

</div>

</body>
</html>
```
# kuraidju.github.io
