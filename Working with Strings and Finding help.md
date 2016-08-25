# Working with Strings and Finding help
###String Properties and Methods
```
var str = '9 letters';
alert( str.length ); 
// opens an alert dialog with the number 9
```
.length returns the number of characters inside a string


```
var str = 'upper';
alert( str.toUpperCase() ); 
// opens an alert dialog with the string 'UPPER'
```
.toUpperCase() returns a copy of a string with all uppercase letters


```
var str = 'LOWER';
alert( str.toLowerCase() ); 
// opens an alert dialog with the string 'lower'
```
.toLowerCase() returns a copy of a string with all lowercase letters

---
####Great reference 
[Mozilla Developer Network (MDN) ](https://developer.mozilla.org/en-US/)

---

###Examples 
```
var passphrase = "Open Sesame";
console.log(passphrase.length);
```
This will display the length of "Open Sesame" within the console of the broswer. 

`message.length` = 	object.property 

`"There are 38 characters in this string".length ` = 38

A method is something you can do with the object.


```
var passphrase = "Open Sesame";
console.log(passphrase.length);
console.log(passphrase.toLowerCase());
```

```
11
open sesame
```

the `toLowerCase()` doesn't modify the actual string, it only changes how it's displayed. 


```
var passphrase = "Open Sesame";
console.log(passphrase.length);
console.log(passphrase.toLowerCase());
console.log(passphrase);
console.log(passphrase.toUpperCase());
```

```
11
open sesame
Open Sesame
OPEN SESAME
```


##Shout App Code
```
var stringToShout = prompt("What should I shout?");
var shout = stringToShould.toUpperCase();
shout + = "!!!";
alert(shout);
```

input
`hi there`

output
`HI THERE!!!`


##Recap 
####Objects
-  a string, the document, the browser's console
-  object have properties, such as length of a string
-  objects have methods, which are actions the object can perform

the `.toUpperCase();` method



##Challenge 
```
var id = "23188xtr";
var lastName = "Smith";

var userName = id.toUpperCase()+"#"+lastName.toUpperCase();
```

output
` 23188XTR#SMITH`


