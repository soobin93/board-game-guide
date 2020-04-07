# Board Games Guide

After when you select a game mode and game type. Human player can run following commands:

1. place [number] [number]
this command allows you to place a piece (make a move).
The first parameter indicates the position in x-axis.
And the second parameter indicates the position in y-axis.

e.g. `place 2 2`
-> this will place a piece in the position 2, 2.

2. undo
this command allows you to undo your latest move and redirect back to your previous turn.

3. redo
this command allows you to redo your 'undo' command and redirect back to your recent turn.

4. save
this command saves your current status of the game in json formatted file, so that you may resume your game in the future.

5. load (working in progress)

6. history
this command will print all the moves that each player made for current game.
