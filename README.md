# Tic-Tac-Toe-Console-Application---Dart-Assesment
Develop a simple console-based Tic-Tac-Toe game in Dart. The game should allow two players to take turns making moves on a 3x3 grid until one player wins or the game ends in a draw. The application should provide an interactive and user-friendly experience.

**Running the Game

Clone the repository or copy the Dart code into a Dart file.
Open a terminal and navigate to the directory containing the Dart file.
Run the Dart file using the command: dart filename.dart

**How to Play

The game starts with an empty 3x3 grid.
Players take turns making moves by entering the number corresponding to an empty cell (1-9).
The game displays the updated board after each move.
The game ends when a player wins, or it's a draw.

**Code Structure
The code is organized into functions and follows Dart best practices for readability and maintainability:

playTicTacToe(): Main function to control the game loop and player turns.
displayBoard(List<String> board): Function to display the current state of the Tic-Tac-Toe board.
getPlayerMove(int currentPlayer): Function to prompt the current player for their move.
isValidMove(List<String> board, int move): Function to validate the player's move.
checkWinner(List<String> board): Function to check for winning conditions.
isBoardFull(List<String> board): Function to check if the board is full (draw condition).
Concepts Used
Lists: The Tic-Tac-Toe board is represented using a list.
Functions: Code is organized into functions for better structure.
Loops: Game loop ensures the game continues until there is a winner or a draw.
Conditional Statements: Used for input validation and checking winning conditions.
User Input: stdin.readLineSync() is used to get input from the console.
Error Handling: Basic error handling for invalid inputs.
Logic for Winning and Draw: Functions to check for winning conditions and a draw.
