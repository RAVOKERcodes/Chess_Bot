<h1>chess-bot</h1>
A chess engine by someone who has interst but don't know how to play chess.

<h2>About</h2>
chess-bot is a simple chess AI in JavaScript.

The primary concern of chess-bot is the decision-making part of the application. All functionality outside the scope of the AI are implemented using external libraries:

Chessboard GUI: Using the chessboard.js API
Game Mechanics: Using the chess.js API
The AI uses the minimax algorithm, which is optimised by alpha-beta pruning.

The evaluation function uses piece square tables adapted from Sunfish.py, and eliminates the need for nested loops by updating the sum based on each move instead of re-computing the sum of individual pieces at each leaf node.

A global sum is used to keep track of black's evaluation score after each move, which is used to display the 'advantage' bar.

<h2>How to Play?</h2>
Head over to https://ravokercodes.github.io/chess-bot

Play as white by dragging a piece to your desired location. The AI plays as black. The AI's minimax search depth (which is directly related to how well it will play) can be customised using the 'Search Depth (Black)' dropdown. Using a higher value will improve the AI's accuracy, but it will take longer to decide on the next move.

To pit the AI against itself, click the 'Start Game' button under Computer vs. Computer. You can stop the game at any time using the 'Stop and Reset' button.
