# Tic-Tac-Toe
This project revolves around the creation of a command-line-based Tic Tac Toe game using Python, without utilizing a graphical user interface (GUI). The primary objective is to implement the game's fundamental mechanics using Python's inherent data structures and control flow constructs. The game will feature a textual interface where players input their moves. The key components of this project include devising the game board as a 3x3 nested list, realizing game logic through conditional statements and iterative loops, and crafting a basic command-line interaction using Python's input() function.

Furthermore, the project encompasses thorough testing and debugging phases to guarantee the game's flawless functionality. The classic Tic Tac Toe gameplay unfolds on a 3x3 grid, with participants taking turns to place their designated symbol (X or O) onto the grid, aiming to achieve a sequence of three symbols in a row. The game concludes either when a player achieves this goal or when the grid is completely occupied without any player securing a winning sequence, resulting in a draw.

## Here's a stepwise breakdown of the game's logic

1. Formulate the game board structure as a 3x3 list of lists. Each element in the list symbolizes a grid square, initially set as an empty string.
2. Develop a function to print the game board to the console. This function will accept the game board as input and utilize loops to iterate through rows and columns, displaying each square in its corresponding position.
3. Create a function to manage player moves. This function will take the game board and the current player's symbol as inputs, prompt the player for their move (via input()), and update the game board with the player's symbol in the appropriate square.
4. Design a function to inspect for a win. This function will receive the game board and the current player's symbol as arguments, assessing whether any rows, columns, or diagonals on the board contain a continuous sequence of the player's symbols.
5. Establish a function to detect a tie. This function will take the game board as input and assess whether all squares on the board are filled.
6. Construct a central game loop that alternates between the two players. In each loop iteration, the game's current state will be displayed, players will be prompted for their moves, the game board will be updated, and checks for victory or a draw will be performed. If a win or draw is confirmed, the loop will terminate, and the pertinent message will be displayed.
7. Validate the game's functionality by actively engaging in gameplay, confirming the proper handling of player moves, accurate detection of wins and draws, and the presentation of suitable messages.
8. Methodically address and resolve any arising issues through debugging.
