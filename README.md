# Memory-Puzzle-Python
Memory Puzzle Game (Tkinter) 🧩
A classic Memory Matching Game developed using Python's Tkinter library. This project features a graphical user interface (GUI) and implements three distinct difficulty levels: Easy (4×4), Medium (6×6), and Hard (8×8).

Key Features
Multiple Difficulty Levels: The game utilizes a tkinter.ttk.Notebook (tabbed interface) to switch between different board sizes and complexity.

Easy: 4×4 board (8 unique pairs).

Medium: 6×6 board (18 unique pairs).

Hard: 8×8 board (32 unique pairs).

Dynamic Graphics: Shapes and colors are dynamically drawn on a tkinter.Canvas to represent the hidden 'cards.'

Game Logic: Implements core memory game logic, including:

Shuffling and initializing the answer board (random.shuffle).

Handling user clicks to reveal cards.

Checking for matching pairs and keeping them revealed.

Tracking the total number of moves for score-keeping.

Modular Code: The logic for each difficulty level is cleanly separated, using distinct variables and functions (e.g., call, call2, call3) for clarity.

How to Run
Prerequisites: Ensure you have Python 3.x installed. Tkinter is typically included with standard Python installations.

Execution: Save the code as a .py file (e.g., memory_game.py) and run it from your terminal:
