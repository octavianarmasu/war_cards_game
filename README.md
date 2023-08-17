#Copyright Octavian Armasu


**War Cards Game README**


## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)

## Description
The "War Cards Game" is a simple text-based card game implemented in Python
using Object-Oriented Programming (OOP) principles. The game simulates a series
of rounds where two players compete against each other by drawing cards from
their respective decks. The player with the higher card rank wins the round,
and the game keeps track of the number of rounds played and the player who wins
each round.

## Installation
1. Clone or download the repository from GitHub.
2. Ensure you have Python installed on your system.
3. Navigate to the project directory.

## Usage
1. Open a terminal or command prompt.
2. Navigate to the directory where the game is located.
3. Run the following command to start the game:
   ```
   python war_cards_game.py
   ```
4. Follow the on-screen instructions to play the game.
5. The game will display the number of rounds played and the player who wins the game.

## Game Rules
- The game is played with a standard deck of 52 playing cards.
- Players draw a card from their decks in each round.
- The player with the higher card rank wins the round.
- Card ranks follow the standard order: 2 < 3 < 4 < ... < 10 < J < Q < K < A.
- In case of a tie (both players draw cards of equal rank), a "war" occurs.
- During a war, each player places six cards face down, and then draws a seventh card.
- The player with the higher rank on their seventh card wins the war and all
the cards in play.
- If there's another tie during a war, the process is repeated until a player wins.
- The game continues until all the cards are exhausted from one player's deck.
- The player with all the cards is declared the overall winner.


