# BlackJackGame

This is my game program, where I realized game logics of BlackJack card game.

Blackjack is a casino banked game, meaning that players compete against the house rather than each other. The objective is to get a hand total of closer to 21 than the dealer without going over 21 (busting).

At the start of a Blackjack game, the players and the dealer receive two cards each. The players' cards are normally dealt face up, while the dealer has one face down (called the hole card) and one face up. The best possible Blackjack hand is an opening deal of an ace with any ten-point card.

So I have Card class containing rank and suit as enumerators and also i can flip my card, also I have an abstract Hand class containing vector of Card objects.
Deck and Generic Player classes extends Hand, Deck is in charge of shuffling cards. 

House realizes a primitive Artificial Intelligence algorithm, while Player is our user.

Game is the main class containing as the varibles Deck, House and collection of Players.

