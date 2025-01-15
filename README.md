# Projeto: Labirinto com Threads

Este projeto implementa a solução de um labirinto utilizando múltiplas threads. A ideia principal é criar um labirinto onde ratos, representados por threads, irão se mover em direção ao queijo de forma automatizada. Cada rato será uma thread distinta e deverá seguir um caminho sem retroceder por áreas já exploradas.

## 🎯 Objetivo

O objetivo deste projeto é criar uma ferramenta que:

- Gere labirintos de forma dinâmica.
- Coloque o queijo em uma posição inicial (por exemplo, [0,0] para um labirinto matricial).
- Posicione múltiplos ratos em locais aleatórios dentro do labirinto.
- Cada rato será uma thread que se moverá automaticamente em direção ao queijo.
- Os movimentos permitidos para os ratos são: cima, baixo, esquerda e direita.
- O labirinto deve garantir que sempre exista um caminho do rato até o queijo.
- Ratos não podem retroceder por caminhos já explorados.
  
## 📋 Funcionalidades

- **Geração de Labirinto Aleatório**: O labirinto é gerado aleatoriamente com paredes e caminhos. O queijo é sempre colocado na posição inicial.
- **Movimento dos Ratos**: Cada rato é implementado como uma thread independente que se move em direção ao queijo. O movimento é realizado de forma automática.
- **Evitar Retrocesso**: Ratos não podem retroceder pelos caminhos que já passaram.
- **Controle de Threads**: Cada rato é uma thread, permitindo que múltiplos ratos se movam simultaneamente no labirinto.

## 🖥️ Como Rodar o Projeto

1. **Clonar o repositório**:
   Se você ainda não tem o repositório, clone-o com o seguinte comando:
   ```bash
   git clone https://github.com/seu-usuario/labirinto-com-threads.git


![image](https://github.com/arthurigm1/LabirintoRatos/assets/95000379/4293555f-7f1d-4b56-9761-6da4dc195f55)


## 🎨 Representação Visual no Labirinto

O labirinto é representado como uma matriz de caracteres e cores, onde:

- **Amarelo (Q)**: Representa a posição do queijo.
- **Cinza (R)**: Representa a posição de cada rato no labirinto.
- **Azul (B)**: Representa o caminho já percorrido por um rato.
