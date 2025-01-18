# my-game
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROCK PAPER SECISSOR</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>ROCK PAPER SECISSOR</h1>
<div class="choices">
<div class="choice" id="rock">
    <img src="stone.png">
</div>
<div class="choice" id="paper">
    <img src="paper.png">
</div>
<div class="choice" id="scissors">
    <img src="seccer.png">
</div>
</div>



<div class="score-board">
    <div class="score">
        <p id="user-score">0</p>
        <p>You</p>
    </div>
    <div class="score">
        <p id="comp-score">0</p>
        <p>Computer</p>
    </div>
</div>


<div class="msg-container">
    <p id="para">play your move</p>
</div>
    <script src="script.js"></script>
</body>
</html>
