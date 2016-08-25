# JavaScript Basics:  Boolean Values


| Strings | number | Booleans |
| :-: | :-: | :-: |
| ‘Hello' | 1 | true |
| '' | 0 | false |
| ‘Welcome to Treehouse | -485.88 |  |
| ‘7000' | 7e4 |  |

```
var correctGuess = false;
var randomNumber = Math.floor(Math.random() * 6 ) + 1;
var guess = prompt('I am thinking of a number between 1 and 6. What is it?');
if (parseInt(guess) === randomNumber ) {
  document.write('<p>You guessed the number!</p>');
  correctGuess= true;
} 
if (correctGuess ) {
  document.write('<p> You guessed the number!</p>');
 } else {
  document.write('<p>Sorry. The number was ' + randomNumber + '.</p>');
 }

```
We rewrote this program so it can have more flexible outcomes in future programs. 

