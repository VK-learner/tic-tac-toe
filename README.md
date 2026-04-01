# Tic-Tac-Toe (Python)

A simple, interactive **Command Line Interface (CLI)** Tic-Tac-Toe game built with Python. This project demonstrates basic programming logic, including input validation, game state management, and win-condition algorithms.

## 🚀 Features
* **Two-player gameplay:** Play locally with a friend.
* **Input Validation:** Prevents players from picking occupied slots or entering invalid coordinates.
* **Draw Detection:** Automatically recognizes when no more moves are possible.
* **Clean Interface:** Dynamic board rendering after every turn.

## 🛠️ How to Run
1.  **Ensure you have Python installed:**
    ```bash
    python --version
    ```
2.  **Clone the repository:**
    ```bash
    git clone [https://github.com/VK-learner/tic-tac-toe.git](https://github.com/VK-learner/tic-tac-toe.git)
    cd tic-tac-toe
    ```
3.  **Run the game:**
    ```bash
    python main.py
    ```

## 🎮 How to Play
* The board is represented by indices **0 through 8**.
* Players take turns entering a number to place their mark (**X** or **O**).
* The first player to get three in a row (horizontally, vertically, or diagonally) wins!

```text
 0 | 1 | 2 
---|---|---
 3 | 4 | 5 
---|---|---
 6 | 7 | 8
```

## 📂 Project Structure
```
tic-tac-toe/
├── main.py         # Main game loop and logic
├── board.py        # Board state management and display
├── game.py         # Game rules and win condition checks
└── README.md       # Project documentation
```

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.  
You are free to use, modify, and distribute this software with proper attribution.