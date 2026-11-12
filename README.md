# Project 1: Tic-Tac-Toe vs. the Computer in C
## Description
This project objective was to create a tic tac toe game versus a computer in C on a 3x3 board, The user plays as O and always goes first while the computer plays as X and responds with a random chosen square. 

The program uses basic c programming concepts such as:
- if and else statements 
- For, while, and do while loops
- Variables and character arrays
- Random number generators using rand() and srand()
- Boolean values  

## Code overview 
The program is divided into different functions to make it easier to understand and to make it more organized 
- init_board() Sets all nine squares to empty spaces
- display_board() Displays the board and shows which squares are available
- get_human_move() Asks the user to enter a square and see if the move is valid
- is_winner() checks the horizontal rows, vertical columns and diagonals to see if a player has won
- other_player() Switches between the player (O) and the computer (X)
- get_computer_move() Uses random numbers to choose an available space for the computer to choose
- play_game() Runs the game and checks if someone wins or the game is drawn
- play_again() Asks the user if they want to play the game again
- take_turn() Handles the current players moves and updates the board.

The board starts with nine available squares as shown below:

```text
 0 | 1 | 2
---+---+---
 3 | 4 | 5
---+---+---
 6 | 7 | 8
```
  
After the user and computer make their first moves, the board will update to show O and X in the selected squares.

The game will keep going on until one player gets 3 symbols in a row or until all 9 squares are filled. When the game ends, the player can decide to quit or to play again. 

## How to run 
1. Download or clone this repository 
2. Open the Project1.c. file in C programming 
3. Compile the program using GCC
`gcc Project1.c -o Project1`
4. Run the program
`./Project1`
5. Enter a number from 0 to 8 to place O on the board.
6. Continue playing against the computer until someone wins or the game ends in a draw.
7. Enter y to play again or q to quit.
