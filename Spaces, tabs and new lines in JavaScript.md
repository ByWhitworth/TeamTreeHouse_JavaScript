# Spaces, tabs and new lines in JavaScript

Like HTML and CSS, JavAScript doesn't care about space

```
var dayInWeek= 7;

var dayInWeek = 7 ;

Var 

		dayInWeek
		
		=
		
		7
			;
```

These all work, but the rule of thumb is just to use space to make the code easier to read. Nothing to distracting. 


####When it doesn't work 
``` 
vardayInWeek = 7 ;
```
*the browser's JavaScript interpreter can not determine there is a variable.*

```
var day In Week = 7 ;
```
*this will result in a syntax error*

