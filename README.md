# Board Games Guide

After when you select a game mode and game type. Human player can run following commands:

1. place (number) (number) <br />
this command allows you to place a piece (make a move).
The first parameter indicates the position in x-axis.
And the second parameter indicates the position in y-axis.<br />
e.g. `place 2 2`<br />
-> this will place a piece in the position 2, 2.<br /><br />

2. undo<br />
this command allows you to undo your latest move and redirect back to your previous turn.<br /><br />

3. redo<br />
this command allows you to redo your 'undo' command and redirect back to your recent turn.<br /><br />

4. save<br />
this command saves your current status of the game in json formatted file, so that you may resume your game in the future.<br /><br />

5. load (working in progress)<br /><br />

6. history<br />
this command will print all the moves that each player made for current game.<br /><br />
