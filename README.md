This is an UNO game for 2-4 players implemented with Python3 and the Tkinter library.
Run UNO.py to start the program.
The infobar at the show displays whose turn it is, the number of cards in other player's hands, and the number of cards in the draw pile.
5 cards are displayed at once on the screen. If the player has more than 5 cards in their hand, use the arrow buttons to cycle through the hand.
Click the "Draw Card" button to draw a card. The "End Turn" button will replace the "Draw Card" button after a card is drawn during a player's turn. Click the "End Turn" button to end turn.
Clicking on unplayable cards will not do anything, but clicking on a playable card will play it and end the player's turn, unless it is a wild card, in which case the player gets to click a button selecting the desired color before the turn is ended automatically.
After the turn is ended, there will be a button telling the next player to begin their turn. Click this button to start the turn. This feature was implemented so that other player's may not see a player's hand.

There are several differences between this version of UNO and the original UNO card game:
1. A challenge function was not able to be implemented because only one player can be on the computer at once, so a player is not able to "challenge" a draw4 card during another player's turn, since they do not have the computer.
2. We did not add an UNO button as the game was programmed so that the player's turn ends immediately once a card is played.
3. Instead of starting the game as described in the rulebook, we decided to start the game by adding cards to the discard pile
until a normal number card is on top, as that is how both of us have learned to play UNO.
4. For the same reason, we decided to make the winner the first player to run out of cards instead of going by the point system
described in the rulebook.

Another note:
We did not add code accounting for if both the draw pile and the discard pile (except the top) runs out, as in a real game,
this situation would not happen as players would be trying to get rid of their cards instead of keeping them in their hands.
Also, there is nothing in the official rulebook that explains what to do in this situation.

Made By:
Anan Aramthanapon and Jackson Fiala