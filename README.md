# Snake Game - Jogo da Cobrinha

Projeto desenvolvido em Python utilizando a biblioteca Pygame como atividade acadêmica de Desenvolvimento de Jogos.

# Sobre o jogo

O objetivo do jogo é controlar uma cobra pela tela, coletar os alimentos e aumentar sua pontuação.

A cada alimento coletado, a cobra cresce e a pontuação aumenta.

O jogo termina quando a cobra:

- bate em uma das paredes;
- bate no próprio corpo.

Após o Game Over, é possível iniciar uma nova partida sem fechar o programa.

# Tecnologias utilizadas

- Python
- Pygame
- Visual Studio Code

# Estrutura do projeto

snake-pygame/
│
├── main.py
├── README.md
└── requirements.txt


# Instalação

É necessário ter o Python instalado.

Depois, instalar a biblioteca Pygame:

pip install pygame

# Executando o jogo

No terminal, dentro da pasta do projeto:

python main.py

Caso o comando `python` não funcione, pode ser utilizado:

py main.py

# Controles

| Tecla | Ação                     |
| ----- | ------------------------ |
| ↑     | Mover para cima          |
| ↓     | Mover para baixo         |
| ←     | Mover para esquerda      |
| →     | Mover para direita       |
| W     | Mover para cima          |
| S     | Mover para baixo         |
| A     | Mover para esquerda      |
| D     | Mover para direita       |
| R     | Reiniciar após Game Over |
| ESC   | Sair do jogo             |

# Funcionalidades

- Movimentação da cobra;
- Controle por teclado;
- Geração aleatória de alimentos;
- Crescimento da cobra;
- Sistema de pontuação;
- Detecção de colisão com as paredes;
- Detecção de colisão com o próprio corpo;
- Tela de Game Over;
- Reinício da partida sem fechar o programa.

# Objetivo acadêmico

O projeto tem como objetivo aplicar conceitos de programação utilizando Python e Pygame, incluindo:

- estruturas de repetição;
- estruturas condicionais;
- funções;
- listas;
- geração de números aleatórios;
- captura de eventos do teclado;
- detecção de colisões;
- manipulação de elementos gráficos;
- organização de código.
