## Snakes & Ladders and Monopoly games
In this project we built a simple game application that is a mixture between the Snakes & Ladders and Monopoly games. The general idea of the game is four players moving in a grid having snakes, ladders, and Cards. The player goal is to get to the last cell before anyone else. He also takes advantage of the special cells to boost his game and obstruct his opponents. The game ends when a player reaches the last cell.

## <img  align= center width=60px src="https://media0.giphy.com/media/j3nq3JkXp0bkFXcNlE/giphy.gif?cid=ecf05e47cftu8uth80woqhyl1kr7oy4m7zaihotdf9twrcaa&ep=v1_stickers_search&rid=giphy.gif&ct=s"> Modes

1) Design mode: is where the user is able to build the playing grid, the player can add, copy, cut, paste, and delete any game object. He can also save a grid and load a previously saved grid.
2) Play mode: is where the user plays the game itself, the player is moving in a grid of 99 cells divided into rows and columns. Each cell has a number from 1 to 99. They are divided to 9 rows and 11 columns, every 3 turns, a player dice roll is used to add money to his wallet instead of moving. A player gets 10*t coins (where t is the result of rolling the dice).

## <img align= center width=50px height=50px src="https://user-images.githubusercontent.com/71986226/154076496-78b6f488-2e01-4606-a225-5bec3eb2f489.gif"> Game objects
1) Ladder
2) Snake
3) Card making the cell a special cell

## <img align=center width=50px height=50px src="https://media0.giphy.com/media/CVrs76nnBvU7azfTLj/giphy.gif?cid=ecf05e47om1y68g5als66xi5mn32ui6gk2g8wpnv145ag265&rid=giphy.gif&ct=s"> Main Toolbar Operations
[I] Design Mode:
  1) Add Ladder
  2) Add Snake
  3) Add Card
  4) Copy Card
  5) Cut Card
  6) Paste Card
  7) Delete Game Object
  8) Save Grid
  9) Open Grid
  10) Switch to Play Mode
  11) Exit

[II] Play Mode:
  1) Roll Dice
  2) Input Dice Value
  3) New Game
  4) Switch to Design Mode
  5) Exit

## <img align= center width=65px height=65px src="https://raw.githubusercontent.com/EslamAsHhraf/EslamAsHhraf/main/images/skills.gif"> Game Cards
1) Card1: Decrements the value of the passing player’s wallet by a value specified when creating the grid.
2) Card2: Moves the player forward to the start of the next ladder in the grid.
3) Card3: gives the player an extra dice roll.
4) Card4: prevents the player from rolling the next turn.
5) Card5: Moves the player backward with the same number of steps that he just rolled.
6) Card6: Instructs the player to go to a specific cell.
7) Card7: Restarts the game for the first player whose cell is after the current player in the grid.
8) Card8: This card is a prison, when a player stops at it, the player should choose either to pay specific amount of coins to go out of the prison, or stay in prison and not playing for 3 turns.
9) Cards [from 9 to 11]: This Card is a station for a specific price, this specific price is deducted from the player’s wallet in case he chooses to buy the cell, gives the player the option to buy this cell and all cells containing a card with the same number, whenever another player stops at a cell owned by another player, he has to pay fees to the player who owns the cell.
10) Card12: This card moves the ownership of the most expensive station that the current user owns from the current user to the player that has the least amount of coins in his wallet.

## <img  align= center width= 50px height =50px src="https://user-images.githubusercontent.com/71986226/154077167-a25cb6de-d3fe-494d-abf8-42204f62b177.gif"> ScreenShots
![image](https://github.com/FaresAtef1/Snakes-Ladders-Monopoly/assets/96792115/34d49efb-5599-455e-b11c-9dee3bda6b0a)
![image](https://github.com/FaresAtef1/Snakes-Ladders-Monopoly/assets/96792115/a2e1aeb5-0e67-4c69-a61c-6f5f2826f74e)
![image](https://github.com/FaresAtef1/Snakes-Ladders-Monopoly/assets/96792115/2a7753dc-6dcf-4621-b400-5a4c084a7d6b)
![image](https://github.com/FaresAtef1/Snakes-Ladders-Monopoly/assets/96792115/60c753aa-642e-4e12-a9b0-cdb60dd0cdb3)

# ©️Developers

| Name                 |         Email          |
|----------------------|:----------------------:|
| Fares Atef           | faresatef553@gmail.com |
| Amr ElSheshtawy      | Sheshtawy321@gmail.com |
| Ghaith Mohamed       |  gaoia123@gmail.com    |
