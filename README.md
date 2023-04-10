# Tic Tac Toe Game

This is a simple Tic Tac Toe game created using Python, where a user can play against the computer.

# Prerequisites

You need to have Python 3 installed on your machine. You can download Python from the official website:
https://www.python.org/downloads/

# Installing

    1.Clone the repository to your local machine:
    git clone https://github.com/your-username/tic-tac-toe.git

    2.Change into the project directory:
    cd tic-tac-toe

    3.Run the game:
    python tic_tac_toe.py

# How to Play

The game is played on a 3x3 grid. The user is represented by "X" and the computer is represented by "O". The user goes first.

To make a move, the user should enter the position number on the grid where they want to place their "X". The position numbers are as follows:

    1 | 2 | 3
    ---------
    4 | 5 | 6
    ---------
    7 | 8 | 9


# Code Explanation

This is a basic Python script in which the game board is represented as a list of 9 strings, numbered from 1 to 9, representing the position of elements on the board.

The user starts the game by entering their desired position on the board, and the computer's move is chosen using the built-in random module to generate a random number from 1 to 9. If the random value is already taken, the module will regenerate a new number until an empty location is found.

The winner is decided based on the position of the elements on the board.
