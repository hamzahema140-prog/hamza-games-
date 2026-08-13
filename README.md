<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Hamza Games</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #0b1020;
            color: white;
            text-align: center;
        }

        header {
            padding: 60px 20px;
            background: linear-gradient(135deg, #111a3a, #25104d);
        }

        h1 {
            font-size: 50px;
        }

        .games {
            padding: 50px 20px;
        }

        .game-card {
            max-width: 400px;
            margin: auto;
            padding: 30px;
            background: #151d38;
            border-radius: 20px;
        }

        .play-button {
            display: inline-block;
            padding: 15px 35px;
            background: #6c5ce7;
            color: white;
            border-radius: 30px;
            text-decoration: none;
            font-size: 20px;
            font-weight: bold;
            cursor: pointer;
        }

        .play-button:hover {
            background: #8c7cff;
        }

        footer {
            margin-top: 50px;
            padding: 25px;
            background: #070b16;
        }
    </style>
</head>

<body>

    <header>
        <h1>🎮 Hamza Games</h1>
        <p>Welcome to my gaming world!</p>
    </header>

    <section class="games">

        <h2>My Games</h2>

        <div class="game-card">

            <h2>Hamza Ibrahim Game 🎯</h2>

            <p>A game created by Hamza.</p>

            <button
                class="play-button"
                onclick="window.open('https://planet.mblock.cc/project/8267714', '_blank')">
                ▶ Play Game
            </button>

        </div>

    </section>

    <footer>
        © 2026 Hamza Games
    </footer>

</body>
</html>
