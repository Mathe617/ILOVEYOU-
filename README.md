# ILOVEYOU-
<!DOCTYPE html><html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quer namorar comigo?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        button {
            font-size: 18px;
            padding: 10px;
            margin: 10px;
            cursor: pointer;
        }
        #nao {
            position: absolute;
        }
    </style>
</head>
<body>
    <div id="container">
        <h1>Quer namorar comigo?</h1>
        <button id="sim" onclick="mostrarMensagem()">Sim</button>
        <button id="nao" onmouseover="mudarLugar()">Não</button>
    </div><script>
    function mostrarMensagem() {
        alert('Sabia que você ia dizer sim! Te amo! ❤️');
    }

    function mudarLugar() {
        var x = Math.floor(Math.random() * window.innerWidth - 100);
        var y = Math.floor(Math.random() * window.innerHeight - 50);
        var botaoNao = document.getElementById('nao');
        botaoNao.style.left = x + 'px';
        botaoNao.style.top = y + 'px';
    }
</script>

</body>
</html>
