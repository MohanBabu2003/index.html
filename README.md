<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stopwatch</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="stopwatch-container">
        <h1>Stopwatch</h1>
        <div class="display">
            <span id="minutes">00</span>:<span id="seconds">00</span>:<span id="milliseconds">00</span>
        </div>
        <div class="buttons">
            <button id="startStopBtn">Start</button>
            <button id="resetBtn">Reset</button>
            <button id="lapBtn">Lap</button>
        </div>
        <div class="laps">
            <h2>Laps</h2>
            <ul id="lapsList"></ul>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
