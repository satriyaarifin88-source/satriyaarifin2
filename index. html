<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Satria Arifin</title>
    <!-- Google Fonts & Font Awesome Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg-dark: #07150c;
            --bg-card: rgba(18, 43, 26, 0.65);
            --border-card: rgba(74, 222, 128, 0.2);
            --primary-green: #4ade80;
            --secondary-green: #22c55e;
            --text-main: #f0fdf4;
            --text-muted: #a7f3d0;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #051009 0%, #0d2816 50%, #174223 100%);
            color: var(--text-main);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 2rem 1rem;
            position: relative;
            overflow-x: hidden;
        }

        /* Background glow effect */
        body::before {
            content: '';
            position: absolute;
            top: 10%;
            left: 50%;
            transform: translateX(-50%);
            width: 300px;
            height: 300px;
            background: rgba(34, 197, 94, 0.25);
            filter: blur(120px);
            border-radius: 50%;
            z-index: 0;
        }

        .container {
            width: 100%;
            max-width: 850px;
            background: var(--bg-card);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid var(--border-card);
            border-radius: 24px;
            padding: 2.5rem;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.5);
            z-index: 1;
        }

        .header {
            text-align: center;
            padding-bottom: 2rem;
            border-bottom: 1px solid rgba(74, 222, 128, 0.15);
        }

        .avatar {
            width: 110px;
            height: 110px;
            background: linear-gradient(135deg, var(--primary-green), var(--secondary-green));
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1.2rem;
            font-size: 2.8rem;
            color: #051009;
            box-shadow: 0 0 25px rgba(74, 222, 128, 0.4);
        }

        .header h1 {
            font-size: 2.2rem;
            font-weight: 700;
            background: linear-gradient(to right, #ffffff, var(--primary-green));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 0.3rem;
        }

        .header p {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        .grid-layout {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(74, 222, 128, 0.1);
            border-radius: 16px;
            padding: 1.5rem;
            transition: all 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: rgba(74, 222, 128, 0.4);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .card-title {
            font-size: 1.1rem;
            font-weight: 600;
            color: var(--primary-green);
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.6rem;
        }

        .info-list {
            list-style: none;
        }

        .info-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 0.8rem;
            font-size: 0.9rem;
        }

        .info-item:last-child {
            margin-bottom: 0;
        }

        .label {
            color: var(--text-muted);
        }

        .value {
            font-weight: 500;
            word-break: break-all;
            text-align: right;
        }

        .tag-container {
            display: flex;
            flex-wrap: wrap;
            gap: 0.6rem;
        }

        .tag {
            background: rgba(74, 222, 128, 0.12);
            color: var(--primary-green);
            border: 1px solid rgba(74, 222, 128, 0.25);
            padding: 0.4rem 0.9rem;
            border-radius: 50px;
            font-size: 0.85rem;
            font-weight: 500;
            display: flex;
            align-items: center;
            gap: 0.4rem;
        }

        .btn-copy {
            background: transparent;
            border: none;
            color: var(--primary-green);
            cursor: pointer;
            margin-left: 0.5rem;
            font-size: 0.85rem;
            transition: color 0.2s;
        }

        .btn-copy:hover {
            color: #ffffff;
        }

        .footer {
            text-align: center;
            margin-top: 2rem;
            font-size: 0.8rem;
            color: var(--text-muted);
            opacity: 0.7;
        }

        @media (max-width: 600px) {
            .container {
                padding: 1.5rem;
            }
            .header h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header / Profile -->
        <div class="header">
            <div class="avatar">
                <i class="fa-solid fa-user"></i>
            </div>
            <h1>Satria Arifin</h1>
            <p><i class="fa-solid fa-location-dot"></i> Jl. Kelud</p>
        </div>

        <!-- Content Grid -->
        <div class="grid-layout">
            <!-- Kontak Card -->
            <div class="card">
                <div class="card-title">
                    <i class="fa-solid fa-address-card"></i> Informasi Kontak
                </div>
                <ul class="info-list">
                    <li class="info-item">
                        <span class="label">Email</span>
                        <span class="value">
                            satriyaarifin88@gmail.com
                            <button class="btn-copy" onclick="copyText('satriyaarifin88@gmail.com')" title="Salin Email"><i class="fa-regular fa-copy"></i></button>
                        </span>
                    </li>
                    <li class="info-item">
                        <span class="label">No. HP</span>
                        <span class="value">
                            082233144219
                            <button class="btn-copy" onclick="copyText('082233144219')" title="Salin No HP"><i class="fa-regular fa-copy"></i></button>
                        </span>
                    </li>
                    <li class="info-item">
                        <span class="label">Alamat</span>
                        <span class="value">Jl. Kelud</span>
                    </li>
                </ul>
            </div>

            <!-- Skill Card -->
            <div class="card">
                <div class="card-title">
                    <i class="fa-solid fa-bolt"></i> Keahlian (Skill)
                </div>
                <div class="tag-container">
                    <span class="tag"><i class="fa-solid fa-mitten"></i> Kick Boxing</span>
                </div>
            </div>

            <!-- Hobi Card -->
            <div class="card" style="grid-column: 1 / -1;">
                <div class="card-title">
                    <i class="fa-solid fa-heart"></i> Hobi & Minat
                </div>
                <div class="tag-container">
                    <span class="tag"><i class="fa-solid fa-person-running"></i> Jogging</span>
                    <span class="tag"><i class="fa-solid fa-shuttlecock"></i> Badminton</span>
                </div>
            </div>
        </div>

        <div class="footer">
            &copy; 2026 Satria Arifin. Built with GitHub Pages.
        </div>
    </div>

    <script>
        function copyText(text) {
            navigator.clipboard.writeText(text).then(() => {
                alert('Berhasil disalin: ' + text);
            }).catch(err => {
                console.error('Gagal menyalin text: ', err);
            });
        }
    </script>
</body>
</html>
