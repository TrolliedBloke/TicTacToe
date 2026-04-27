# TicTacToe

ARCHITECTURE ----------------------

GRID LAYOUT:

0 1 2
3 4 5
6 7 8

WINNING COMBINATIONS:

0 1 2
3 4 5
6 7 8

0 3 6
1 4 7
2 5 8

2 4 6
0 4 8

STRUCTURE:

1 Two Players Active

2 Player Clicks Square

3 Check to see if Square is Empty or Not
If square is not empty just return
If square is empty update cell with player marker (O/X)
Check if any player has winning combination
If yes -
return who is winner
If not -
Next players turn
