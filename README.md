# Jogo da Velha com Pygame usando o algoritmo Minimax

## Descrição
Este repositório contém um jogo da velha interativo implementado com o Pygame, uma biblioteca popular para o desenvolvimento de jogos em Python. O jogo permite que dois jogadores joguem entre si ou enfrentem uma inteligência artificial (IA) baseada no algoritmo Minimax.

O algoritmo Minimax é uma técnica de busca que permite que a IA escolha a melhor jogada possível, considerando todas as possíveis jogadas subsequentes até o fim do jogo. A IA avalia cada estado do tabuleiro e atribui uma pontuação com base na sua perspectiva de vitória. Dessa forma, ela sempre busca maximizar sua pontuação e minimizar a pontuação do oponente, garantindo que tome decisões ótimas.

## Recursos e Funcionalidades
- Interface gráfica: O jogo foi desenvolvido com a biblioteca Pygame, oferecendo uma interface gráfica e interativa.
- Diferentes níveis de dificuldade: Ao começar a jogar você pode apertar a tecla "0" para que a IA escolha jogadas aleatórias ou "1" para que ela escolha de acordo com o algoritmo
- Dois modos de jogo:
  1. Modo contra IA: Os jogadores podem optar por jogar contra uma IA que utiliza o algoritmo Minimax para tomar decisões estratégicas ou uma IA que escolhe movimentos aleatórios.
  2. Modo para dois jogadores: Os jogadores podem desafiar um ao outro e competir no jogo da velha.
- Aperte a tecla "R" para resetar o jogo

## Como Executar o Jogo
1. Clone o repositório para sua máquina local ou baixe os arquivos
2. Navegue até o diretório do projeto
3. Instale as dependências necessárias utilizando o pip:
   ```python
   pip install -r requirements.txt
   ```
4. Execute o jogo da velha:
    ```python
   python tictactoe.py
   ```
