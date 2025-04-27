# Tic Tac Toe — Minimax vs Alpha-Beta Pruning

Welcome to a simple yet powerful implementation of **Tic Tac Toe** using Artificial Intelligence!

This project demonstrates:
- The **Minimax Algorithm** for decision making
- The optimized version — **Minimax with Alpha-Beta Pruning**
- A **performance comparison** between the two techniques
- An option for **Human vs Computer** gameplay

---

## 🛠 How to Run

1. Make sure you have Python installed (preferably 3.8+).
2. Clone this repository:
    ```bash
    git clone https://github.com/Daniyal025/AIES.git
    cd AIES/AIES\ Assignments
    ```
3. Run the main file:
    ```bash
    python tic_tac_toe.py
    ```

---

## 🎮 How it Works:

- The **AI** plays optimally using either **Minimax** or **Alpha-Beta Pruning**, depending on settings.
- A **random computer player** is used as an opponent when comparing performance.
- You can also **play against the AI** yourself after the comparison.

---

## 🚀 Features:

- **Minimax** based AI (`use_alpha_beta=False`)
- **Alpha-Beta Pruning** based AI (`use_alpha_beta=True`) — faster decision making
- **Random Computer** player for simple testing
- **Human Player** input
- **Performance Measurement**:
  - Shows execution time for both Minimax and Alpha-Beta Pruning AI
- **Game Board Printing** after every move

---

## 📋 How it Works Internally:

- **Minimax Algorithm**:
  - Explores all possible moves recursively.
  - Chooses the move that maximizes the AI's chance of winning.
  
- **Alpha-Beta Pruning**:
  - Same logic as Minimax, but **skips unnecessary branches**.
  - Reduces the number of moves evaluated, improving speed.

- **Clean Logic**:
  - Better readable win/loss scoring system.
  - Well-structured player classes (`HumanPlayer`, `RandomComputerPlayer`, `GeniusComputerPlayer`).

---

## 📈 Performance Comparison:

Before the real game starts, the program will:
- Play two automated games.
- One game using **Minimax**.
- One game using **Alpha-Beta Pruning**.
- Display the **time taken** by each approach.

This helps visualize how much **faster** Alpha-Beta Pruning can be!

---

## 🎯 Future Improvements:

- Add **difficulty levels** (easy, medium, hard)
- Add a **graphical interface** (using `tkinter` or `pygame`)
- Allow choosing **who goes first** (Human or AI)

---

# 📚 Credits

- Created with ❤️ for learning purposes.
- Demonstrates basic AI concepts using Python.
