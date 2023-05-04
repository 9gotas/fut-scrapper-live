Script de Leitura de Jogos de Futebol em Tempo Real
Este script em Python permite a leitura em tempo real de jogos de futebol e envia para o Telegram apenas os jogos que passarem pelo filtro escolhido pelo usuário.

Como funciona?
O script utiliza a API do Football Data para obter informações sobre os jogos de futebol em tempo real. O usuário pode escolher o filtro desejado, como por exemplo, jogos de determinado campeonato, times específicos ou jogos em uma determinada data, número de escanteios, gols, ataques perigosos...

O script é executado em segundo plano e verifica constantemente as informações dos jogos. Quando um jogo que atende ao filtro escolhido pelo usuário é encontrado, o script envia uma mensagem para o Telegram com as informações do jogo.

Como usar?
Para utilizar o script, é necessário ter uma conta no Telegram e criar um bot. Em seguida, é necessário obter o token do bot e o ID do chat para onde as mensagens serão enviadas.

Após obter as informações necessárias, basta editar o arquivo 
config.ini
 com as informações do bot e do chat, além de escolher o filtro desejado.

Por fim, execute o arquivo 
main.py
 e o script começará a enviar as informações dos jogos que atendem ao filtro escolhido para o chat do Telegram.

Conclusão
Com este script, é possível acompanhar os jogos de futebol em tempo real de forma automatizada e personalizada. Além disso, o uso da API do Football Data permite obter informações precisas e atualizadas sobre os jogos.
