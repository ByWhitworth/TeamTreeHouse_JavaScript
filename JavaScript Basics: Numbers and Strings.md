# JavaScript Basics: Numbers and Strings

Learn how to convert strings to numbers.

```
var HTMLBadges = prompt('How many HTML bages do you have?');
var CSSBadges = prompt('How many CSS badges do you have?');
var totalBadges = HTMLBadges + CSSBadges;
alert ('Wow! You have ' + totalBadges + ' badges!');
```
Input: `10 and 5` 
Result: `Wow! You have 105 badges!`
The plus symbol combines the string values together.


How to convert Number Strings to real numbers. Good example of this is when you see any type of form input. These inputs are first inputted as strings and not a number value. 

####Converting string values to real numbers.
```
var HTMLBadges = prompt('How many HTML bages do you have?');
var CSSBadges = prompt('How many CSS badges do you have?');
var totalBadges = parseInt(HTMLBadges) + parseInt(CSSBadges);
alert ('Wow! You have ' + totalBadges + ' badges!');
```
Result: `Wow! You have 15 badges!`


#####Converting a string value to a floating number;
`parseFloat('3.14');`
Result: `3.14`

`parseFloat('1.89 light years away');`
Result: `1.89`

`parseInt('That is so 2004');`
Result: `NaN` (Not a Number)

####Examples of Parse Command

| Parse Command | Return Value |
| :-: | :-: |
| `parseInt(’11’);` | `11`|
| `parseInt(‘135px’);` | `135` |
| `parseInt(‘202.99’)` | `202` |
| `parseInt(‘Plan 9’)` | `NaN` |
| `parseFloat(’32.50’)` | `32.50` |
| `parseFloat(‘273.15’)` | `-273.15` |
| `parseFloat(‘Absolute zero is -273.15’)` | `NaN` |


###Tips
>you are also able to run JS code within the Console.





