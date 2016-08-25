# JavaScript Basics: Build a Random Number Guessing Game

```
var randomNumber = Math.floor(Math.random() * 6 ) + 1;
var guessedNumber = prompt('Pick a number between 1 - 6');
var number = parseInt(guessedNumber);
if (number === randomNumber){
  alert('Your correct!')
} else {
  alert('That was incorrect, the number is ' + randomNumber +' !')  
}
```


Treehouse Solution: 

```
var randomNumber = Math.floor(Math.random() * 6 ) + 1 ; 
var guess = prompt('I am thinking of a number between 1 and 6. What is it?');
if (parseInt(guess) === randomNumber ) {
	document.write('<p> You guessed the number! </p>');
	} else {
	document.write('<p> Sorry. The number was ' + randomNumber + '</p>');
	}
```
Just to reference between the code they provided and what I wrote. You can eliminate the `number` variable so you don't have to do the `parseInt()` separately. So you can ideally just do the `parseInt()` within the `if` statement.

