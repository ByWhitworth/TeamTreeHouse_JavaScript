# JavaScript Basics: Random Number Challenge

Random number between two numbers. 
`Math.floor(Math.random() * (6 - 1 + 1)) + 1; `


My Solution

```
function getRandomNumber( upper, lower ) {
			var randomNumber = Math.floor( Math.random() * upper - lower + lower ) +1; 
			return randomNumber;
		
		alert(getRandomNumber(10, 1));

		
```

TeamTreeHouse Solution

```
function getRandomNumber ( lower, upper ) {
	return Math.Floor(Math.random() * (upper - lower + 1)) + lower;
}

console.log ( getRandomNumber (1,6));
	
console.log ( getRandomNumber (10,60));

console.log ( getRandomNumber (12,61));

```

