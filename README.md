# Get The Key - The first prototype (v0.0.1)
Get the key is a quick and simple board game that can play by 2 to 6 people.

## Goal of the game
The goal of the game for a player is to get a key and then comeback to his or her starting point.

## The elements of the game

There are 5 elements in the game:

* A set of 5 dice in which one die has a different color from the others called the movement dice.
* A hexagon map with the dimension of 23 cells in a row x 13 cells in a collumn. (With the keys marked in the map in setup phase)
* A set of 6 different players indicators.
* A set of many (100) enegery indicators.
* A deck of card which contains 30 cards in which:

  * Each card has a value from 1 to 10.
  * There is a set of 10 advancement cards.
  
    * For a user to move his or her character. The number of cells a player can move indicate by the value in the played card.
  
  * There is a set of 10 push back cards.
    
    * Push all other players back a number of columns equivalent with the value in the card.
    * If the player being pushed back has yet to take a key then his or her starting point is the furthest point he or she can be pushed back to.
    * If the player being pushed back has taken a key then that key place is the furthest point he or she can be pushed back to.
    
  * There is a set of 10 shield cards.
    
    * Use to substract the push back card value. If the result is bigger or equal 0, the push back card has no effect to the player play the shield card. If the result is -x, then x is the final number of column the player play the shield card to be pushed back.

## Set up

* All the players start from the edge of the map either row 1 or row 13
* Roll the dice to determine who can place his or her character first. The bigger the results of the dice to better. 
* The number of keys available will be the same with the number of players.
* All the keys are place in column 11 of the map.
* A key can be picked up by just go to the cell contain the key.
* A player start with 3 cards and will refill after each turn to always has 3 cards.

## End game condition

* The game end when a player come back to his or her starting point successfully with the key. 

## A player turn
  
1. Roll 4 dice other than the movement dice. 
2. Roll the movement dice.
3. [Resolve the dice](#resolve-the-dice).
4. Use cards as long as having enough energy and cards on hand.

  * A card can be used if a player spend the number of energies equal to the value in that card.
  * A push back card will affect all players other than the one who play that card.
  * A shield or advancement card will affect one the one who play that card.  

## Resolve the dice

* When there is a double in the 4 normal dice, take the number of energies equivalent to the number in one die of the double.
* When there is a triple in the 4 normal dice, take double the number of enegies when having double.
* When there is a quadruple in the 4 normal dice, take triple the number of energies when having double.
* When the movement die has a value bigger than or equal to a value in any of the double, triple, quadruple in the normal dice, then the player who roll the dice award free movement equivalent to the value of a value in a normal die. If there are two doubles of normal dice and a movement die value is bigger than both, the player will be rewarded with a free move equivalent to the value of a dice in the bigger dice pair. For example: 

  * If a player roll two 4 and two 2, and the movement die value is 3 then the player get 2 steps free move.
  * If a player roll two 4 and two 2, and the movement die value is 5 then the player get 4 steps free move.
  

## Find available material for test plays
It is very easy to prepare for a test play.

* Prepare a map: You can go to the google and download a hexagon map. Printed it out to A3. The map can be a bit bigger, in that case you can use a pen to filter out extra cells.
* Prepare player indicators: You can get 6 different bottle cap as the player indicators.
* Prepare dice: You can buy 5 different color dice in the online stores or local stores and indicate one color as the movement dice.
* Prepare energies: You can cut paper to small identical pieces.
* You can draw a set of cards with your signs or buy a deck of playing cards. One way of using a deck of playing card: 
  
  * Use diamonds cards as shield cards
  * Use hearts as advancement cards
  * Use spades as push back cards
  
## Ideas

* Your ideas to improve the game are welcome. Please open an issue for it. 

# HAVE FUN PLAYING!

## LICENSE

* The code in this repository is under an MIT license.
* This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) - [![License: CC BY 4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](https://creativecommons.org/licenses/by/4.0/)
