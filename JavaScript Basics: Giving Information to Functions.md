# JavaScript Basics: Giving Information to Functions
Modify how functions work by sending information to functions when you call them. 

```
function goToCoffeeShop(drink) {
	alert( drink + 'is on the way!');
}


goToCoffeeShop('Espresso');


```

###Die Rolling Challenge update
```
function getRandomNumber( upper ) {
  var randomNumber = Math.floor( Math.random() * upper ) + 1; 
  return randomNumber;
}

console.log( getRandomNumber (6));
console.log( getRandomNumber (100));
console.log( getRandomNumber (1000));
console.log( getRandomNumber (10000));

```


###Multiple Arguments 
```
function goToCoffeeShop (drink, pastry) {
	alert( drink + "and " + pastry + "are on the way!");
	}

goToCoffeeShop("Expresso", "crosissant");
	
```

```
function getArea(width, length, unit) {
  var area = width * length;
  return area + " " + unit);
}

console.log( getArea(10,20, 'sq ft'));
```


