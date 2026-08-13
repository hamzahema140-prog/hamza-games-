<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Hamza Games</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #080d1c;
            color: white;
            text-align: center;
            overflow-x: auto;
        }

        header {
            min-height: 70vh;
            padding: 100px 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #111a3a, #25104d);
        }

        header h1 {
            font-size: clamp(42px, 8vw, 75px);
            margin-bottom: 20px;
        }

        header p {
            font-size: clamp(18px, 4vw, 25px);
            color: #c8ceff;
        }

        .container {
            width: 100%;
            max-width: 1100px;
            margin: auto;
            padding: 60px 20px;
        }

        .section-title {
            font-size: clamp(32px, 6vw, 45px);
            margin-bottom: 40px;
        }

        .games {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 25px;
        }

        .game-card {
            width: 350px;
            max-width: 100%;
            padding: 35px 25px;
            background: #151d38;
            border-radius: 25px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.4);
        }

        .game-icon {
            font-size: 65px;
            margin-bottom: 15px;
        }

        .game-card h3 {
            font-size: 28px;
            margin-bottom: 15px;
        }

        .game-card p {
            color: #c8c8c8;
            line-height: 1.6;
            margin-bottom: 25px;
        }

        .play-button {
            display: inline-block;
            padding: 15px 32px;
            background: #6c5ce7;
            color: white;
            border-radius: 30px;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            transition: 0.2s;
            cursor: pointer;
        }

        .play-button:hover {
            background: #8c7cff;
            transform: scale(1.05);
        }

        .about {
            background: #10162b;
            padding: 60px 20px;
        }

        .about p {
            max-width: 700px;
            margin: auto;
            color: #c8c8c8;
            font-size: 18px;
            line-height: 1.8;
        }

        footer {
            padding: 30px 20px;
            background: #050812;
            color: #888;
        }

        @media (max-width: 600px) {
            header {
                min-height: 60vh;
                padding: 70px 15px;
            }

            .container {
                padding: 45px 15px;
            }

            .game-card {
                width: 100%;
            }

            .play-button {
                padding: 16px 30px;
                font-size: 18px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>🎮 Hamza Games</h1>
        <p>Welcome to my gaming world!</p>
    </header>

    <section class="container">

        <h2 class="section-title">🎮 My Games</h2>

        <div class="games">

            <div class="game-card">

                <div class="game-icon">🎯</div>

                <h3>Hamza Ibrahim Game</h3>

                <p>
                    A fun game created by Hamza.
                    Try it and have fun!
                </p>

                <a
                    href="https://planet.mblock.cc/project/8267714"
                    class="play-button"
                    target="_blank"
                    rel="noopener">
                    ▶ Play Game
                </a>

            </div>

        </div>

    </section>

    <section class="about">

        <h2 class="section-title">👤 About Hamza</h2>

        <p>
            Welcome to Hamza Games!
            This website is created by Hamza to share
            his games and projects with everyone.
            More games are coming soon! 🚀
        </p>

    </section>

    <footer>
        © 2026 Hamza Games 🎮
    </footer>

</body>
</html>
