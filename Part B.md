# Part B - Class Design
## Car Class:
Attributes:
+ Price
+ Smart Systems
+ Horse Power
+ Top Speed
+ Fuel EFficiency
+ Weight

Methods:
- Generate Attributes()
- Display Attributes()

Role: It provides data for cars that can be transfered onto cards.

## Card Class:
Attributes:
+ Car
+ ID
+ Image

Methods:
- Compare Stats()
- List Stats()

Role: It makes car objects from the car class into playable cards.

## Deck Class:
Attributes:
+ Cards
+ Size

Methods:
- Shuffle Cards()
- Hand Out Cards()

Role: The deck stores and organises all cards and moves the cards into the players hands during the game loop.

## Player Class:
Attributes:
+ Cards In Hand
+ Current Card

Methods:
- Choose Stat()
- Add Cards()
- Has Cards()

Role: The players uses cards and control the flow of the game.

## Game Class:
Attributes:
+ Players
+ Deck

Methods:
- Start Game()
- Win()
- Lose()

Role: Loop the game so players can play.