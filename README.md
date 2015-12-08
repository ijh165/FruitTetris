# FruitTetris
By Ivan Jonathan Hoo (ihoo@sfu.ca)

# Description
This game combines features from Tetris and Falling Fruits (http://www.wordgames.com/search.html?query=falling+fruits). When a row  is completely  filled,  it  is  removed  and  the  tiles above it will be moved one row down. When three same fruits are in a row or column, they will be removed and the tiles above them  will  be  moved  down. This game is coded in C++ with OpenGL libraries.

# Prerequisites
This game requires Linux OS with OpenGL libraries installed.

# To run the program
1. Go to "source_codes" folder (type "cd source_codes" in terminal).
2. Type "make" in the terminal (ignore all warnings).
3. Type "./FruitTetris" in the terminal.

# Controls
- Up key to rotate the tetris block
- Left and Right key to move the tetris block left and right
- Down key to accelerate falling speed of the tetris block
- Space to shuffle color
- 'Q' to quit
- 'R' to restart

# Additional Features
- Score: 1 point for 3 same color in a row or column and 3 points for a full row (the score will be output in the terminal when the game is over).
- To make the game more difficult, I make a restriction that each individual box of the new tile piece must have a different color.

# Known Bugs/Problems
- When there is more than 3 adjacent same colour (for example there are 5 same color in a row or column), the program will only remove three of the cells. This shouldn't really be a problem but this makes the game a bit weird (and harder too).
