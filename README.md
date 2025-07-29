# Tic_Tac_Toe
 Introduction
The Tic Tac Toe game is a classic two-player game that involves strategy, planning, and quick decision-making. This Python-based version is a console application built using Object-Oriented Programming (OOP) principles. It allows two players to play alternately by entering positions on a 3x3 board using the numbers 1 to 9. The game continuously checks for a winning condition or tie and ends appropriately with a message.

This mini project demonstrates how simple logic, condition checking, and user input can be combined to create an interactive command-line game using Python.

✅ Objectives
To implement a two-player Tic Tac Toe game.

To use classes and functions for structured and reusable code.

To handle user input and validate moves.

To check for winning conditions or a tie.

To enhance user experience with clear UI formatting and time delay.

⚙️ How It Works – Step-by-Step:
The program starts by initializing an empty 3x3 board.

Player X begins the game.

The board is displayed with current placements.

The player is prompted to choose a position (1–9).

The program:

Validates the input.

Updates the board with the player's symbol.

Checks for a win or a tie.

If no one has won yet, it switches to the next player.

The loop continues until:

One player wins, or

The board is full (tie).

A final message is shown and the game pauses briefly before exiting.

🧪 Winning Conditions Checked
3 symbols (X or O) in:

Any row (horizontal line)

Any column (vertical line)

Either of the two diagonals

📋 Sample Board Layout (Position Guide)
markdown
Copy
Edit
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9
Players use this mapping to enter their move number.

👨‍💻 Technologies Used
Python 3.x

Console I/O (input, print)

Time delay using time.sleep()

OOP concepts (Class, Methods, Attributes)

📦 Conclusion
This project is a beginner-friendly implementation of a popular game. It demonstrates how fundamental programming concepts such as loops, conditionals, and classes can be applied to create engaging user-interactive applications. It’s also a great stepping stone for building more advanced versions like:

GUI-based Tic Tac Toe (Tkinter, PyQt)

Online multiplayer Tic Tac Toe (using Flask/Django)

AI opponent with Minimax Algorithm

