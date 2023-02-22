# Tic Tac Toe Game

This is a simple console-based implementation of the popular Tic Tac Toe game using Java. The game features a 3x3 board with two players, X and O, who take turns marking the spaces in the grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.

## How to Play

To play the game, simply run the program in any Java IDE or from the command line. The game starts with an empty board and the prompt for X player to make the first move. The player should enter a number between 1 and 9 to mark the respective square on the board. The game continues until a player wins or the board is full and the game ends in a draw.

## Implementation

The game logic is implemented in a single `TicTacToe` class that uses a `board` array to store the moves and a `turn` variable to keep track of whose turn it is. The `checkWinner()` method checks the board for any winning combination, and returns the winner (if there is one) or null if the game is still in progress. The `printBoard()` method prints out the current board on the console.

The main method of the `TicTacToe` class implements the game loop that takes input from the user, updates the board, and checks for the winner. It also includes input validation and error handling for invalid inputs.

## Conclusion

This Tic Tac Toe game is a simple and fun project that demonstrates the basics of Java programming, including arrays, control structures, and user input handling.
