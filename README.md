# Tic-Tac-Toe AI

This is a Python implementation of the **Tic-Tac-Toe** game, featuring a choice of two AI algorithms:

- **Minimax**: A brute force search algorithm to find the optimal move.
- **Alpha-Beta Pruning**: An optimization of the Minimax algorithm, pruning branches that do not need to be explored.

### Features

- **Two AI Algorithms**: Minimax and Alpha-Beta Pruning.
- **User vs AI**: Play as either "X" or "O" against an AI opponent.
- **Game Loop**: Players can play multiple rounds with the option to restart after each game.
- **AI Thinking Process**: The AI will automatically calculate the best move and play it.
- **Node Counting**: Both algorithms track and display the number of nodes explored during the search process.

---

## Table of Contents

- [Installation](#installation)
- [How to Play](#how-to-play)
- [AI Algorithms](#ai-algorithms)
- [Example Game](#example-game)
- [License](#license)

---

## Installation

This project requires Python to run. To get started:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/tic-tac-toe-ai.git
   cd tic-tac-toe-ai
   ```

2. **Install Python (if not already installed)**:

   - Download Python from [python.org](https://www.python.org/downloads/).
   - Ensure `python` and `pip` are available from the command line.

3. **Run the game**:

   The game is a Python script. To play, simply run:

   ```bash
   python tic_tac_toe.py
   ```

---

## How to Play

1. **Start the Game**: Upon running the game, you will be prompted to choose between two AI algorithms:
    - **1**: Minimax
    - **2**: Alpha-Beta Pruning

2. **Choose Your Symbol**: Select either "X" or "O" as your symbol.

3. **Make Your Move**: As a human player, you will be asked to input your move's row and column (0-2). You can make your move in an empty cell, and the AI will respond with its move.

4. **Game End**: The game ends when:
    - A player wins (either human or AI).
    - The board is full, resulting in a draw.

5. **Play Again**: After the game ends, you'll be prompted to play again or exit.

---

## AI Algorithms

### Minimax Algorithm

The **Minimax algorithm** explores all possible moves and selects the one that maximizes the player's advantage while minimizing the opponent's. It considers the entire game tree, simulating all possible future moves.

### Alpha-Beta Pruning

**Alpha-Beta Pruning** improves upon the Minimax algorithm by eliminating branches in the search tree that cannot possibly affect the final decision. This results in fewer nodes being explored, speeding up the process.

---

## Example Game

**AI Choice**: Let's say you choose **Minimax** and **X** as your symbol.

```
Welcome to Tic-Tac-Toe AI!

Select AI Algorithm:
1. Minimax
2. Alpha-Beta Pruning
Enter 1 or 2: 1

Choose your symbol (X or O): X

Board:
  |   |   
-----------
  |   |   
-----------
  |   |   

Enter your move row (0-2): 1
Enter your move col (0-2): 1

AI is thinking...
Board:
  |   |   
-----------
  | X |   
-----------
  |   |   

AI Move: Row 0, Col 0
...

AI wins! Better luck next time.
```

---
