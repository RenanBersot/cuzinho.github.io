# cuzinho.github.io
<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .box {
            font-size: 40px;
            color: white;
            height: 250px;
            width: 350px;
            border-radius: 10px;
            background: #191919;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .buttons-container {
            display: flex;
            justify-content: space-around;
            height: 50px;
            width: 150px;
        }
        button {
            height: 30px;
            width: 50px;
            background: black;
            border-radius: 5px;
            color: white;
            font-weight: 600;
        }
    </style>
</head>
<body>
    <div class="box">
        <p><span style="font-size: 24px; color: #ffffff">C*zinho hoje?</span></p>
        <div class="buttons-container">
            <button>
                <a href="https://link.com">Sim</a>
            </button>
            <button id="no">Não</button>
        </div>
    </div>
    <audio autoplay loop>
        <source src="./360ytmp3.com_320kbps-mc-saci-faltou-czin-feat-mc-pretchako-l-dj-sammer-e-dj-matheus-henrique.mp3" type="audio/mpeg">
    </audio>
</body>
<script>
    let button = document.getElementById('no');
    let height = window.innerHeight - 50;
    let width = window.innerWidth - 50;

    button.addEventListener('mouseover', function () {
        button.style.position = "absolute";
        button.style.top = Math.random() * height + "px";
        button.style.left = Math.random() * width + "px";
    })
</script>
</html>
