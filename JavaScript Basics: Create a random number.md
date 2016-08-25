# JavaScript Basics: Create a random number


the `Math.random()` can do a lot
* liven up your home page by randomly selecting a photo
* randomly place enemy spaceships on the screen
* randomly select a question as part of a quiz application

[Math.random( ) on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)


| `Math.floor()` |  | `Math.ceil()` |  |
| :-: | :-: | :-: | :-: |
| `Math.floor(1.2)` | 1 | `Math.ceil(1.2)` | 2 |
| `Math.floor(0.0012)` | 0 | `Math.ceil(0.0012)` | 1 |
| `Math.floor(5.028)` | 5 | `Math.ceil(5.028)` | 6 |
| `Math.floor(2)` | 2 | `Math.ceil(2)` | 2 |
| `Math.floor(0)` | 0 | `Math.ceil(0)` | 0 |

`Math.floor()` rounds the value down
*like towards the floor

`Math.ceil()` round the value up
*towards the ceiling

If the value is already a whole number / int. then it will remain that whole number. 


`Math.random() * 6` 
Output: `5.00134532552`

If you use `Math.random()` in conjunction with `Math.floor()` it will round down to a whole number.  

`Math.floor( Math.random() * 6 )`
Output: `5`

`Math.floor (Math.random() * 6) + 1`
This will generate a number between one and 6


###App.js 
```
var dieRoll = Math.floor(Math.random()*6) + 1;
alert('You rolled a '+ dieRoll);
```
Random numbers between 1 - 6 which will popup an alert.

