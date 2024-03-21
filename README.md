# Blackjack Game

Welcome to the Blackjack game implemented in Java! This simple console-based game allows you to enjoy the classic casino experience of Blackjack right from your command line. Below you'll find information on how to play the game and what each part of the code does.

## How to Play
Setup:

Run the Blackjack class.
Follow the prompts to begin the game.
You'll be dealt two cards and the dealer will also have two cards, one of which is face down.
Player's Turn:

You'll be prompted to either hit or stay.
If you choose to hit, you'll receive another card.
If your total goes over 21, you bust and lose the game.
Dealer's Turn:

Once you choose to stay, the dealer reveals their face-down card and draws additional cards until their total is at least 17.
If the dealer busts (goes over 21), you win the game.
Determining the Winner:

The winner is determined by comparing the total values of the player's and dealer's hands.
The player wins if their total is higher than the dealer's and the dealer hasn't busted.
Game End:

Once the winner is determined, the game ends.
## Code Explanation
drawRandomCard():

Generates a random number between 1 and 13 to represent a playing card.
cardString(int cardNumber):

Returns a string representation of the card based on its number.
faceDown():

Returns a string representation of a face-down card (used for the dealer's initial card).
hitOrStay():

Prompts the player to choose between hitting (getting another card) or staying (ending their turn).
Main Method:

Controls the flow of the game, including dealing cards, player and dealer turns, and determining the winner.
## How to Run
To run the game, simply execute the main() method in the Blackjack class. Follow the prompts displayed in the console to play the game.

Have fun and good luck!
