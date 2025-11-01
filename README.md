# Unity-Para-Iniciantes-Jogo-da-Velha-Jenpex-

Um jogo da velha (tic-tac-toe) feito em Unity como projeto de estudo.  
O objetivo é praticar lógica de jogo e interface simples em C#.

<p align="center">
  <img src="https://github.com/devleocruz/Unity-Para-Iniciantes-Jogo-da-Velha-Jenpex-/blob/main/Hierarquia/Tela%20Inicial.png" alt="1020px" width="720px"> <br/>
</p>

## 🕹 Tecnologias / Stack

- Unity (versão usada: 6.2)
- C#
- Canva
- TextMesh Pro (UI)

## Funcionalidades
- Tabuleiro 3x3 clicável
- Dois jogadores locais (X e O)
- Verificação de vitória ou empate
- Reiniciar partida sem reiniciar o jogo inteiro  
- Bloqueia jogadas depois que alguém vence  
- Mostra mensagem de "X venceu", "O venceu", "Empate"


## 🗂 Estrutura do Projeto

Principais pastas em `Assets/`:

### `Scenes/`
- `SampleScene` → Cena principal do jogo.

### `Scripts/`
- `JogoDaVelhaBackEnd.cs` → Lógica principal do jogo (tabuleiro, turno, vitória e regras)

### `Imagens/`
- Arte e sprites usados na interface.

### `TextMesh Pro/`
- Fontes e materiais de texto usados na UI.

---

### Objetos principais na cena (`Hierarchy`)

- `Main Camera`
- `Directional Light`
- `Global Volume`
- `FrontEnd`
- `EventSystem`
- `Scripts` → GameObject que contém os componentes de lógica do jogo

  ### FrontEnd
<p align="center">
 <img src="https://github.com/devleocruz/Unity-Para-Iniciantes-Jogo-da-Velha-Jenpex-/blob/main/Hierarquia/Hierarquia.png" alt="315px" width="717px"><br/>
</p>
