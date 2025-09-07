
# 🎲 Trabalho: Diagonal 6
Este repositório contém a solução do problema **Diagonal 6**, desenvolvido como trabalho da disciplina de **Estrutura de Dados I**.  
Este trabalho foi implementado integralmente em **C++**, utilizando Pilha, Fila e lógica.

---
  ### O jogo: 
  •Trata-se de uma competição entre 4 pessoas. O objetivo é marcar mais pontos que seus
  oponentes.
  • As peças:
  o As 6 torres, uma estrutura vertical usada para manter as jogadas prévias dos jogadores, e
  visualizar o estado do jogo. Cada torre possui 6 espaços. A diagonal principal esta marcada
  pela linha verde
  
  <img width="328" height="297" alt="Captura de tela 2025-09-07 130553"   src="https://github.com/user-attachments/assets/fec66398-b70a-4c9d-8ffb-e3eff6c94553" />
  
  o As fichas: Cada jogador recebe 11 fichas de uma cor. Podendo escolher entre Azul,
  Vermelho, Roxo e Branco. Alem das 11 fichas o jogador também recebe 2 fichas pretas.
  Em cada ficha tem escrito um numero indicando a qual torre ela pertence.
  
  <img width="428" height="137" alt="Captura de tela 2025-09-07 130604" src="https://github.com/user-attachments/assets/db50692b-c29c-4188-bfff-7324cf7e2752" />
  
 • Iniciando o Jogo: 
  As fichas de cores semelhantes são agrupadas e entregues aos respectivos jogadores. As fichas
  pretas são distribuídas e cada jogador recebe duas. Todas essas fichas estão embaralhadas, sem
  uma seqüência pré definida. O jogo sempre começa pelo jogador Azul, seguido pelo Vermelho,
  Roxo e Branco, respectivamente. Cada ficha é empilhada na torre que tem o mesmo numero
  descrito na ficha. As fichas são empilhadas uma a uma por cada jogador. Quando uma ficha preta
  é jogada, é retirada a ficha no topo da torre indicada pela ficha preta. O jogo continua até    que todas as torres estejam completamente cheias. Ao terminar, a pontuação é contada. O         vencedor é o jogador com mais fichas na diagonal principal da torre. Cada ficha que um   jogador consegue colocar na diagonal principal vale um ponto.

---
