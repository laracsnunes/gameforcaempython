
🎮 Hangman's Noose
_____________________________________________________________________________________________________________________________________

https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white 

A game without an interface developed in Python, with the aim of applying some of the techniques learned with this language.
This game is based on the following link: https://thewordsearch.com/hangman/#google_vignette 

🎯 Step by Step 
_____________________________________________________________________________________________________________________________________

✦Define the list of possible words 
✦Choose a random word from the list 
✦Create an empty list to store the guessed letters 
✦Set the maximum number of attempts allowed 
✦While the number of attempts allowed 
1)As long as the number of attempts has not reached the maximum limit: 
2)Show the word as a series of underscores, with the guessed letters filled in the 3)correct spaces 
4)Ask the player to guess a letter 
5)Check if the letter guesses the word 
6)If the guessed letter is in the word, add the letter to the list of guessed letters and update the word display 
7)If the guessed letter is not in the word, reduce the number of remaining attempts to display the message "Incorrect letter. Attempts remaining: [number of attempts remaining]"
8)Check that all the letters in the word have been guessed 
9)If all the letters have been guessed, display the message "You win!" 
10)If the number of attempts left reaches zero, display the message "You lost. The word was [chosen word] and end the game."



