
# Tic Tac Toe Game

In this game, the players are prompted to enter their moves using the standard input/output console. The game board is displayed on the console, and each cell of the board is represented by a number. Players need to enter the number corresponding to the cell where they want to place their mark. The game then checks if the move is valid or not, and if it is, it updates the game board with the player's mark in the desired cell. The game also keeps track of the current state of the game after each move, including whether a player has won or the game has ended in a draw.

To make the game more engaging, additional features can be added, such as allowing players to choose their mark (e.g., 'X' or 'O'), implementing a scoring system, adding sound effects and animations, and even developing a graphical user interface using a library like Qt or SDL. Additionally, the game can be extended to allow players to play against a computer opponent with varying levels of difficulty, using different AI algorithms like Minimax or Monte Carlo Tree Search. This can make the game more challenging and allow players to improve their strategic thinking skills. Overall, there are many ways to extend and enhance this simple Tic Tac Toe game to make it more fun and engaging for players of all skill levels.
## Documentation


Here are the steps involved in the Tic Tac Toe game program:

1. Define a main function that will manage the overall flow of the game.
2. Create helper functions to manage the game board, including initializing the board and updating it with each player's move.
3. Create a function to prompt the players to enter their moves, and validate the input to ensure that the move is valid (i.e. the selected cell is empty).
4. After each move, update the game board with the player's mark (i.e. 'X' or 'O') in the selected cell.
5. Check the current status of the game (i.e. whether someone has won or the game is tied) after each move, and display the corresponding message to the players.
6. If the game is not over, repeat steps 3-5 for the other player's move.
7. Once the game is over, display the final game board and the winner (if any).

The game board can be represented as a 3x3 array, with each cell initialized to a default value (e.g. the cell - number). The player's move can be marked on the board with their respective mark (i.e. 'X' or 'O'). With these basic steps, a simple Tic Tac Toe game can be created without the use of graphics.


## Output

![Output](https://user-images.githubusercontent.com/91213354/223536082-9c741a2b-bd47-4f31-8d1d-f9cffe3484ab.png)


## Author

- [@atandrit](https://github.com/atandrit)

