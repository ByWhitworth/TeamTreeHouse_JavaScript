# JavaScript Basics: Getting Information From a Function 

Functions don't just run JavaScript statements. They can also return values that you can use elsewhere in a program. 


Returning a value within a function you need to do the following:

```
function goToCoffeeShop() {
	return "Espresso is on its way.";
}

alert( goToCoffeeShop() );

```

You can **return** the value in many different ways.
`console.log( goToCoffeeShop() );`
`document.write( goToCoffeeShop() );`
`var coffeeStatus = goToCoffeeShop();`

###Example
```
function getRandomNumber() {
  var randomNumber = Math.floor( Math.random() * 6 ) + 1; 
  return randomNumber;
}

alert( getRandomNumber() );
console.log ( getRandomNumber() ); 
var dieRoll = getRandomNumber();

```


###Example Two

```
function isEmailEmpty() {
	//Checks the Element Email
	var field = document.getElementById('email');
	//Looks at var field to see if there is a empty string. If so, it will return a value of 'true'
	if (field.value ==='') {
		return true;
	} else {
		return false;
	}
}

var fieldTest = is EmailEmpty();
If (fieldTest === true) {
	alert('Please provide your email address');
}
```


####Tip
> When calling a `return` value it will exit out of the code block 
> 
> ```
> function noAlert() {
>   	return 5;
> 		alert("This won't appear");
> }
> 
> noAlert();
> alert("This will appear!");
> ```


####Tip
>a `return` statement can only `return` one value.

