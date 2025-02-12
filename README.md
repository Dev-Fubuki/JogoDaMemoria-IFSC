# 🧠 Jogo de Memória em C

Este é um projeto desenvolvido durante a disciplina **Introdução à Programação** em 2023. Realizado como Prova Final aplicada pelo Professor **Fernando** (IFSC - Campus Canoinhas).

![Image](https://github.com/user-attachments/assets/91ecf750-8fe9-4e82-a267-143a47254a38)

## 🚀 Funcionalidades

- 🃏 Tabuleiro de 6x6 (36 posições) com 18 pares de cartas embaralhadas.
- 🕹️ O jogador deve escolher duas posições para revelar e verificar se formam um par.
- ⏳ Fase inicial de visualização das letras por 15 segundos para o jogador memorizar as posições.
- 🏁 O jogo termina quando todos os pares forem encontrados ou quando o tempo expirar.
- 🎯 O número de tentativas e o tempo total são mostrados ao final do jogo.

## 🕹️ Como Jogar

1. **Memorize as letras**: Ao iniciar o jogo, as letras serão exibidas por 15 segundos.
2. **Escolha duas cartas**: O jogador deve escolher duas posições (linha e coluna) para revelar as letras.
3. **Par ou não**: Se as letras forem iguais, o par é encontrado. Caso contrário, as letras são ocultadas novamente.
4. **Vença o jogo**: O jogo termina quando todos os pares são encontrados ou o tempo se esgota.

## 💻 Como Rodar o Jogo

### 🔧 Pré-requisitos

- Um compilador C (exemplo: `gcc`).
- Sistema Unix/Linux (para o comando `clear` e `sleep`).

### 🏗️ Compilando e Executando

1. Clone o repositório:

    ```bash
    git clone https://github.com/seu-usuario/jogo-de-memoria.git
    cd jogo-de-memoria
    ```

2. Compile o código:

    ```bash
    gcc -o jogo_de_memoria jogo_de_memoria.c
    ```

3. Execute o jogo:

    ```bash
    ./jogo_de_memoria
    ```
- Ou Baixe e Execute o Arquivo: 

   ```bash
    Memoria.Exe
   ```
    

### ⚠️ Observações

- O comando `clear` limpa a tela após cada jogada. Esse comando funciona em sistemas Unix/Linux.
- O tempo de visualização inicial é de **15 segundos**.
