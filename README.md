# Tic-Tac-Toe in C++

## Introduction
Tic-Tac-Toe is a simple yet classic two-player game played on a 3x3 grid. The objective is to align three of your marks (X or O) in a row, either horizontally, vertically, or diagonally. This C++ implementation allows a player to compete against a computer that makes random moves.

## Features
- **Single-player mode** (player vs. computer)
- **Interactive console-based UI**
- **Randomized computer moves**
- **Automatic win and tie detection**

## How to Play
1. The game starts with an empty 3x3 grid.
2. The player (X) chooses a position (1-9) to place their mark.
3. The computer (O) makes a move at a random available position.
4. The game continues until:
   - A player wins by forming a line of three marks.
   - The board is full, resulting in a tie.
5. The game displays the winner or declares a tie before exiting.

## Installation & Execution
### Prerequisites
- C++ compiler (e.g., g++, clang++)

### Steps to Run the Game
1. Clone this repository or download the `tic_tac_toe.cpp` file.
2. Open a terminal and navigate to the project directory.
3. Compile the code using:
   ```sh
   g++ tic_tac_toe.cpp -o tic_tac_toe
   ```
4. Run the executable:
   ```sh
   ./tic_tac_toe
   ```

## Code Structure
- `drawBoard()`: Displays the game board.
- `playerMove()`: Handles user input for placing a marker.
- `computerMove()`: Generates a random move for the computer.
- `checkWinner()`: Checks if a player has won.
- `checkTie()`: Determines if the game ends in a draw.



## License
This project is open-source and available under the MIT License.

## Author
**Ranjith A R**

