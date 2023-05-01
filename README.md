<!DOCTYPE html>

<html lang="es">

<head>

  <meta charset="UTF-8">

  <title>música por stalin</title>

 <head>

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>

    /* Estilos CSS para el reproductor de música */

    body {

			margin: 0;

			padding: 0;

			font-family: verdana, sans-serif;

			background-image: url('https://lastfm.freetls.fastly.net/i/u/500x500/4566772a44ba9f146481c50c236a93a5.jpg');

			background-size: cover;

			background-position: center;

      backdrop-filter: blur(2px);

      display: flex;

      flex-direction: column;

      justify-content: center;

      align-items: center;

      height: 100vh;

      margin: 0;

      padding: 0;						

      color: white;

    }

    .reproductor {

      display: flex;

      flex-direction: column;

      justify-content: center;

      align-items: center;

      padding: 30px;

      background-color: #333;

      border-radius: 15px;

      box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);

      max-width: 90%;

    }

    .reproductor img {

      width: 250px;

      height: 250px;

      border-radius: 50%;

      margin-bottom: 20px;

      box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);  

    }

    .reproductor h2 {

      color: white;

      font-size: 20px;

      margin: 0;

      margin-bottom: 20px;

      text-align: center;

      text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);

    }

    .botones {

      display: flex;

      justify-content: center;

      align-items: center;

      margin-bottom: 20px;

    }

    .botones button {

      background-color: #fff;

      border: none;

      border-radius: 50%;

      width: 40px;

      height: 40px;

      margin: 5px;

      cursor: pointer;

      transition: background-color 0.3s ease;

    }

    .botones button:hover {

      background-color: #ff6378;

    }

    .barra {

      width: 100%;

      margin-bottom: 10px;

    }

    .barra input {

      width: 100%;

      -webkit-appearance: none;

      background-color: #555;

      height: 5px;

      border-radius: 5px;

      outline: none;

      opacity: 0.7;

      transition: opacity 0.2s ease;

    }

    .barra input:hover {

      opacity: 1;

    }

    .barra input::-webkit-slider-thumb {

      -webkit-appearance: none;

      appearance: none;

      background-color: #fff;

      width: 10px;

      height: 10px;

      border-radius: 50%;

      cursor: pointer;

    }

    .barra input::-moz-range-thumb {

      background-color: #fff;

      width: 10px;

      height: 10px;

      border-radius: 50%;

      cursor: pointer;

    }

    .reproductor img {

  /* otros estilos existentes */

  animation: giro 10s linear infinite;

}

@keyframes giro {

  from {

    transform: rotate(0deg);

  }

  to {

    transform: rotate(360deg);

  }

  

  </style>    

<div class="reproductor">

  <img id="portada" src="https://m.media-amazon.com/images/I/41b8F4hk1QL._UX420_FMwebp_QL85_.jpg" alt="Portada de la canción">

  <h2>SUNROOF</h2>

  <audio id="audio" src="https://drive.google.com/uc?export=download&id=1NlCkYUzsihe7tjQphDcAJZO26x3nVh8n"></audio>

  <div class="botones">

    <div class="boton">

        <button id="previous"><span class="previous-icon">◀◀</span></button>

        <div class="nombre-boton"></div>

    </div>

    <div class="boton">

        <button id="play">▶</button>

        <div class="nombre-boton"></div>

    </div>

    <div class="boton">

        <button id="pause">■</button>

        <div class="nombre-boton"></div>

    </div>

    <div class="boton">

        <button id="next"><span class="next-icon">▶▶</span></button>

        <div class="nombre-boton"></div>

    </div>

</div>

  <input type="range" id="seek" min="0" value="0" step="1">

  <span id="tiempo-transcurrido">0:00</span>

</div>

<style>

  #tiempo-transcurrido {

    font-weight: bold;

  }

</style>

<script>

  var audio = document.getElementById('audio');

var playButton = document.getElementById('play');

var pauseButton = document.getElementById('pause');

var previousButton = document.getElementById('previous');

var nextButton = document.getElementById('next');

var seekBar = document.getElementById('seek');

var timeElapsed = document.getElementById('tiempo-transcurrido');

var portada = document.getElementById('portada');

playButton.addEventListener('click', function() {

  audio.play();

  portada.style.animationPlayState = 'running';

});

pauseButton.addEventListener('click', function() {

  audio.pause();

  portada.style.animationPlayState = 'paused';

});

previousButton.addEventListener('click', function() {

  audio.currentTime -= 10;

});

nextButton.addEventListener('click', function() {

  audio.currentTime += 10;

});

audio.addEventListener('timeupdate', function() {

  var duration = audio.duration;

  var currentTime = audio.currentTime;

  var minutes = Math.floor(currentTime / 60);

  var seconds = Math.floor(currentTime - minutes * 60);

  var timeString = minutes + ':' + (seconds < 10 ? '0' + seconds : seconds);

  timeElapsed.innerHTML = timeString;

  var progress = (currentTime / duration) * 100;

  seekBar.value = progress;

});

seekBar.addEventListener('input', function() {

  var duration = audio.duration;

  var seekTime = duration * (seekBar.value / 100);

  audio.currentTime = seekTime;

});

</script>

<style>

      /* Estilos CSS para el enlace */

      #myName {

        color: white;

        text-decoration: underline;

        cursor: pointer;

        color: white;      

        

      }

    <style#myName {

    text-decoration: none;

}

</style>

<p>𝗵𝗲𝗰𝗵𝗼 𝗽𝗼𝗿 <a href="#" id="myName">𝘀𝘁𝗮𝗹𝗶𝗻.𝗾𝗳</a></p>

<script>

document.getElementById("myName").addEventListener("click", function() {

  alert("𝐠𝐫𝐚𝐜𝐢𝐚𝐬 𝐩𝐨𝐫 𝐯𝐢𝐬𝐢𝐭𝐚𝐫 𝐦𝐢 𝐩𝐫𝐨𝐲𝐞𝐜𝐭𝐨. 𝐦𝐞 𝐭𝐨𝐦𝐨 𝐡𝐨𝐫𝐚𝐬 𝐞𝐧 𝐭𝐞𝐫𝐦𝐢𝐧𝐚𝐫𝐥𝐨 :𝐜... 𝐩𝐞𝐫𝐨 𝐡𝐚𝐫𝐞 𝐜𝐚𝐦𝐛𝐢𝐨𝐬 𝐲/𝐨 𝐦𝐞𝐣𝐨𝐫𝐚𝐬 𝐝𝐞 𝐥𝐚 𝐩𝐚𝐠𝐢𝐧𝐚 :𝟑.");

});

</script>

         <a href="https://www.instagram.com/stalin.qf"><img src="https://www.freepnglogos.com/uploads/logo-ig-png/logo-ig-instagram-new-logo-vector-download-13.png" alt="Instagram" width="30" height="30"></a>

   </div>

</body>

</html>


