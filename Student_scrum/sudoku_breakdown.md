# Sudoku
## Logic structure
- Grid
- Validation
	- Numbers from 1-9 in 3x3 section
	- Numbers from 1-9 on each horizontal and vertical line
	- No duplicates anywhere
- Problem history to prevent playing the same sudoku again
## UI
- How many empty squares are left
- Selected square highlight
- Conflict indicator when inputting a duplicate
## Menus/screens
- Start screen
- Game screen
- End/win screen
## Input
- Input position selection
- Possible values (no 0, only \[1-9\])
- Only keyboard?
- Mouse for selection?
## Graphics
- Ascii
- Colors for indication and hierarchy
## Statistics
- How many guesses did you take
## Problem generation or library
- How to create new problems
- How to select problems of a given difficulty
- If using library:
	- Format for saving/loading problems, data file type
## End of game
- Validation of entire grid
- Congratulations message
- Back to menu, new problem, exit
