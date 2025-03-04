# Python Chess Engine

## Overview
A fully functional chess game implemented in Python with a graphical user interface using Pygame. The project features a chess engine with advanced AI move generation, move validation, and intelligent move selection.

## Features
- Full chess game implementation
- Graphical user interface with Pygame
- AI opponent with Negamax Alpha-Beta pruning algorithm
- Move validation and advanced chess rules
- Supports special moves like:
  - Castling
  - En passant
  - Pawn promotion
- Move log and game state tracking
- Undo and reset game functionality

## Requirements
- Python 3.7+
- Pygame
- Multiprocessing

## Installation
1. Clone the repository
2. Install dependencies
3. Ensure you have piece images in an `images/` directory

## How to Play
- Run `main.py` to start the game
- Left-click to select and move pieces
- Press 'Z' to undo a move
- Press 'R' to reset the game

## AI Details
- Uses Negamax Alpha-Beta pruning algorithm
- Considers piece position and value
- Depth of move calculation can be adjusted in `ChessAI.py`
