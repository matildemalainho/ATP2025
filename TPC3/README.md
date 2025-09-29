# TPC3
## Autor: Matilde Malaínho; a111729
![foto passe](https://github.com/user-attachments/assets/8f2c4369-682d-42a6-8983-0f1cd21b9896)
### resumo:
O trabalho de casa consistiu na programação do jogo do adivinha, no qual é escolhido um número de 1 a 100, sendo este adivinhado pelo jogador. No primeiro nível é o jogador que tenta adivinhar o número escolhido de forma aleatória pelo computador. Já no segundo nível, é o computador que tenta adivinhar o número do jogador, usando o algoritmo de partição binária.
#### Nível 1:
O programa escolhe um número aleatório entre 1 e 100;
O jogador tem 7 tentativas para adivinhar;
A cada palpite:
Se for menor que 1 ou maior que 100 → mostra "Número inválido".
Se acertar → mostra "Parabéns, acertou!!" e encerra.
Se errar → informa se o número escolhido é maior ou menor que a tentativa.
Se acabar as tentativas → mostra "Oh não!! Acabaram-se todas as suas tentativas." 
#### Nível 2:
O jogador pensa em um número entre 1 e 100 e informa ao programa;
O computador tem 7 tentativas para descobrir usando busca binária (chutando sempre o meio do intervalo restante);
A cada tentativa:
Pergunta: "O número é X?"
Se a resposta for "s" → o computador vence.
Se for "n" → o jogador deve dizer se o número é "maior" ou "menor", ajustando o intervalo.
Se a resposta for inválida, o programa pede novamente.
Se o computador não acertar em 7 tentativas → mostra "O computador não conseguiu adivinhar dentro do limite de tentativas."
## Link:
[TPC3.py](https://github.com/user-attachments/files/22607183/TPC3.py)
