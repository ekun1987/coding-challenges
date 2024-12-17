# Tic-Tac-Toe Game
A simple Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript. The game logic, including player turns, win detection, and game restart functionality, is powered entirely by JavaScript.

# ⚙ JavaScript Functionality
Key Features:
1. Game Initialization
Sets up the game by adding event listeners to the game cells and the restart button.
Starts the game and displays the current player's turn.

2. Player Actions
Handles player clicks on cells to place their mark (X or O).
Prevents moves on already occupied cells.

3. Win and Draw Detection
Checks all possible winning combinations (rows, columns, diagonals).
Declares a winner if a player aligns three marks.
Ends the game as a draw if all cells are filled without a winner.

4. Player Switching
Alternates the turn between Player X and Player O.

5. Restart Game
Resets the game board and allows players to start a new game.

# 🔑 Core Functions
initializeGame(): Sets up the game by adding event listeners and initializing the board.
cellClicked(): Handles clicks on cells and updates the game state.
updateCell(cell, index): Updates the selected cell with the current player's mark.
checkWinner(): Checks for a winner or a draw after every move.
changePlayer(): Switches the turn to the next player.
restartGame(): Resets the game to its initial state.
 # 🛠 How It Works
Players take turns clicking on the 3x3 grid to place their marks.
After every move, the game checks for a winner or a draw.
The game ends when:
A player aligns three marks (declares a winner).
All cells are filled without a winner (declares a draw).
Players can click Restart to clear the board and start a new game.