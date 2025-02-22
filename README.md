# Tic-Tac-Toe Game

## Overview
This is a simple command-line implementation of the classic Tic-Tac-Toe game. Two players take turns placing their marks (X or O) on a 3x3 grid. The game ends when one player forms a winning sequence or when the board is full, resulting in a tie.

## Features
- Two-player mode
- Board visualization
- Turn-based gameplay
- Win condition checking
- Detects ties when the board is full

## How to Play
1. Players take turns entering row and column numbers (0-based index) to place their piece.
2. The game board updates after every move.
3. If a player completes a row, column, or diagonal with their mark, they win.
4. If all positions are filled and no winner is found, the game ends in a tie.

## Setup and Installation
### Prerequisites
- Java installed on your system
- IntelliJ IDEA (or any Java IDE)
- Git (for version control)

### Steps to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/aayushkr03/TicTacToe.git
   ```
2. Open the project in IntelliJ IDEA.
3. Compile and run `TicTacToeGame.java`.

## Code Structure
- `TicTacToeGame.java` - Main class handling game logic
- `Board.java` - Handles board representation and piece placement
- `Player.java` - Represents a player
- `PlayingPiece.java` - Abstract class for pieces (X and O)
- `PlayingPieceX.java` - Represents X pieces
- `PlayingPieceO.java` - Represents O pieces

## Contributing
Feel free to fork the repository and submit pull requests for improvements.

## License
This project is licensed under the MIT License.

