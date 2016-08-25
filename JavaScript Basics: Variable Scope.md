# JavaScript Basics: Variable Scope

How JavaScripts protects variables from writing over each other. 


```
function greeting () {
	person = 'Lilah';
	alert(person);
}

var person = 'George';
greeting();
alert(person);
greeting();

```

Always use the `var` keyword when creating a variable inside a function. If you don't your function is reaching out to the global scope and might override another variable with the same name. 




