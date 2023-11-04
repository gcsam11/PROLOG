# 2023/2024 PFL Project - Differo_7

For the 2023/2024 Functional and Logical Programming course, we chose to do the Differo board game.

## Instalation and Execution

To install and execute the game Differo, firstly, you will need to download PFL_TP1_T03_Differo7.zip and then proceed to unzip it. Secondly, you will need to use Sicstus to consult the main.pl file which is inside the src directory. Finally, the game starts with the predicate play/0:

```
? - play.
```

## Game Rules

Differo is a game for two players. It is played with a hexagonal board and 13 black and white pieces each.

In this game, you win by calculating the difference in strength between your side and the enemy side, and by supporting your own side or blocking the opponent’s side to reach the goal.

While steadily advancing your own piece, you often find yourself unable to stop the opponent’s pieces that is closing in. This is a fun abstract game with simple rules and thrills.

### Components

- 13 white and 13 black pieces each
- Hexagonal board with 5 on a side

### End condition

- You win when one of your piece reach the goal.
- You lose if you cannot move any of your pieces in your turn.

### Preparation
- Place pieces in predetermined positions.
- Choose your own color. White is the first turn.

### Play procedure
- On your turn, you moves only one of your pieces according to the following rules
- The piece moves on a line. The piece may jump over any number of pieces at once, either your own and your opponent’s.
- The number of steps to move the piece is always (number of your pieces) − (number of your opponent’s pieces) on the line to be moved. If this value is less than or equal to 0, the piece cannot move on the line.
- You cannot move the piece off the board or into a place already occupied by another piece.
- You cannot move the piece into the opponent’s goal.

## Game Logic
 
TBD.

## Contribution

This project was done by:
- Gonçalo de Castilho Serra Alves Martins (up202108707)
- Diogo Silveira Viana (up202108803)

Both students had a 50% collaboration in the project.

## Conclusions 

TBD.

## Bibliography
The main references used were:
- Game rules: https://boardgamegeek.com/boardgame/375056/differo
