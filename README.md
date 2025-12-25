# Tic-Tac-Toe
## What is it?
**Tic-Tac-Toe** is an application which allows the user to play the famous game Tic-Tac-Toe against the computer. 
This application consists of 5 functions:
- display_board(board): displays the game board on the screen in the required format: a 3×3 grid with borders, showing either numbers, 'X', or 'O'. 
It only prints the board and does not modify it.

- enter_move(board): asks the user to enter a move, checks that the input is valid (a number from 1 to 9 and the chosen cell is free), and updates the board by placing an 'O' in the selected position. The input is repeated until it is correct.

- make_list_of_free_fields(board): scans the board and returns a list of tuples (row, column) representing all the free cells (cells that are not occupied by 'X' or 'O'). The board itself is not modified.

- victory_for(board, sgn): checks whether the player using the symbol sgn ('X' or 'O') has won the game by completing a row, a column, or a diagonal. It returns 'me' if 'X' wins, 'you' if 'O' wins, or None if there is no winner.

- draw_move(board): randomly selects one of the free cells (using randrange) and places an 'X' there, updating the board. If no free cells are available, the function does nothing.

## How to try it?
This project was developed in Python language.

### Prerequisites
- Python 3 (version 3.x)
### Run locally
1. Clone the repository:
   ```bash
   git clone https://github.com/salvatoregrimaldi03/Tic-Tac-Toe.git
   ```
2. Open the project in IDLE or any similar IDE
3. Execute the source code and enjoy it! :)

##Built With
[Python 3](https://www.python.org/) - Core language
