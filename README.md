## Computational Social Science - Final Project - Summer 2026
This is Sylvia Zuniga's final project where she tries to find what is the a good starting word for Wordle.

### What is Wordle?
According to the Wikipedea: 

"Wordle is a web-based word game... In the game, players have six attempts to guess a five-letter word, receiving feedback through colored tiles that indicate correct letters and their placement. A single puzzle is released daily, with all players attempting to solve the same word."


### What makes a starting word GOOD?
The goal is not for the starting word to be the BEST. 

Fefine BEST: a starting word that gets the target word on the first try. 

However, that starting word cannot be the best again the next day since Wordle changes the word everyday. Therefore, instead of looking for the BEST starting word, we are seeing if the choosen starting word is  a *good* starting word.

Define a good starting word: a word that shares one or more letters (either green or yellow) with the target word. The word remains good if it stays consistent, as in you can use the word for the next day's Wordle and it still shares letters with the target word.

### Data Used
The data used was both data collected by Sylvia(shown at the beginning of the notebook) and from Sean Patlan. If you'd like to see his process it is on [GitHub](https://github.com/seanpatlan/wordle-words/blob/main/word-bank.csv)!
Sean made two CSV files: 
- **valid-words.csv**: a list of all words that Wordle considers a valid guess (12,972 words)
- **word-bank.csv**: the list of words that Wordle selects the daily word from (2,315 words)
