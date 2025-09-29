# TPC2
## Autor: Matilde Malainho; a111729
![foto passe](https://github.com/user-attachments/assets/185f1055-58c3-46da-ba54-06260ff0a717)
### Resumo:
O jogo dos fósforos é um jogo de dois jogadores em que se começa com um número fixo de fósforos (por exemplo, 21). Os jogadores alternam turnos e, em cada jogada, podem remover 1, 2 ou 3 fósforos. O objetivo é não ser o jogador a tirar o último fósforo.

#### Inicialização do jogo:
Define-se o número inicial de fósforos (n=21). A variável n define o número de fósforos.
O jogador começa.

#### Laço principal:
Enquanto houver fósforos:
O jogador escolhe quantos fósforos quer tirar (1 a 3) e o seu input é validado (se o número escolhido não estiver entre 0 e 4 a jogada do jogador não é válida). O número de fósforos escolhidos pelo jogador é definido pela variável n.
O número de fósforos é atualizado após cada jogada (n-=p, ou seja, n=n-p).
A jogada do computador é sempre estratégica, de modo a garantir a vitória. Esta consiste na escolha de um número (comp), de modo a que o número de fósforos após a sua jogada seja múltiplo de 5.
O número de fósforos é novamente atualizado (n=n-comp).
Esta sequência é repetida até o número de fósforos chegar a 0 (é usada a estrutura cíclica while).

#### Fim do jogo:
O jogador que for forçado a tirar o último fósforo perde. Se ,após a respetiva jogada, o número de fosfóros for menor ou igual a 0 faz-se print da mensagem "Perdeste, o computador ganhou!".
### Link para o código
[TPC2.py](https://github.com/user-attachments/files/22592345/TPC2.py)
