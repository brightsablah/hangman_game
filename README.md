# hangman_game
- generate a word 
- show as many blanks as the number of characters in the word 
- user inputs a guess letter 
- check if guessed letter is part of the secret word 
- if not part of it, 
    - loose a life 
    - check if out of lives. 
        - if out of lives, you lose. 
        - else, display prompt to guess a letter 

- if part of it, 
    - replace space with the guessed letter.
    - then check if all blanks are filled
        - if yes, you win
        - if no, display promt to guess letter again
- quit game

* additional information
  - after every loss of life, display athe hangman progrssively being drawn to a perfect picture
  - display game won or game over depending on the performance of the player
