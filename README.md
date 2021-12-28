# Tic-Tac-Toe-using-AI
Tic-Tac-Toe game AI using Minimax algorithm with alpha-beta pruning optimization and fast win heuristics.
Heuristic/Evaluation function is such that it chooses the move that makes fastest win / slowest loss by giving score to the terminal states based on the their depth.

### Features: ✨

1. User-friendly UI/UX with very smooth sliding animations.
2. Choose your own marker (X/O).
3. 2 modes - **Play against AI 🤖** or **Play against a Friend 🙋🏻‍♂️**.
4. **3 difficulty levels** for playing against AI.
5. Number of matches played, timer and scoreboard with the playing player highlighted.

## Difficulty Levels (AI): 🎚️
### 1. Easy: 
AI randomly chooses any available spot on the board.

### 2. Medium:
Minimax algorithm with 30% randomness. AI can choose a random spot with 30% probability.

### 3. Impossible:
Minimax algorithm with alpha-beta pruning for optimization of minimax algorithm as it reduces the time complexity by pruning nodes in the minimax tree (abstract).
Score to a terminal state is assigned with +- depth of that state which accounts for the closness of this terminal state to the current state. Closser terminal states means faster winning move.

## Resources: 
1. https://www.freecodecamp.org/news/how-to-make-your-tic-tac-toe-game-unbeatable-by-using-the-minimax-algorithm-9d690bad4b37/
2. https://github.com/nehakalbande/chess-engine
