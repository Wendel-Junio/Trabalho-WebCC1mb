# Trabalho-WebCC1mb
O trabalho foi todo feito no Repl.it
https://repl.it/@WendelJunio/TrabalhoWeb#script.js

*Parte do html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Roboto'>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>nome do site</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
    <script src="script.js"></script>
  </head>
  <body  background="https://cdn.wallpapersafari.com/2/74/3Iqw2l.gif">
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
  <div class="w3-center">
  <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
    <div class="w3-large">
      <center class="w3-container w3-white">
        <div class="center p">
          <hr>
          <h1 class="main w3-text-purple w3-xxxlarge">Conversor Binário</h1><br>
          <hr>
          <textarea autofocus class="inBinario" id="inBinario" onKeyUp="convertBinary()"></textarea>
          <textarea class="outBinario" id="outBinario" readonly></textarea><br>
          <div class="about">Feito por <strong class="w3-text-purple">Wendel</strong></div><br>
        </div>
      </center>
       
    </div>
  </body>
</html>

*Parte do Js
function convertBinary() {
  var output = document.getElementById("outBinario");
  var input = document.getElementById("inBinario").value;
  output.value = "";
  for (i = 0; i < input.length; i++) {
    var e = input[i].charCodeAt(0);
    var s = "";
    do {
      var a = e % 2;
      e = (e - a) / 2;
      s = a + s;
    } while (e != 0);
    while (s.length < 8) {
      s = "0" + s;
    }
    output.value += s;
  }
}

