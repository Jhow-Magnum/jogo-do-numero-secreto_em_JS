# jogo-do-numero-secreto_em_JS
O código cria uma interação entre o jogador e o computador, onde o jogador tenta adivinhar um número secreto dentro de uma faixa especificada, recebendo feedback a cada tentativa até que o número correto seja adivinhado. O objetivo é fazer com que o jogador descubra o número secreto com o menor número possível de tentativas.


1- Inicialização do Jogo:
O jogo é iniciado com uma mensagem de boas-vindas, informando que é o "Jogo do Número Secreto".

2-Geração do Número Secreto:
Um número secreto é gerado aleatoriamente dentro de uma faixa especificada (de 1 a 5000 no exemplo). Este número é escolhido de forma aleatória para garantir que cada jogo seja único.

3- Iteração do Jogador:
O jogador é convidado a fazer uma escolha, inserindo um número através de um prompt.

4-Avaliação da Escolha do Jogador:
O código compara a escolha do jogador com o número secreto.
Se o número escolhido pelo jogador é igual ao número secreto, o jogo informa que a escolha está correta e fornece o número de tentativas que o jogador levou para acertar.
Se a escolha não for correta, o jogo fornece dicas ao jogador indicando se o número secreto é maior ou menor que a escolha feita.

5-Iteração e Contagem de Tentativas:
O jogo continua a pedir ao jogador que faça escolhas até que a escolha seja correta.
A cada iteração, o jogo conta o número de tentativas que o jogador fez para acertar o número secreto.

6-Finalização do Jogo:
Quando o jogador adivinha corretamente o número secreto, uma mensagem de vitória é exibida, informando o número secreto e o número total de tentativas realizadas pelo jogador.
