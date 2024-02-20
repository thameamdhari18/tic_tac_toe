# tic_tac_toe
THIS IS A CONSOLE BASED TIC TAC TOE GAME WHICH IS DEVELOPED BY USING C++ LANGUAGE.

This code is a C++ program for a simple Tic Tac Toe game that runs in the console.

Here's a breakdown of how it works:

Header includes: 
              The code includes the necessary header files for input-output operations and for using the rand() function.

Global variables:
board: 
              A 2D array to represent the Tic Tac Toe board.
choice: 
              Variable to store the user's choice of position.
row, col:
              Variables to store the row and column corresponding to the user's choice.
turn: 
              A variable to keep track of whose turn it is (either 'X' or 'O').
draw:
              A boolean variable to check if the game is drawn.
display_board() function: 
              This function displays the current state of the Tic Tac Toe board. It prints the board with placeholders for the current moves.

player_turn() function:
              This function handles a player's turn. It prompts the current player to enter their choice of position on the board. It then updates the board with the player's move and switches the turn to the other player. If the chosen position is already occupied, it prompts the player to choose another position.

gameover() function:
              This function checks if the game is over. It checks for winning conditions (three in a row, column, or diagonal) for both players. If any player has won, it returns false. If the board is completely filled without any winning condition, it returns true (indicating the game is still ongoing). If the game is drawn, it sets the draw flag to true.

main() function:
              It starts by displaying the introduction to the game.
              It enters a loop where it displays the board, prompts the current player for their move, and checks if the game is over.

              
After the game is over, it checks if there is a winner or if the game is drawn, and displays the appropriate message.


Overall, this code implements a simple console-based Tic Tac Toe game where two players take turns to play until one of them wins or the game ends in a draw.





