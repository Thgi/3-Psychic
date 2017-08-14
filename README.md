# 3-Psychic

Psychic website is a game that has the user guess what letter the computer has selected. The user has 9 attempts at guessing the right letter. If after 9 attempts the user has not guessed it correctly, then the user loses the game and the losses counter adds up. If the user guess the letter correctly, they win the game and the wins column increases. The game resets and the user plays again.

The website is also the the first time I have used embedded javascript within an HTML.

In order to have Javascript run in your HTML, you need to include the following:

<script type="text/javascript">


The Javascript file runs the logic for playing the psychic game.

It heavily uses arrays to store the 26 letters of the alphabet, and to store the different guesses the user makes.

I also learned how to use the function document.onkeyup where this allows a function to run once a key is pressed. This is where I have the function check the letter each time if it matches the computer guess.
