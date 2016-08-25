# JavaScript Basics: The Conditional Challenege

Ask at least five questions

Keep track of the number of questions the user answered correctly

Provide a final message after the quiz letting the user know the number of questions he or she got right.

Rank the player. If the player answered all five correctly, give that player the gold crown: 3-4 is a silver crown; 1-2 correct answers is a bronze crown and 0 correct is no crown at all.


```
//quiz begins, no answers correct
var correct = 0;

//ask questions
var answers1 = prompt("Name a programming language that's also a gem"); 
if (answers1.toUpperCase() === 'RUBY'){
	correct += 1;
}
var answers2 = prompt("Name a programing language that's also a snake"); 
if (answers2.toUpperCase() === 'PYHON'){
	correct += 1;
}
var answers3= prompt("What language do you use to style web pages?");
if (answers3.toUpperCase() === 'CSS'){
	correct += 1;
}
var answers4= prompt("What language do you use to build the structure of web pages");
if (answers3.toUpperCase() === 'HTML'){
	correct += 1;
}
var answers3= prompt("What language do you use toto add interactivity to a web page?");
if (answers3.toUpperCase() === 'JAVASCRIPT'){
	correct += 1;
}

// output results
document.write("<p>You got " + correct + " out of 5 questions correct. <p>");

// output rank
if (correct === 5) {
	document.write("<p><strong> You earned a gold crown! </strong></p>");
} else if ( correct >= 3 ) {
	document.write ("<p><strong>You earned a silver crown. </strong></p>");
} else if (correct >= 1 ) {
	document.write("<p><strong>You earned a bronze crown.</strong></p>");
} else {
	document.write("<p><strong>No crown for you. You need to study.</strong></p>;")
} 

```


JavaScript Functions can greatly help and eliminate code. 
	

###Challenge 
Before

```
var money = 9;
var today = 'Friday'

if ( money >= 100 || today === 'Friday' ) {
  alert("Time to go to the theater");    
} else if ( money >= 50 || today === 'Friday' ) {
  alert("Time for a movie and dinner");    
} else if ( money > 10 || today === 'Friday' ) {
  alert("Time for a movie");   
} else if ( today !== 'Friday' ) {
  alert("It's Friday, but I don't have enough money to go out");   
} else {
  alert("This isn't Friday. I need to stay home.");
}

```
Output

```
Time to go to the theater
```
####Fix

```

var money = 2;
var today = 'Friday';

if ( money >= 100 && today === 'Friday' ) {
	alert("Time to go to the theater");    
} else if ( money >= 50 && today === 'Friday' ) {
	alert("Time for a movie and dinner");    
} else if ( money > 10 && today === 'Friday' ) {
	alert("Time for a movie");   
} else if ( today === 'Friday') {
	alert("It's Friday, but I don't have enough money to go out");   
} else {
	alert("This isn't Friday. I need to stay home.");
}
```
Output

```
It's Friday, but I don't have enough money to go out"
```


