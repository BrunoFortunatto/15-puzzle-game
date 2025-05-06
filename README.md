# 15 Puzzle Game

## Descrição

Este é uma implementação web do clássico jogo dos 15 (ou jogo da paciência), desenvolvido com HTML, CSS e JavaScript. O objetivo do jogo é organizar as peças numeradas em ordem crescente, utilizando o espaço vazio para deslizar as peças adjacentes.  O jogo oferece diferentes tamanhos de tabuleiro (3x3, 4x4 e 5x5), placar dos melhores resultados e um modo escuro para uma experiência de usuário aprimorada.

## Como Jogar

1.  **Escolha o Tamanho do Tabuleiro:** No início ou a qualquer momento, você pode selecionar o tamanho do tabuleiro clicando nos botões "3x3", "4x4" ou "5x5".  Note que mudar o tamanho reinicia o jogo.
2.  **Mova as Peças:** Clique em uma peça adjacente ao espaço vazio para deslizá-la para o espaço. As peças só podem se mover na mesma linha ou coluna do espaço vazio.
3.  **Organize as Peças:** Continue movendo as peças até que elas estejam organizadas em ordem numérica, da esquerda para a direita e de cima para baixo, com o espaço vazio na última posição.
4.  **Acompanhe seu Progresso:** O número de movimentos e o tempo decorrido são exibidos na tela.
5.  **Pausar/Continuar:** Use o botão "Pausa" para pausar o jogo.  Clique em "Continuar" para retomar.
6.  **Reiniciar:** O botão "Reiniciar" permite começar um novo jogo com o mesmo tamanho de tabuleiro.
7.  **Vitória:** Quando as peças estiverem na ordem correta, uma mensagem de vitória será exibida, mostrando seu número de movimentos e tempo final.
8.  **Jogar Novamente:** Após vencer, clique no botão "Jogar Novamente" para iniciar um novo jogo com o mesmo tamanho de tabuleiro.

## Funcionalidades

* **Múltiplos Tamanhos de Tabuleiro:** Jogue em tabuleiros 3x3, 4x4 ou 5x5 para diferentes níveis de desafio.
* **Contador de Movimentos:** Acompanhe quantos movimentos você fez para resolver o quebra-cabeça.
* **Cronômetro:** Meça o tempo necessário para completar o jogo.
* **Placar dos Melhores Resultados:** Os 5 melhores resultados (em movimentos e tempo) são armazenados localmente para cada tamanho de tabuleiro.
* **Modo Escuro:** Alterne entre os modos claro e escuro para melhor conforto visual, especialmente em ambientes com pouca luz.
* **Tabuleiro Aleatório Solucionável:** O jogo gera tabuleiros aleatórios que são sempre solucionáveis, garantindo uma experiência justa.
* **Interface Intuitiva:** Design limpo e fácil de usar, com feedback visual claro para as interações.
* **Responsivo:** O jogo é projetado para funcionar bem em diferentes tamanhos de tela.

## Tecnologias Utilizadas

* **HTML:** Estrutura da página e elementos do jogo.
* **CSS:** Estilização e layout, incluindo suporte para o modo escuro.
* **JavaScript:** Lógica do jogo, manipulação do DOM, cronômetro, contador de movimentos, placar e interatividade.
* **LocalStorage:** Armazenamento dos melhores resultados no navegador do usuário.

## Estrutura do Código

* **index.html:** Contém a estrutura HTML do jogo, incluindo o tabuleiro, botões de controle, informações de status e placar.
* **style.css:** Define a aparência do jogo, incluindo cores, fontes, layout e estilos para o modo escuro. (Nota: o código CSS está incorporado no arquivo HTML).
* **script.js:** Contém a lógica do jogo, incluindo a geração do tabuleiro, embaralhamento, movimento das peças, verificação de vitória, gerenciamento do cronômetro, placar e modo escuro. (Nota: o código JavaScript está incorporado no arquivo HTML).

##  Notas de Desenvolvimento

* O código foi desenvolvido com foco na clareza e organização, utilizando boas práticas de programação.
* A acessibilidade foi considerada na escolha de cores e no design da interface.
* O desempenho foi otimizado para garantir uma experiência de jogo suave.
* O código é modularizado para facilitar a manutenção e expansão.

## Desenvolvedor

Desenvolvido por Bruno Fortunato.

##  Agradecimentos

* Agradecimentos à comunidade de desenvolvedores web por recursos e inspiração.
* Agradecimentos aos jogadores por testarem e fornecerem feedback.

##  Próximos Passos

* Adicionar animações e efeitos sonoros.
* Implementar mais opções de personalização (temas, estilos de peças).
* Suporte para diferentes níveis de dificuldade.
* Compartilhamento de resultados em redes sociais.
