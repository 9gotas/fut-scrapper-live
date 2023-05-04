<!DOCTYPE html>
<html>
<head>
    <title>Script de Leitura de Jogos de Futebol em Tempo Real</title>
    <style>
        h1 {
            font-size: 36px;
            font-weight: bold;
            text-align: center;
            margin-top: 50px;
            margin-bottom: 30px;
        }
        h2 {
            font-size: 24px;
            font-weight: bold;
            margin-top: 30px;
            margin-bottom: 20px;
        }
        p {
            font-size: 18px;
            line-height: 1.5;
            margin-bottom: 20px;
        }
        code {
            font-size: 18px;
            background-color: #f2f2f2;
            padding: 5px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Script de Leitura de Jogos de Futebol em Tempo Real</h1>
    <p>Este script em Python permite a leitura em tempo real de jogos de futebol e envia para o Telegram apenas os jogos que passarem pelo filtro escolhido pelo usuário.</p>
    <h2>Como funciona?</h2>
    <p>O script utiliza a API do <a href="https://www.football-data.org/">Football Data</a> para obter informações sobre os jogos de futebol em tempo real. O usuário pode escolher o filtro desejado, como por exemplo, jogos de determinado campeonato, times específicos ou jogos em uma determinada data.</p>
    <p>O script é executado em segundo plano e verifica constantemente as informações dos jogos. Quando um jogo que atende ao filtro escolhido pelo usuário é encontrado, o script envia uma mensagem para o Telegram com as informações do jogo.</p>
    <h2>Como usar?</h2>
    <p>Para utilizar o script, é necessário ter uma conta no Telegram e criar um bot. Em seguida, é necessário obter o token do bot e o ID do chat para onde as mensagens serão enviadas.</p>
    <p>Após obter as informações necessárias, basta editar o arquivo <code>config.ini</code> com as informações do bot e do chat, além de escolher o filtro desejado.</p>
    <p>Por fim, execute o arquivo <code>main.py</code> e o script começará a enviar as informações dos jogos que atendem ao filtro escolhido para o chat do Telegram.</p>
    <h2>Conclusão</h2>
    <p>Com este script, é possível acompanhar os jogos de futebol em tempo real de forma automatizada e personalizada. Além disso, o uso da API do Football Data permite obter informações precisas e atualizadas sobre os jogos. Aproveite e faça o download do script agora mesmo!</p>
</body>
</html>
