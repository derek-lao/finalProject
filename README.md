# Hangman

## Members
- Kenneth Chin  
- Minuk Kim  
- Derek Lao  

## Description of Project  
We are making our attempt of creating the popular child's game hangman.
The objective of the game is to guess a word that someone else chooses. The
guessers guess a letter each turn. If the letter is part of the word, the
position the letter is in the word is shown, else a part of a drawing of a stick 
figure is drawn. If the guesser can get the word before the drawing is done, they win.

## Description of User Interface:  
- There is an option to choose to be the guesser or chooser.
- For guessers - there will be an option to guess a letter or word.
- For chooser - they will be able to input their word


## Technical Design:
- Networking: Allow two (or more tbd) players to play against each other.
- Signals: To relay the what letters the guessers guess and what the word is.
- Share Memory/ Semaphores: Only one guesser can go at a time.
- Allocated Memory: Store the words and guess letters.

## Timeline:

