# Sudoku-Solver
This is a fully functional sudoku game with auto-solving capabilities written in python using pygame. The user may click on any empty square and type a number that they think goes in said square. If they are right, the number will appear in the square. If they are wrong, they will get an X. Three X’s and you lose the game. If the user has given up on solving the puzzle, they may press the spacebar to have the computer solve it for them. The code reads a board setup from a file so that the user may add more puzzles if they so choose.

Images:

![image](https://user-images.githubusercontent.com/43431078/127757906-451202ea-2c18-49a6-9be9-c68bfc4426bc.png)

![image](https://user-images.githubusercontent.com/43431078/127758079-92dcf4f2-e7d5-4bfa-8586-719ea8247155.png)

These first two images show the initial board state and the board after some time of playing. The board in the second image shows two X's at the bottom of the image meaning the player only has one more incorrect quess left. The dark grey square in the second image shows which square is currently selected. 

![image](https://user-images.githubusercontent.com/43431078/127758112-81691b32-4299-44a4-a6a3-0b85104de2d6.png)

![randsnip (2)](https://user-images.githubusercontent.com/43431078/127758136-c730b7fe-d07c-404c-b33b-a28c0f9a0d1b.PNG)

![image](https://user-images.githubusercontent.com/43431078/127758158-e55952d2-93b9-4f3e-9cae-96def1a41298.png)

These last three images show the sudoku solver solving the board. The images don’t give it justice as it is much cooler to see live. The player gets to watch as the board slowly fills up and eventually solves. For those interested, the solver is an implementation of a depth first search!
