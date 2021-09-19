<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eventos Dom</title>
    <style>
        div#area {
            font: normal 20pt arial;
            background: green;
            color: white;
            width: 200px;
            height: 200px;
            line-height: 200px;
            text-align: center;
            
        }
    </style>
</head>
<body>
    <div id="area" onclick="clicar()" onmouseenter="entrar()"
    onmouseout="sair()">
        Interaja...
    </div>

    <script>
        var a = window.document.getElementById('area')
        function clicar() {
            a.innerText = 'Clicou!'
            a.style.background = 'Blue'
            a.innerText = 'Azul Confiança!'
        }
        function entrar() {
            a.innerText = 'Entrou!'
        }
        function sair() {
            a.innerText = 'Saiu!'
            a.style.background = 'green'
        }
    </script>
</body>
</html>
