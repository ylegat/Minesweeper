**Game steps**

* When the game starts, the player gets prompted for the grid size (width x height) and the number of mines.
* The grid is generated according to these requirements.
* The games starts, the user is prompted for the coordinates (x, y) of the first cell to uncover.
* The game shows the resulting grid and prompts for new coordinates.
* And so on ...
The game ends when there is no more non-mined cell to uncover or the player uncovers a mine.

**Rules**

* Uncover a mine, and the game ends.
* Uncover an empty cell, and the player keeps playing.
* In each empty uncovered cell the number of adjacent cells holding mines is displayed.
* Uncovering a cell holding the number '0' (=no adjacent mined cells) uncovers all adjacent cells, and so on.

**Notes**

* Command-line is sufficient, no fancy ui needed.
* Basically it's the good old windows minesweeper (minus flags).
* If you can, try solving this exercise using TDD (keep your commit history to proove you did it !) and Java 8 lambda.
* Focus on readability and simplicity.
