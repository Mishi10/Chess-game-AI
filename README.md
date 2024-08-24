# Chess-game-AI
**Chess-AI Overview:**

Chess-AI is a straightforward chess engine built in JavaScript, focusing on making smart decisions during the game.

For other features like the chessboard display and game rules, it uses external libraries:

Chessboard GUI: Powered by chessboard.js
Game Mechanics: Managed by chess.js
The AI makes its moves using the minimax algorithm, enhanced with alpha-beta pruning for efficiency.

To evaluate the game, it uses a piece square table inspired by Sunfish.py. Instead of recalculating the score for every move, it updates a global score that tracks black's advantage after each move. This score is shown on the 'advantage' bar during the game.
