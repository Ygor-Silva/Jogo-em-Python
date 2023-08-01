# Jogo Pedra, Papel e Tesoura

Implementação em Python do clássico jogo pedra, papel e tesoura. O usuário joga contra o computador que escolhe aleatoriamente sua jogada. O código compara as escolhas para determinar o vencedor de cada rodada. O loop do jogo continua enquanto o usuário desejar jogar novamente. Um projeto simples servindo como exemplo para iniciantes que estão aprendendo Python. Ótimo para praticar conceitos básicos como entrada e validação de dados, aleatoriedade, comparações e loops.

## Como Jogar

Quando você executar o jogo, será solicitado a escolher entre pedra, papel ou tesoura. O computador então escolherá aleatoriamente entre essas três opções.

Depois que ambas as escolhas forem feitas, o programa determinará um vencedor e imprimirá quem ganhou aquela rodada.

O jogo continuará jogando rodadas até você decidir sair.

## Visão Geral do Código

A lógica principal do jogo está em `jokenpo.py`.

- `get_computer_choice()` seleciona aleatoriamente uma escolha usando o módulo `random` do Python
- `get_player_choice()` pede uma entrada do usuário e valida se é uma escolha válida
- `check_winner()` compara as escolhas e determina um vencedor
- `play_game()` contém o loop principal do jogo

## Exemplo de Jogo

```
Escolha pedra, papel ou tesoura: pedra
O computador jogou: papel
Computador ganhou!

Jogar novamente? (s/n) s

Escolha pedra, papel ou tesoura: papel
O computador jogou: tesoura 
Você ganhou!

Jogar novamente? (s/n) n
```

Como mostrado acima, o jogo continuará jogando rodadas até você decidir sair.