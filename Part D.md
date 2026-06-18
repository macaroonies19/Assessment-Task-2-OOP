# Part D — Game Mechanics Design
## Round:
A round is played with all players with the deck split evenly among all players, then the person to the left of the dealer starts, they pick an attribute on their card and whoever has the best stat of that attribute wins everyone's cards. It is then the next players turn in clockwise order.

## Attributes:
Attributes are selected to make cards have even stats, e.g. a car with a high top speed will most likely come at a higher price, which is an unwanted attribute.

## Winners:
Whoever has the highest/best statistic of the chosen attribute will win everyones cards.

## Draw:
In the event that two players have an even stat for an attribute, it can be settled via the original player who chose the attribute to select another attribute on their card, and the people who have drawn will see who has the best statistics and will win the cards.

## Ending:
The game ends when one player has won all of the cards from the deck.

## Structure Chart:
```text
Top Trumps Game
│
├── Game Setup
│   ├── Load Cards
│   └── Create Players
│
├── Game Play Loop
│   ├── Deal Cards
│   ├── Select Current Player
│   ├── Choose Attribute
│   ├── Compare Attributes
│   ├── Determine Winner/Draw
│   ├── Award Cards
│   └── Check Win Condition
│
└── End Game
    └── Display Winner
```