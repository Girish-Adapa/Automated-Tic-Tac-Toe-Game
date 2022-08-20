# Automated-Tic-Tac-Toe-using-C++

Implementation of the  automated Tic-Tac-Toe game


Rules of the Game

The game is to be played between two people.
One of the players chooses ‘O’ and the other ‘X’ to mark their respective cells.
The game starts with one of the players and the game ends when one of the players has one whole row/ column/ diagonal filled with his/her respective character (‘O’ or ‘X’).
If no one wins, then the game is said to be drawn.


In this program, the moves taken by the players are chosen randomly. We used rand() function for this.

The program is in not played optimally by both sides because the moves are chosen randomly. The program can be easily modified so that both players play optimally (which will fall under the category of Artificial Intelligence). Also, the program can be modified such that the user himself gives the input (using scanf() or cin).

Time Complexity: The time complexity is O(N) where ‘N’ is the number of moves as the ‘moves[]’ array is only traversed once (i.e. number of rows).

Space Complexity: The space complexity is O(1) or O(8 + 8) as 8-sized two arrays A and B are created for storing moves for 3 rows, 3 columns, and 2 diagonals for A and B players.
