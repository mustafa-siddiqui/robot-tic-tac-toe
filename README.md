# Calico Robot Tic-Tac-Toe Game
Code for a tic-tac-toe game played against a Calico Myro Robot on a physical board. 
(Written using the 'Myro' library)

There are functions written for the movement of the robot (the robot remembers it's orientation and according to that, moves to the next square to be moved to), detection of a sign placed on the board, and then for the game in general. Function for robot movement use a 2D coordinate system `{(0,0), (0,1) ...}` while the game functions use a 1D coordinate system `{1, 2 ...}`, so there are functions that convert between the two coordinate systems.

A demonstration of how it works can be seen [<ins>here</ins>](https://drive.google.com/file/d/1tKolPaJLSlm88Gb1pUVR5TVBfCzfNAeq/view?usp=sharing). 
> You make a move and then the robot scans the board for your move, and the proceeds to make its move by making a beep at a square on the board. It then returns to the middle of the board and waits until the user indicates that they have made a move through the terminal. Then the process repeats. The robot is by no means 'intelligent'. It will make the generic moves against the user.
