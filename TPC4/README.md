# TPC3
## Autor: Matilde Malaínho; a111729
![foto passe](https://github.com/user-attachments/assets/8f2c4369-682d-42a6-8983-0f1cd21b9896)
### Resumo:
O objetivo deste trabalho foi desenvolver uma aplicação para gestão de um conjunto de salas de cinema de um centro comercial. Neste, existem algumas salas de cinema (que poderão estar a exibir filmes ou não), cada sala tem uma determinada 
lotação, uma lista com a referência dos bilhetes vendidos (lugares ocupados; cada lugar é identificado por um número inteiro), e cada sala tem um filme associado.
#### O modelo dos cinemas terá o seguinte formato:
#### Cinema = [Sala]
#### Sala = [nlugares, Vendidos, filme]
#### nlugares = Int
#### filme = String 
#### Vendidos = [Int]
O programa inicia por exibir um menu, a partir do qual o utilizador poderá escolher a operação que pretende realizar.
#### Algumas das funções utilizadas foram:
#### 1. `listar( cinema )` - que lista no monitor todos os filmes que estão em exibição nas salas do cinema passado como argumento;
#### 2. `disponivel( cinema, filme, lugar )` - que dá como resultado **False** se o lugar lugar já estiver ocupado na sala onde o filme está a ser exibido e dará como resultado **True** se o inverso acontecer;
#### 3. `vendebilhete( cinema, filme, lugar )` - que dá como resultado um novo cinema resultante de acrescentar o lugar à lista dos lugares ocupados, na sala onde está a ser exibido o filme;
#### 4. `listardisponibilidades( cinema )` - que, para um dado cinema, lista no monitor para cada sala, o filme que está a ser exibido e o total de lugares disponíveis nessa sala (número de lugares na sala menos o número de lugares ocupados);
#### 5. `inserirSala( cinema, sala )` - que acrescenta uma sala nova a um cinema (devendo verificar se a sala já existe);
### Link:
[TPC4.py](https://github.com/user-attachments/files/22887918/TPC4.py)
