<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Nim_game</title>
    <link rel="stylesheet" href="nimgame.css">
    <link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
  </head>

  <body>

  <div class="heading">
    <h1>WELCOME  &nbsp TO  &nbsp NIM &nbsp GAME..</h1>
    <marquee>  ~~~ 😉let's se who wins the game👻 ~~~  </marquee>
  </div>

  <div class="stones">
    <img src="stones1.jpg" alt=""><br />
    <br>&nbsp Enter the no. of stones:
    <input type="text" id="myText" name="text1" value=""><br><br>
    <button type="button" name="button" onclick="func()" align="center">START</button>
    <center><h5 id="start" ></h5></center>
  </div>

  <div class="players">
      <h5 id="player1" ></h5>
    <p id="demo"></p>
      <p id="demo1"></p>
    <h4 id="remaining">&nbsp &nbsp &nbsp &nbsp &nbsp
       Select the no. of balls given below :</h4>
       <button type="button" name="Player 1" onclick="play()" id="countButton1" value="1">1</button>
       <button type="button" name="Player 1" onclick="play()" id="countButton2" value="2">2</button>
       <button type="button" name="Player 1" onclick="play()" id="countButton3" value="3">3</button>

  </div>


  <script src="index.js" charset="utf-8"></script>

  </body>
</html>
