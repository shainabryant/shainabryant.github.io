# Make A Buck  
This is a game I have played with my students with actual playing cards. I thought it would be cool to make a digital version of it.


## Two Player Game 
- The user will play against the opponent (computer).


## Rules of the game
- The object of this game is to be the first to collect ten cards that exactly equal $1.00.
- This game is played using a complete deck of cards.
- In this game, Ace = $0.01, Two = $0.02, Three = $0.03, … Tens = $0.10, Jack = $0.11, Queen = $0.12 and King = $0.13.
- To begin, the opponent (computer) will shuffle the deck and deal ten cards to each player.
- Player and opponent then take turns drawing and discarding one card at a time until the deck of cards is depleted or someone collects exactly $1.00.


## Win State
- The first to collect ten cards that equal $1.00 wins that round and earns 1 point. 
- If no one has $1.00 after the deck is depleted, the person closest to $1.00 (without going over) earns 0.5 point.
- The player with the most points at the end of the 5 rounds (or when the game is quit) wins the game. 


## Lose State
- If a player goes over $1.00, they will lose the round.
- If a player has a lesser total than the other player when the deck is depleted, they will lose the round.
- The player with the lowest score when the game is over or quit is the loser of the game.


## Multiple rounds to play
- At the end of each round, the live player has the option to move to the next round or end the game. They will see the following prompt (or something similar): "Would you like to move to the next round or quit the game?")


## Technical Challenges
- shuffle cards



## Wireframe
![Game Open](/wireframe/game-open.png)
![Game Play](/wireframe/game-play.png)
![Game Round End](/wireframe/game-round-end.png)
![Game Over](/wireframe/game-over.png)


## Timeline 
- Wednesday - finalize proposal, create wireframe, videos and articles for tech challenges, create files (css, html, js), COMMIT!!
- Thursday - create psuedocode, create divs for the game, begin to gather game assets, COMMIT!!
- Friday - work on HTML & JS, COMMIT!!
- Saturday - work on HTML & JS, COMMIT!!
- Sunday - work on HTML & JS, start CSS, COMMIT!!
- Monday - finish styling with CSS, COMMITT!!, submit Github link (YOU DID IT! YAY!!)

---

### Note to Self: Ideas for Variation for later development
- To make the game a little easier, change the cards to whole number values and play to $100. For instance, Ace = $1, Two = $2 and so on.

- To make the game a little more challenging, use integer operations: make the black cards positive values and red cards negative values and play to zero.

