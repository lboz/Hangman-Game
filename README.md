# Hangman-Game

Python variation of the classic wordgame Hangman

The computer selects a word at random from the list of available words 
(words.txt). 

The game is interactive; the flow of the game goes as follows:
  - At the start of the game, let the user know how many letters the computer's
    word contains.
  - Ask the user to supply one guess (i.e. letter) per round.
  - The user should receive feedback immediately after each guess about whether
    their guess appears in the computer's word.
  - After each round, the computer displays to the user the partially guessed
    word so far, as well as the position of the letters that the user has not 
    yet guessed.
    
Some additional rules of the game:
-   A user is allowed 8 guesses. Make sure to remind the user of how many
    guesses s/he has left after each round. Assume that players will only ever
    submit one character at a time (A-Z).
-   A user loses a guess only when s/he guesses incorrectly.
-   If the user guesses the same letter twice, do not take away a guess - 
    instead, print a message letting them know they've already guessed that 
    letter and ask them to try again.
-   The game ends when the user constructs the full word or runs out of 
    guesses. If the player runs out of guesses (s/he "loses"), reveal the word
    to the user when the game ends.
