# JavaScript Basics: Improving the Random Number Guessing Game.

```
var correctGuess = false;
var randomNumber = Math.floor(Math.random() * 6 ) + 1;
var guess = prompt('I am thinking of a number between 1 and 6. What is it?');
if (parseInt(guess) === randomNumber ) {
  correctGuess = true;
} else if ( parseInt(guess) < randomNumber ) {
   var guessMore = prompt('Try Again. The number I am thinking of is more than ' + guess);
    if (parseInt(guessMore) === randomNumber ) {
        correctGuess = true;
    }
} else if ( parseInt(guess) > randomNumber ) {
   var guessLess = prompt('Try again. The number I am thinking of is less than ' + guess);
}
if ( correctGuess ) {
    document.write('<p>You guessed the number!</p>');
} else {
    document.write('<p>Sorry. The number was ' + randomNumber + '.</p>');
}

``` 

Nested `if` statements is what is making the `correctGuess` statement true

