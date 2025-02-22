# Tic-Tac-Toe Game

## 🏆 About the Project
Tic-Tac-Toe is a classic two-player game where players take turns marking a 3x3 grid with 'X' or 'O'. The goal is to form a horizontal, vertical, or diagonal line with three of their marks. This project is a **Java-based console application** that simulates the game with a simple yet interactive user experience.

## 🎮 Features
✅ Two-player turn-based gameplay  
✅ Dynamic board updates after each move  
✅ Win condition detection (row, column, diagonal)  
✅ Tie detection when the board is full  
✅ Simple command-line interface  

## 🛠️ Technologies Used
- Java (Core Logic & Game Implementation)
- IntelliJ IDEA (Development Environment)
- GitHub (Version Control)

## 🚀 Getting Started
### Prerequisites
Ensure you have the following installed:
- **Java 8+** (Check version: `java -version`)
- **Git** (Check version: `git --version`)

### Installation & Running the Game
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/aayushkr03/TicTacToe.git
   ```
2. **Navigate to the Project Directory:**
   ```sh
   cd TicTacToe
   ```
3. **Compile and Run the Game:**
   ```sh
   javac TicTacToeGame.java
   java TicTacToeGame
   ```

## 🎲 How to Play
1. The game starts with an empty 3x3 board.
2. Players take turns entering the **row** and **column** (0-based index) to place their mark.
3. The board updates, and the system checks for a winner.
4. The game continues until a player wins or all positions are filled (tie).
5. The result is displayed at the end.

### Example Gameplay
```
Player1 (X), enter row,column: 0,0
Player2 (O), enter row,column: 1,1
Player1 (X), enter row,column: 0,1
Player2 (O), enter row,column: 2,2
Player1 (X), enter row,column: 0,2
Player1 Wins! 🎉
```

## 📂 Project Structure
```
TicTacToe/
│── src/
│   ├── TicTacToeGame.java  # Main game logic
│   ├── Board.java          # Board structure & rules
│   ├── Player.java         # Player details
│   ├── PlayingPiece.java   # Abstract class for game pieces
│   ├── PlayingPieceX.java  # 'X' piece implementation
│   ├── PlayingPieceO.java  # 'O' piece implementation
│── README.md               # Documentation
```

## 🤝 Contributing
Want to improve this project? Contributions are welcome!  
1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature-name`)
3. **Commit changes** (`git commit -m 'Added new feature'`)
4. **Push to GitHub** (`git push origin feature-name`)
5. **Open a pull request**

## 📜 License
This project is licensed under the **MIT License** – feel free to use and modify it! 🎉

---

⭐ **Enjoy playing Tic-Tac-Toe!** Have fun coding! 🚀

