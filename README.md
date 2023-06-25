<!DOCTYPE html>
<html lang="pt-br">
<head>
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class="box">
        <p> quer casar comigo?</p>
        <div class="buttons-container">
            <a href="sim.html"><button>Não</button></a>
            </button>
            <button id="no">Sim</button>

        </div>
    </div>
    <script>
        let button = document.getElementById('no');
        let height = window.innerHeight - 50;
        let width = window.innerWidth - 50;

        button.addEventListener('mouseover', function() {
            button.style.position = "absolute";
            button.style.top = Math.random() * height + "px";
            button.style.top = Math.random() * width + "px";
        })
    </script>
</body>
</html>
