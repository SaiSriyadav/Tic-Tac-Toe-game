Tic-Tac-Toe Game (Python - Tkinter)

A simple and interactive Tic-Tac-Toe game built using Python, Tkinter, and NumPy. This project provides a graphical user interface (GUI) where two players can play the classic game with score tracking.

📌 Features
🟢 Interactive GUI using Tkinter
❌⭕ Player vs Player gameplay
🧠 Automatic win & tie detection
📊 Score tracking (Player X, Player O, Tie)
🔁 Click to restart game instantly
🎨 Clean and colorful design



🖥️ Demo
Click on any grid to place your symbol (X or O)
Player X always starts first (alternates after each game)
Winner or tie result is displayed at the end
Scores are maintained across rounds
Click anywhere to play again


<img width="1758" height="894" alt="Tic-Tac-Toe game and score result" src="https://github.com/user-attachments/assets/0b310d89-7d7e-4fb4-a12e-06bce7203088" />


⚙️ Technologies Used
Python 3
Tkinter (GUI)
NumPy (Game logic & board management)
📂 Project Structure
tictactoe/
│── main.py        # Main game file
│── README.md      # Project documentation


▶️ How to Run
Clone the repository:
git clone https://github.com/your-username/tic-tac-toe.git
Navigate to the folder:
cd tic-tac-toe
Install dependencies:
pip install numpy
Run the game:
python main.py


🧠 Game Logic
Board is represented using a 3x3 NumPy array
Player X = -1, Player O = 1
Win conditions:
Rows
Columns
Diagonals
Tie occurs when all cells are filled with no winner



✍️ Author
Sai Sri

Passionate Python developer
Interested in GUI applications and game development
Focused on building interactive and user-friendly projects
🚀 Future Improvements
🤖 Add AI opponent (Minimax Algorithm)
🌐 Online multiplayer support
🎵 Sound effects
📱 Mobile-friendly version
📜 License

This project is open-source and available under the MIT License
