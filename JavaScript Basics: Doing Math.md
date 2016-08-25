# JavaScript Basics: Doing Math

JavaScript allows Add, Subtract, Multiple, and divide numbers. 

```
2+7 //Add
2-3 //Subtract
6/3 // Multiple
10*9 // Divide 
```

```
var score = 0;
score = score + 100;
```
The stuff on the right go into the stuff on the left. 

###Mathematical Shorthands.
`+= 10` to add 10 to the contents of the variable


| Changing the value of a variable | Shorthand Version  |
| :-: | :-: |
| `score = score + 10;` | `score += 10;` |
| `score = score - 20;` | `score -=20;`  |
| `score = score * 5;` | `score *=5;` |
| `score = score / 2;` | `score /= 2;` |
 

---
###Example Exercise 
####Displaying the number of seconds in a one day
```
var secondsPerMin = 60;
var minPerHour = 60;
var hoursPerDay = 24;
var daysPerWeek = 7;
var weeksPerYear = 52;
var secondsPerDay = secondsPerMin * minPerHour * hoursPerDay;
Document.write('There are '+ secondsPerDay + ' seconds in a day');
```

Result: `There are 86400 seconds in a day`


####Displaying the amount of seconds alive of a person
```
var secondsPerMin = 60;
var minPerHour = 60;
var hoursPerDay = 24;
var daysPerWeek = 7;
var weeksPerYear = 52;
var secondsPerDay = secondsPerMin * minPerHour * hoursPerDay;
document.write('There are '+ secondsPerDay + ' seconds in a day');
var yearsAlive = 31;

var secondsAlive = secondsPerDay * 365 * yearsAlive;
document.write("I've been alive for " + secondsAlive +" seconds");
```
Result: `There are 86400 seconds in a dayI've been alive for 977616000 seconds`

