# Ultimate Tic-Tac-Toe with Minimax AI

This project is a Python implementation of Ultimate Tic-Tac-Toe featuring an AI opponent powered by the Minimax algorithm with alpha-beta pruning. The AI uses a heuristic scoring system to make strategic moves, aiming to create a challenging and engaging game for human players.

## Features

- **Minimax AI with Alpha-Beta Pruning**: Optimized decision-making for efficient move calculation.
- **Multi-board Win Conditions**: Supports Ultimate Tic-Tac-Toe gameplay across nine smaller grids.
- **Heuristic Scoring**: Custom scoring for claimed tiles, sequences, and positioning to enhance AI performance.
- **Interactive GUI**: Built with Pygame, featuring real-time board updates and responsive gameplay.

## Getting Started

### Prerequisites

- Python 3.x
- Pygame

Install Pygame with:
```bash
pip install pygame
```

## **Running the Game**
To start the game, run:

```bash
python UltimateTicTacToeMiniMax.py
```

## **Gameplay**
- **Mouse Controls**: Click on a tile within the allowed grid to make a move.
- **AI Turns**: The AI will automatically select and play the optimal move after each human turn.

## **Project Structure**
- **Game Logic**: Implements board state evaluations, win condition checks, and Minimax with alpha-beta pruning in Python.
- **Scoring Mechanism**: Heuristic-based scoring prioritizes advantageous moves for AI efficiency.
- **Graphics**: The Pygame library renders the multi-board layout and highlights current move options.

## **How It Works**
- **Board Evaluation**: Checks each sub-board for win conditions and scores tiles based on specific criteria.
- **Minimax Algorithm**: Recursively calculates moves, evaluating potential outcomes to maximize AI success.
- **Alpha-Beta Pruning**: Reduces the computation by pruning non-beneficial moves, improving performance.
