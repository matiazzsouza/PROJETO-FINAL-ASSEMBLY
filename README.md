# 🏴‍☠️ Batalha Naval em Assembly

## 📌 Descrição
Este projeto implementa o clássico jogo **Batalha Naval** utilizando Assembly x86. O objetivo é criar um jogo interativo onde o jogador pode posicionar seus navios e tentar acertar os navios inimigos.

## 🚀 Funcionalidades
- Mapa de **20x20** para maior desafio.
- Posicionamento **aleatório** dos navios inimigos.
- Opção para **diferentes níveis de dificuldade**.
- Exibição de **regras do jogo** e interface interativa.
- **Feedback visual** ao acertar ou errar um tiro.
- Opção de **reiniciar o jogo** ao final.

## 🛠️ Tecnologias Utilizadas
- **Assembly x86 (NASM)**
- **Emulador DOSBox** (para execução em sistemas modernos)

## 🎮 Como Jogar
1. Execute o programa em um ambiente compatível com Assembly x86 (DOSBox ou outro emulador).
2. Escolha o nível de dificuldade.
3. Insira as coordenadas para atacar um ponto no mapa.
4. O jogo indicará se você **acertou** ou **errou**.
5. Continue até afundar todos os navios inimigos!

## 📂 Estrutura do Projeto
```
/
├── batalha_naval.asm  # Código-fonte principal do jogo
├── README.md          # Documentação do projeto
├── regras.txt         # Regras detalhadas do jogo
└── assets/            # Recursos adicionais (se necessário)
```

## 📜 Regras do Jogo
- O mapa tem **20x20** posições (A0 a T19).
- Cada jogador posiciona seus navios estrategicamente.
- O jogador deve inserir coordenadas para atacar o oponente.
- O jogo informa "Acertou!" ou "Errou!" a cada jogada.
- O jogo termina quando todos os navios forem destruídos.

## 📌 Controles
- Digitar coordenadas (exemplo: `B3`, `H10`).
- Pressionar **Enter** para confirmar o tiro.
- Pressionar **R** para reiniciar ao final do jogo.

---
Desenvolvido com 💻 e dedicação por Mateus Marinho e Bernardo Duque.
