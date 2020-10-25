# jquery-wordsearch-game
 A word search game developed as a jQuery widget


This jQuery widget creates a grid of letters with words from the wordlist.
These words are randomly placed in the following directions
1. Horizontal
1. Vertical 
1. Left-Diagonal
1. Right-Diagonal

In addition, the letters are placed in forward or reverse order, randomly.
Provision is made to overlap words

The User is expected to click on a letter and drag to the last letter of the word. If the selected letters form a word that is in the word list the UI will indicate that by crossing it out from the wordlist

If the user cannot find a word, she can click on that word in the Wordlist. The UI will highlight that word in the grid and cross it out.

Usage:
```
$("#aDiv").wordsearchwidget({"wordlist" : words,"gridsize" : 12});

parameters:
gridsize - Size of grid to generate (this will be a square)
wordlist - Comma separated list of words to place on the grid
```

Original project by Ryan Fernandes
Forked from https://code.google.com/archive/p/jquery-wordsearch-game/
