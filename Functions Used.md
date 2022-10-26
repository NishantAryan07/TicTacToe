# TicTacToe

--Next Turn Function--
Since we are passing the row and columns in the arguments at line 123, so we need to set up those parameters in the next turn function. 
Now we need access to our player so we say "Global Player"
Now we check if the button we click on is empty. Here we see whether the text of the button we click is emtpy and whether the checkwinner() function returns false, which
would mean there is no winner. Then we would fill in that button with our player i.e. either X or O. 
Hence to see if the player button is empty we check if the player we want to select is the same as the player at 0th index of the players list (we plan on swampping them
later so we can chosose between both of them.
If the above loop is true then we take our player at that row and column and change its text to that player. 
Now after filling in that button we check to see iof we have a winner, If there is no winner then we swap player with players at index of 1
But incase there is a winner, we just print the message with player at index 0 is the winner and if there is no winner we just print the mesage tie. 
Now if the player is not equal to the player at 0th index then we chenge the button's text to wherever the player is at and and check the entire thing again

---------------------------------------------------------------------------I N C O M P L E T E-----------------------------------------------------------------------------------------------
