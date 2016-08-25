# What are loops

In programming, a loop is a way to repeat the same actions a certain number of times, or until a certain condition is true. 


```
while () {

}

```

```
function randomNumber(upper) {
	return Math.floor(Math.random() * upper ) + 1;
}

var counter = 0;
while (counter < 10) {
	var randNum = randomNumber(9);
	document.write(randNum + ' ');
	counter += 1;
}
```




