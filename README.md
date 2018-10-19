# -jogo-da-vida-python
Jogo da vida de Conway

A ideia básica do "jogo" é começar com uma configuração simples de células vivas (organismos) que são colocadas em um tabuleiro 2D de vários métodos. Isto constitui a primeira geração. As "leis genéticas" de Conway para nascimentos, mortes e sobrevivência (as quatro regras acima) são então aplicadas e a nova geração é então colocada de acordo. Geração a geração os "jogador(es)" observam as várias imagens que surgem. 

As regras sao simples:
    1. Qualquer célula viva com menos de dois vizinhos vivos morre de solidão.
    2. Qualquer célula viva com mais de três vizinhos vivos morre de superpopulação.
    3. Qualquer célula morta com exatamente três vizinhos vivos se torna uma célula viva.
    4. Qualquer célula viva com dois ou três vizinhos vivos continua no mesmo estado para a próxima geração.
