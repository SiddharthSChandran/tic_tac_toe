# tic_tac_toe
________________________________________________________________
The tic-tac-toe game is played on a 3x3 grid the game is played by two players, who take turns. The first player marks moves with a cross, the second with a circle. The player who has formed a horizontal, vertical, or diagonal sequence of three marks wins. The program draws the game board, ask the user for the coordinates of the next mark, change the players after every successful move, and pronounces the winner. 

To implement this usually data structures like one dimensional and two dimensional arrays are used. We try to implement it using linked lists.

ALGORITHM
____________________________________________________________________
1.We define a structure node containing the character stored inside the board for each turn as an X or  an O. It also contains a next pointer to access the next element in the linked list.

2.Then we define the functions.

3.Then we start the main part of the program by initializing the board elements to NULL and the head of the linked list to NULL.
The move number is initialized to zero and the turn is set to the first player .i.e X’s turn.

4.A while loop is executed for 9 times as that is the maximum number of times moves can be made in a 3X3 tic tac toe. At the beginning of while loop we put the display function to display each turn. 

5.Inside the loop we ask for each time the move number and the turn and the turn is stored in the array embedded in the structure.

6.For each input we perform a check.

7.After that the linked list comes into play. 

8.We define a node tempptr and assign it’s elements like the turn and the movenumber. 

9.It is then assigned to head.

10.Move number is incremented by 1 and the function to change turn  is invoked.

11 . If there is a winner within the 9 moves the program displays the player turn and calls them as winner.

12. Else it says no winner and ends the program.

