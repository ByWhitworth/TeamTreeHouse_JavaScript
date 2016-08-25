# JavaScript Basics: Introducing Functions

Start by _declaring_ a function

```
function goToCoffeeShop() {

}

```

####Function Names
* Can only be made up of letters, numbers, the _, and $ characters
* They can't start with a number
* They can't include any spaces or other punctuation

####Tip
>if you see `()` after the name, then you know you are dealing with a function.


```
function goToCofeeShop() {
	alert('Espresso is on the way!');
	}
	
```
To call the function you just insert this: `goToCoffeeShop();` and it will run that code block. 


####Tip
>It is common to write the function at the top of the .js file
>The function is simply just memorized 


```
function alertRandom(){
  var randomNumber = Math.floor( Math.random() * 6 ) + 1; 
  alert(randomNumber);
}


alertRandom();
```



####Teacher's Notes
The basic structure of a function

```
function myFunction() {
  // do a bunch of stuff here
}
```
Calling a function

```
myFunction();
```

A function expression

```
var myFunction =  function () {
  // do stuff here
};	
```

