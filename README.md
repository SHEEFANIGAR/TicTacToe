# Tic-Tac-Toe Game in Java

A simple **3x3 Tic-Tac-Toe game** implemented in Java.  
This project helped me practice **Java fundamentals** like arrays, loops, conditional statements, exception handling, and basic OOP concepts.

---

## Features

- Two-player game (X and O)
- Console-based interface
- Validates user input:
  - Only allows numbers 1-9
  - Prevents moves in occupied slots
- Detects win or draw automatically
- Displays the current board after each move

---

## How It Works

1. The board is represented as a 1D array of strings (`board[9]`).
2. Players take turns entering slot numbers to place their mark (X or O).
3. After each move:
   - The board is printed
   - The game checks for a winner or draw
4. The game ends when a player wins or the board is full.

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YourUsername/TicTacToe.git
```
2. Navigate to the project folder:
```bash
cd TicTacToe
```
3. Compile the Java file:
```bash
javac TicTacToe.java
```
4. Run the game:
```bash
java TicTacToe
```
5. Follow the prompts to play!
