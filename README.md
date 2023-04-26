- <!DOCTYPE html>

<html lang="es">

<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Abrazo virtual</title>

    <style>

        

        body {

            background: url('https://media.tenor.com/Lz_tkHmPD1YAAAAd/anime.gif') no-repeat center center fixed;

            background-size: cover;

            color: white; /* Cambio de color de texto a blanco */

        }

        * {

            margin: 0;

            padding: 0;

            body {

            }

            ;

            font-family: 'georgia', cursive;

        }

        :root {

            --loading-width: 100px;

            --loading-heigth: 13px;

        }

        body {

            width: 100vw;

            height: 100vh;

            position: absolute;

            display: flex;

            justify-content: center;

            align-items: center;

        }

        main {

            text-align: center;

            width: 70vw;

        }

        .box {

            display: inline-block;

            border: solid black 10p;

            width: var(--loading-width);

            background-color: black;

        }

        .loading-box {

            height: var(--loading-heigth);

            width: var(--loading-width);

            background-color:purple;

            animation: loading 7s;

        }

        #state-message {

            font-size: larger;

            font-weight: bold;

            color: orange;

        }

        @keyframes loading {

            0% {

                width: 0;

            }

            100% {

                width: var(--loading-width);

            }

        }

        #title,

        #result {

            margin-top: 8px;

            margin-bottom: 10px;

        }

        #me {

            margin-top: 8px;

            margin-bottom: 10px;

        }

        .box {

            margin-top: 3px;

        }

        #copyright {

            background-color: orange;

            position: absolute;

            bottom: 0;

            width: 50%;

            text-align: center;

            padding: 5px;

        }

        

    </style>

    

</head>

<body>

    <main>

        <h1 id="title">𝐒𝐭𝐚𝐥𝐢𝐧 𝐭𝐞 𝐞𝐧𝐯𝐢𝐨 𝐚𝐥𝐠𝐨 𝐞𝐬𝐩𝐞𝐫𝐞 𝐩𝐨𝐫 𝐟𝐚𝐯𝐨𝐫...🦋</h1>

        <div>

            <img id="me" src="https://media.tenor.com/YE5iCstDdVIAAAAi/cat-farsi-hug.gif" alt="" style="width: 50%; height: auto;">

        </div>

        <div class="box">

            <div class="loading-box"></div>

        </div>

        <h3 id="state-message">cargando...</h3>

        <h2 id="result">&nbsp;</h2>

        <script>

            

            setTimeout(function() {

                const message = document.getElementById('result');

                message.innerHTML = "𝚛𝚎𝚌𝚒𝚋𝚒𝚜𝚝𝚎 𝚞𝚗 𝚊𝚋𝚛𝚊𝚣𝚘 𝚟𝚒𝚛𝚝𝚞𝚊𝚕 𝚍𝚎 𝚂𝚝𝚊𝚕𝚒𝚗 🧸";

                

            }, 6200);

            setTimeout(function() {

                const message = document.getElementById('state-message');

                message.innerHTML = "&nbsp;";

            }, 6000);                       

        </script>

        <button onclick="alert('y un lapo por si acaso! 😂 ')">haz clic aquí</button>

        

            <h6 style="color: white;">copyright © stalin.qf</h6>

</div>

	<script>

		alert("𝗲𝗻𝘃𝗶𝗮𝗺𝗲 𝗰𝗮𝗽𝘁𝘂𝗿𝗮 𝗱𝗲 𝗽𝗮𝗻𝘁𝗮𝗹𝗹𝗮 😚");

	</script>

 

    </main>

</body>

</html>






