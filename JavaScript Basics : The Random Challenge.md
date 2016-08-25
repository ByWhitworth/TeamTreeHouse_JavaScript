# JavaScript Basics : The Random Challenge

Collect a number from the user and a pick a random number from 1 - that users number. 

```
var userNumber = prompt('Pick a number');

alert('you picked ' + parseInt(userNumber));

var randomNumber = Math.floor(Math.random() * parseInt(userNumber)) + 1;
document.write(randomNumber);
```

Treehouse Solution: 

```
var input1 = prompt('Please type a starting number');
var input = prompt('Please type a number');
var topNumber = parseInt(input);
var randomNumber = Math.floor(Math.random() * (topNumber - bottomNumber + 1 )) + bottomNumber;
var message = "<p>" + randomNumber + " is a number between " + bottomNumber + " and " + topNumber + ".</p>";
document.write(message);
```

