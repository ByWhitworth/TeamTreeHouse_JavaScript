# JavaScript Basics: Combining Multiple Tests into a Single Condition

###'And' Operator 

`&&` - `(20 < age && age < 30)`

Both these values work together to create a Boolean value. 

| value of age | 20 < age | age < 30 | results of && |
| :-: | :-: | :-: | :-: |
| 25 | true | true | true |
| 35 | true | false | false |
| 10 | false | true | false |
| ‘string' | false | false | false |


###'Or' Operator 

`||` - `(agree === 'yes' || agree === 'y')`

If _one_ of the statements are true, then the string is set as `true` 


| value of agree | agree === ‘yes' | agree === ‘y' | Results  |
| :-: | :-: | :-: | :-: |
| ‘yes' | true | false | true |
| ‘y' | false | true | True |
| ’n' | false | false | false |


####Tip
> You need to have a full condition for these operators to work. 

```
if ( agree === 'yes' || 'y') {

}
```
This is invalid


```
if (agree === 'yes' || agree === 'y'){

}
```
This is a valid condition 


You can more than two 'and' and 'or' operators in your condition. 

```
(score === 0 && ships <= 0 $$$ time === 0 ) 
```
Note: that if any of the operators are `false` the whole condition is `false`

```
(password === "" || email === "" || phoneNumber ==="")
```
Note: if any of the operators are `true` the whole condition is `true`



