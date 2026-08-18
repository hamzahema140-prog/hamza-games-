<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

    <title>Hamza Games - Ball Game</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background: #080d1c;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            overflow: hidden;
            touch-action: none;
        }

        h1 {
            margin: 15px 0 5px;
            font-size: 32px;
        }

        #score {
            font-size: 20px;
            margin-bottom: 10px;
        }

        #game {
            position: relative;
            width: min(90vw, 700px);
            height: min(65vh, 600px);
            min-height: 400px;
            margin: auto;
            background: #111a3a;
            border: 3px solid #6c5ce7;
            border-radius: 15px;
            overflow: hidden;
        }

        #ball {
            position: absolute;
            width: 25px;
            height: 25px;
            background: white;
            border-radius: 50%;
            left: 50%;
            top: 80px;
            transform: translateX(-50%);
        }

        #bar {
            position: absolute;
            width: 130px;
            height: 20px;
            background: #6c5ce7;
            border-radius: 10px;
            bottom: 25px;
            left: 50%;
            transform: translateX(-50%);
        }

        #message {
            margin: 12px;
            font-size: 20px;
            font-weight: bold;
        }

        #controls {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 15px;
        }

        .control {
            width: 90px;
            height: 65px;
            border: none;
            border-radius: 20px;
            background: #6c5ce7;
            color: white;
            font-size: 35px;
            font-weight: bold;
            user-select: none;
            -webkit-user-select: none;
            touch-action: manipulation;
        }

        .control:active {
            transform: scale(0.92);
            background: #8c7cff;
        }

        #restart {
            display: none;
            margin-top: 10px;
            padding: 12px 25px;
            border: none;
            border-radius: 20px;
            background: #6c5ce7;
            color: white;
            font-size: 18px;
            font-weight: bold;
        }
    </style>
</head>

<body>

    <h1>🎮 Hamza Games</h1>

    <div id="score">Score: 0</div>

    <div id="game">

        <div id="ball"></div>

        <div id="bar"></div>

    </div>

    <div id="message">
        🎯 Catch the ball!
    </div>

    <div id="controls">

        <button class="control" id="left">⬅️</button>

        <button class="control" id="right">➡️</button>

    </div>

    <button id="restart">
        🔄 Play Again
    </button>

<script>

    const game = document.getElementById("game");
    const ball = document.getElementById("ball");
    const bar = document.getElementById("bar");

    const scoreText = document.getElementById("score");
    const message = document.getElementById("message");
    const restartButton = document.getElementById("restart");

    const leftButton = document.getElementById("left");
    const rightButton = document.getElementById("right");

    let ballX;
    let ballY;

    let ballSpeedX = 4;
    let ballSpeedY = 4;

    let barX;

    let score = 0;

    let gameRunning = true;

    let moveLeft = false;
    let moveRight = false;

    const barSpeed = 8;

    function resetGame() {

        ballX = game.clientWidth / 2 - 12.5;
        ballY = 80;

        barX = game.clientWidth / 2 - 65;

        ballSpeedX = 4;
        ballSpeedY = 4;

        score = 0;

        gameRunning = true;

        scoreText.textContent = "Score: 0";

        message.textContent = "🎯 Catch the ball!";

        restartButton.style.display = "none";

        updateObjects();
    }

    function updateObjects() {

        ball.style.left = ballX + "px";
        ball.style.top = ballY + "px";

        bar.style.left = (barX + 65) + "px";
    }

    function moveBar() {

        if (!gameRunning) {
            return;
        }

        if (moveLeft) {
            barX -= barSpeed;
        }

        if (moveRight) {
            barX += barSpeed;
        }

        const maxBarX = game.clientWidth - 130;

        if (barX < 0) {
            barX = 0;
        }

        if (barX > maxBarX) {
            barX = maxBarX;
        }
    }

    function moveBall() {

        if (!gameRunning) {
            return;
        }

        ballX += ballSpeedX;
        ballY += ballSpeedY;

        const ballSize = 25;

        const gameWidth = game.clientWidth;
        const gameHeight = game.clientHeight;

        if (ballX <= 0) {

            ballX = 0;

            ballSpeedX = Math.abs(ballSpeedX);
        }

        if (ballX + ballSize >= gameWidth) {

            ballX = gameWidth - ballSize;

            ballSpeedX = -Math.abs(ballSpeedX);
        }

        if (ballY <= 0) {

            ballY = 0;

            ballSpeedY = Math.abs(ballSpeedY);
        }

        const barY = gameHeight - 25 - 20;

        if (
            ballY + ballSize >= barY &&
            ballY + ballSize <= barY + 25 &&
            ballX + ballSize >= barX &&
            ballX <= barX + 130 &&
            ballSpeedY > 0
        ) {

            ballY = barY - ballSize;

            ballSpeedY = -Math.abs(ballSpeedY);

            score++;

            scoreText.textContent = "Score: " + score;

            if (score >= 20) {

                message.textContent = "🏆 ناجح! You Win!";

                gameRunning = false;

                restartButton.style.display = "inline-block";
            }
        }

        if (ballY > gameHeight) {

            message.textContent = "💥 Game Over!";

            gameRunning = false;

            restartButton.style.display = "inline-block";
        }
    }

    function gameLoop() {

        moveBar();

        moveBall();

        updateObjects();

        requestAnimationFrame(gameLoop);
    }

    document.addEventListener("keydown", function(event) {

        if (event.key === "ArrowLeft") {
            moveLeft = true;
        }

        if (event.key === "ArrowRight") {
            moveRight = true;
        }

    });

    document.addEventListener("keyup", function(event) {

        if (event.key === "ArrowLeft") {
            moveLeft = false;
        }

        if (event.key === "ArrowRight") {
            moveRight = false;
        }

    });

    function startLeft(event) {

        event.preventDefault();

        moveLeft = true;
    }

    function stopLeft(event) {

        event.preventDefault();

        moveLeft = false;
    }

    function startRight(event) {

        event.preventDefault();

        moveRight = true;
    }

    function stopRight(event) {

        event.preventDefault();

        moveRight = false;
    }

    leftButton.addEventListener("touchstart", startLeft);
    leftButton.addEventListener("touchend", stopLeft);
    leftButton.addEventListener("touchcancel", stopLeft);

    rightButton.addEventListener("touchstart", startRight);
    rightButton.addEventListener("touchend", stopRight);
    rightButton.addEventListener("touchcancel", stopRight);

    leftButton.addEventListener("mousedown", startLeft);
    leftButton.addEventListener("mouseup", stopLeft);
    leftButton.addEventListener("mouseleave", stopLeft);

    rightButton.addEventListener("mousedown", startRight);
    rightButton.addEventListener("mouseup", stopRight);
    rightButton.addEventListener("mouseleave", stopRight);

    restartButton.addEventListener("click", function() {

        resetGame();

    });

    resetGame();

    gameLoop();

</script>

</body>
</html>
