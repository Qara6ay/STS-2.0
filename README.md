<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>МОШЕННИКИ КРАДУТ ТЕНГЕ: ШОКИРУЮЩИЕ ФАКТЫ 2025</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700;600&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #fff;
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        h1 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            font-size: 2.2rem;
            text-align: center;
            margin-bottom: 10px;
            text-shadow: 0 2px 4px rgba(0,0,0,0.5);
        }
        .subtitle {
            font-size: 1.1rem;
            margin-bottom: 30px;
            text-align: center;
            opacity: 0.9;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
            max-width: 1400px;
        }
        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 16px;
            padding: 20px;
            width: 420px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.18);
        }
        .card h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.4rem;
            margin: 0 0 15px 0;
            text-align: center;
            color: #00d4ff;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 15px;
            font-size: 0.95rem;
        }
        th, td {
            padding: 12px 10px;
            text-align: left;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
            color: #fff;
        }
        th {
            background: rgba(0, 212, 255, 0.2);
            font-weight: 600;
            font-family: 'Montserrat', sans-serif;
            text-transform: uppercase;
            font-size: 0.8rem;
            letter-spacing: 0.5px;
        }
        tr:hover {
            background: rgba(0, 212, 255, 0.1);
        }
        .highlight {
            font-weight: 600;
            color: #ff6b6b;
        }
        .chart-container {
            position: relative;
            height: 220px;
            margin: 15px 0;
        }
        .icons {
            text-align: center;
            font-size: 2rem;
            margin: 15px 0;
        }
        .growth {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 8px;
            font-size: 1.3rem;
            font-weight: 600;
            color: #ff4757;
        }
        .growth-arrow {
            font-size: 1.8rem;
        }
        .sts {
            margin-top: 30px;
            font-family: 'Montserrat', sans-serif;
            font-size: 1.5rem;
            font-weight: 700;
            text-align: center;
            background: linear-gradient(90deg, #ff6b6b, #ffa502);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: none;
        }
        @media (max-width: 900px) {
            .card { width: 100%; max-width: 500px; }
            h1 { font-size: 1.8rem; }
        }
    </style>
</head>
<body>
    <h1>МОШЕННИКИ КРАДУТ ТЕНГЕ: ШОКИРУЮЩИЕ ФАКТЫ 2025</h1>
    <p class="subtitle">Данные МВД и Нацбанка РК</p>

    <div class="container">

        <!-- Карточка 1: Основные показатели -->
        <div class="card">
            <h2>📊 Ключевые показатели</h2>
            <table>
                <tr><th>Период</th><th>Значение</th></tr>
                <tr><td>Случаи кибермошенничества (5 мес. 2025)</td><td class="highlight">10 145</td></tr>
                <tr><td>Рост к 2024 году</td><td class="highlight">+22–23%</td></tr>
                <tr><td>Доля интернет-афер</td><td class="highlight">54%</td></tr>
                <tr><td>Ущерб за год (оценка)</td><td class="highlight">15–20 млрд ₸</td></tr>
                <tr><td>Возвращено жертвам</td><td class="highlight">~1 млрд ₸</td></tr>
            </table>
            <div class="icons">📱💸🚫</div>
            <div class="growth">+23% <span class="growth-arrow">⬆</span></div>
        </div>

        <!-- Карточка 2: Жертвы -->
        <div class="card">
            <h2>🎯 Кто пострадал</h2>
            <table>
                <tr><th>Группа</th><th>Доля</th></tr>
                <tr><td>Пенсионеры</td><td class="highlight">35%</td></tr>
                <tr><td>Студенты</td><td class="highlight">25%</td></tr>
                <tr><td>Женщины / домохозяйки</td><td class="highlight">40%</td></tr>
            </table>
            <div class="chart-container">
                <canvas id="victimsChart"></canvas>
            </div>
        </div>

        <!-- Карточка 3: Регионы -->
        <div class="card">
            <h2>📍 Лидеры по случаям</h2>
            <table>
                <tr><th>Регион</th><th>Случаи</th></tr>
                <tr><td>Астана</td><td class="highlight">1 548</td></tr>
                <tr><td>Алматы</td><td class="highlight">1 114</td></tr>
                <tr><td>Карагандинская обл.</td><td class="highlight">868</td></tr>
            </table>
            <div class="chart-container">
                <canvas id="regionsChart"></canvas>
            </div>
        </div>

        <!-- Карточка 4: Схемы -->
        <div class="card">
            <h2>🎭 Популярные схемы</h2>
            <table>
                <tr><th>Схема</th><th>Доля</th></tr>
                <tr><td>Фишинг-ссылки</td><td class="highlight">45%</td></tr>
                <tr><td>Звонки "от банка"</td><td class="highlight">30%</td></tr>
                <tr><td>SMS "выигрыш/блокировка"</td><td class="highlight">25%</td></tr>
            </table>
            <div style="font-size:0.85rem; margin-top:10px; opacity:0.9;">
                Заблокировано звонков: <b>67 млн</b>
            </div>
            <div class="chart-container">
                <canvas id="schemesChart"></canvas>
            </div>
        </div>

    </div>

    <div class="sts">STS: Остановим воровство тенге вместе!</div>

    <script>
        // График жертв
        new Chart(document.getElementById('victimsChart'), {
            type: 'doughnut',
            data: {
                labels: ['Пенсионеры', 'Студенты', 'Женщины/домохозяйки'],
                datasets: [{
                    data: [35, 25, 40],
                    backgroundColor: ['#ff6b6b', '#4ecdc4', '#45b7d1'],
                    borderColor: '#fff',
                    borderWidth: 2
                }]
            },
            options: {
                responsive: true,
                plugins: {
                    legend: { position: 'bottom', labels: { color: '#fff', font: { size: 12 } } },
                    tooltip: { callbacks: { label: ctx => ctx.label + ': ' + ctx.parsed + '%' } }
                }
            }
        });

        // График регионов
        new Chart(document.getElementById('regionsChart'), {
            type: 'bar',
            data: {
                labels: ['Астана', 'Алматы', 'Караганда'],
                datasets: [{
                    label: 'Случаи',
                    data: [1548, 1114, 868],
                    backgroundColor: '#00d4ff',
                    borderColor: '#fff',
                    borderWidth: 1
                }]
            },
            options: {
                responsive: true,
                plugins: {
                    legend: { display: false },
                    tooltip: { callbacks: { label: ctx => ctx.parsed.y + ' случаев' } }
                },
                scales: {
                    y: { ticks: { color: '#fff' }, grid: { color: 'rgba(255,255,255,0.1)' } },
                    x: { ticks: { color: '#fff' } }
                }
            }
        });

        // График схем
        new Chart(document.getElementById('schemesChart'), {
            type: 'pie',
            data: {
                labels: ['Фишинг', 'Звонки', 'SMS'],
                datasets: [{
                    data: [45, 30, 25],
                    backgroundColor: ['#ffa502', '#ff4757', '#2ed573'],
                    borderColor: '#fff',
                    borderWidth: 2
                }]
            },
            options: {
                responsive: true,
                plugins: {
                    legend: { position: 'bottom', labels: { color: '#fff', font: { size: 12 } } },
                    tooltip: { callbacks: { label: ctx => ctx.label + ': ' + ctx.parsed + '%' } }
                }
            }
        });
    </script>
</body>
</html>
