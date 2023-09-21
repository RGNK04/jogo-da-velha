
# JOGO DA VELHA

Esse foi o meu primeiro projeto na programação, foi criado com a finalidade de um trabalho acadêmico do meu curso de Programação Web em 2021. Nele eu me desafiei a criar um jogo da velha em que fosse possível tanto jogar com um amigo quanto jogar sozinho contra o próprio programa.

# Sobre

esse jogo foi criado com a linguagem javascript e me levou 3 dias para ficar pronto. Nele eu criei um 2 bot para cada estilo de jogo, um para quando o player começava e outro para quando o programa começava. Para isso eu tive que programar uma estratégia de resposta para cada movimento do jogador. No modo onde o programa faz a primeira jogada, criei uma estratégia simples e objetiva, dependendo de poucas respostas sobre a jogada do nosso jogador. No modo em que o jogador inicia, tive que criar uma estratégia mais complexa que respondesse de maneira inteligente qualquer jogada feita e analisando apartir das jogadas anteriores, porém para otimizar o programa, a partir de uma determinada rodada, o programa lê todo o campo, analisando a possibilidade de vencer, caso ainda não exista uma naquela rodada, o programa irá preencher de 1 a 9 o primeiro campo que ainda não estiver ocupado por algum símbulo. No final da partida, ira aparecer uma tela dizendo se você ganhou ou perdeu e com a imagem visual do tabuleiro

# Instruções

No inicio de cada rodada irá aparecer um alert com o tabuleiro do jogo da velha determinando visualmente como o jogo está no momento atual e quais campos estão livres. após o alert virá um prompt onde o jogador irá digitar um número de 1 a 9 para determinar qual campo ele irá preencher. Os campos do tabuleiro são contados da esquerda para direitac de cima para baixo, Ex:

1/2/3

4/5/6

7/8/9


# Observações e bugs

- Caso seja preenchido no prompt um campo já ocupado irá ocorrer um bug em que o jogador ira perder a vez e caso seja uma jogada que determine o movimento do programa, o mesmo irá bugar e possivelmente preencher um campo já ocupado por si mesmo também.

- O programa foi feito com a intenção de testar a lógica e aprendizado no período acadêmico criando um programa com uma finalidade e que fosse funcional, sendo assim ainda não foi investido uma aparência visual melhor para o mesmo.

- O programa está em desenvolvimento para resolver bugs e melhorar sua aparência, aceito dicas para que eu possa ter um programa com uma melhor qualidade e experiência para o usuário.
