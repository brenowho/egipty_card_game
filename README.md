# Egípcia
Egípcia, jogo de cartas
2 a 4 jogadores
52 ou 104 cartas

Vou criar um jogo de cartas, chamado Egípcia, em python. Pode ser jogado de 1 (contra CPU) a 4 jogadores em rede. Serão dois baralhos, onde o naipe não tem relevância, apenas mostrar para colocar as imagens depois. 

Preparação do jogo:

São 3 cartas viradas para baixo para cada jogador, não podem ser vistas;
3 cartas viradas para cima, uma em cima de cada uma das cartas viradas para baixo;
3 cartas na mão de cada jogador

Regras:

Começa quem tiver o 3 nas cartas da mão, caso ninguém tenha, quem tiver o 4, caso ninguém tenha o 5 e assim sucessivamente;
O primeiro jogador descarta a carta e compra até que tenha o total de 3 cartas na mão;
Todos os jogadores devem ter o mínimo de 3 cartas na mão;
O próximo jogador, sentido horário, pode jogar uma ou mais cartas, sendo iguais ao do último jogador ou que sejam iguais e maiores.
Caso tenham 4 cartas iguais em cima do monte, o monte é descartado do jogo;
Caso o jogador não tenha carta maior ou igual, deverá comprar todas as cartas que estão no monte em jogo;
Quando é jogado uma carta 10 o monte em jogo deverá ser descartado do jogo;
Quando é jogado uma carta 9 o próximo jogador só poderá jogar cartas de 3 ao 9
Quando é jogado uma carta Ás, o jogador que jogou, escolhe qual jogador jogará uma carta alta ou baixa;
Cartas altas: 2, Ás e 10;
Cartas baixas: 3 ao K (rei);
Quando acabarem as cartas do monte de compra e acabarem as cartas da mão, o jogador deverá recolher as 3 cartas que estão viradas para cima;
Quando conseguir descartar as 3 cartas que estavam viradas para cima, deverá jogar no escuro, sem saber qual é a carta que será jogada;
Vence quem conseguir ficar sem nenhuma carta na mão e na mesa.

## Links Úteis

[Baralhos](https://pense-python.caravela.club/18-heranca/04-baralhos.html)
[Python](https://pt.stackoverflow.com/questions/261210/estrutura-de-dados-que-represente-um-baralho-de-cartas)

## Imagens Inspiração

![299f2186-7fbf-458e-a7ae-eecc37de194d](https://github.com/brenowho/egipty_card_game/assets/146211848/ab784443-93ee-4c9d-b4f0-a5da57ac22fa)
![9cfad3ef-f844-4a1e-afd9-9fb3fa2682e4](https://github.com/brenowho/egipty_card_game/assets/146211848/81504967-c664-4f85-acf3-06e05dc47aa6)
![5a456615-9b1e-4ce5-804b-cba732ba4182](https://github.com/brenowho/egipty_card_game/assets/146211848/53b817ee-7582-40c5-8b87-850341b2ae47)
![50328c18-1730-4bd7-a51a-7c6f39deab39](https://github.com/brenowho/egipty_card_game/assets/146211848/5781b0df-3eed-458d-9eeb-b6a5f2c25bbb)
