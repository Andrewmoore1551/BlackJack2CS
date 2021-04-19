# BlackJack2CS

P:

- Create a deck of 52 cards
- Create a player
- Create the house (dealer)
- Cards must be shuffled before each game starts
- Game over at 21 points. Closest to 21 wins
- Tie goes to the dealer
- Face cards = 10
- Ace = 11
- Used cards need to removed from deck until new game
- Add a hit option
- Add a stand option

E:

- Dealer: 19 player: 20 player wins
- Dealer: 21 player: 21 tie goes to the dealer
- Dealer: 18 player:17 dealer wins
- Dealer: 22 player:15 player wins
- Dealer: 21 player:16 dealer wins

D:

- Ill be keeping the deck as a list of cards objects
- Ill be keeping the players hand as a list of card objects
- Keeping a dealer hand as a list of card objects
- If the dealers hand is 17 or more the dealer will stand
- At the start of the game both the computer and players hand will store two cards
- When computer or player hit another card will be added to hand until they stand
- Print a you win message if the player wins
- Print a you lose message if the computer wins or you tie
- Were going to ask the player if he want to play again. Loop back to the begining if play again
- Repeat the previous step until they say quit

A:

- Create a list for suits { Diamonds, Hearts, Clubs, Spades }
- Create a list of card values to store the value of cards
- Use the fisher- Yates shuffle to shuffle the deck of cards in a random order
- Dealer deals two cards for the player and two cards for the computer while only displaying the player cards
- Add up the total value of the players cards and display the total value. 22 or more is a bust and you lose
- Ask the player would you like to hit or stand?
- If hit display the card, add the total value up and display it
- If stand player turn is over and is the computers turn
- Display computers hand, display it for the player the to see and add up the total value
- If the total card value is less than 17 computer hits
- Display the card, add the new total value and display it for the player to see. keep repeating this step if less than 17
- Once computer reaches 17 or more computer will stand. 22 or more is a bust and you lose
- Closest one to 21 is is the winner
- Display whether player won or player lost
- Ask the player if they’d like to play again? Go back to to shuffle the cards at random expect for when the player says “Quit”
- Quit = quit
