# Introduction to Debugging

## Introduction
This repository contains the starter files for the 'Introduction to Debugging' exercise.

As part of this exercise you will debug a simple, browser-based 'card matching' game. The HTML, CSS, and JavaScript code that makes up the game has been provided. However, it's a bit... buggy.

## Rules
The game is intended to work as follows:
- The user is presented with a selection of 3 pairs of cards, for a total of 6 cards.
- Each pair of cards features a matching symbol.
- All of the cards are displayed 'face down', meaning that the symbols are not visible.
- The user will select two cards, one at a time.
- When a card is selected it will be flipped 'face up', meaning that the symbol will be displayed.
- If the symbols match, the cards will remain face up.
- If the symbols do not match, the cards will be flipped face down.
- This continues until the user has matched all 6 cards.
- When all 6 cards have been matched, a message is displayed and the game ends.

## Bonus Features
- Users are able to change the colour of the cards by adding any one of the following values to the end of the URL:
- #green
- #red
- #orange

## Defects
Our users have reported the following problems:
- I am able to select more than 2 cards.
- Cards do not seem to be compared/matched correctly.
- The cards are never flipped face down, regardless of whether or not they match.
- The game does not end, even after all the cards have been matched.

Additionally, adding the #green, #red, or #orange values to the URL and then refreshing the page _does not_ update the colour of the cards.

## Approach
- Debug and fix each defect (in order if possible). Introduce each fix as a separate commit.
- Focus on debugging the 'rules' (part 1)  before moving on to the 'bonus features' (part 2).

Please review the accompanying class materials for additional details.

## Attribution
- Card background by [Gordon Johnson](https://pixabay.com/users/gdj-1086657/), provided by [Pixabay](https://pixabay.com/).
