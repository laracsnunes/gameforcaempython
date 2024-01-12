<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h1 align="left">🎮 Hangman's Noose</h1>
__________________________________________________________________________________________________________

<a href="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
</a>

<p>A game without an interface developed in Python, with the aim of applying some of the techniques learned with this language.</p>
<p>This game is based on the following link:https://thewordsearch.com/hangman/#google_vignetteL</p>

<h1 align="left">🎯 Step by Step</h1> 
___________________________________________________________________________________________________________
 <ul>
 <li>Define the list of possible words</li>
 <li>Choose a random word from the list</li> 
 <li>Create an empty list to store the guessed letters</li>
 <li>Set the maximum number of attempts allowed</li>
  </ul>
  <ol>
<li>While the number of attempts allowed</li>
<li>As long as the number of attempts has not reached the maximum limit:</li>
<li>Show the word as a series of underscores, with the guessed letters filled in the 3)correct spaces</li>
<li>Ask the player to guess a letter</li> 
<li>Check if the letter guesses the word</li> 
<li>If the guessed letter is in the word, add the letter to the list of guessed letters and update the word display</li> 
<li>If the guessed letter is not in the word, reduce the number of remaining attempts to display the message "Incorrect letter. Attempts remaining: [number of attempts remaining]"</li>
<li>Check that all the letters in the word have been guessed</li> 
<li>If all the letters have been guessed, display the message "You win!"</li> 
<li>If the number of attempts left reaches zero, display the message "You lost. The word was [chosen word] and end the game."</li>
  </ol>
 </body>
</html>

