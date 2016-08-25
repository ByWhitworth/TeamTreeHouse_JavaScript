# The Story Making Game

1. Create a variable and capture input.
2. Create a separate variable for each piece of input.
3. Add an alert to tell the visitor that they're finished.
4. Combine the input with other strings to create a message.
5. Print the story to the browser window


###Prompting 
```
var verb = prompt("Input a Verb");
```
###Alerting 
```
alert("You have completed inputing data");
```

###Combine 
```
var message = verb + verb2;
```

###Print to Window
```
document.write(message);
```


---
###Create a story-telling program: (Prompt)

1. Use the prompt() command several times to collect different types of words -- nouns, verbs, adjectives.
2. Store the result of each prompt() command in a different variable.
3. Combine the variables with other strings to create one or more non-sensical statements.
4. Print the resulting story to the browser using the document.write() command.

```
//Prompting visitor for variables. 
var firstNoun = prompt("Input a Noun");
var secondNoun = prompt("Input another Noun");
var firstVerb = prompt("Input a verb");
var secondVerb = prompt("Input another verb");
var firstAdjective = prompt("Input an Adjective");
var secondAdjective = prompt("Input another Adjective");

//1st part for Displaying visitor selections.
var nouns = firstNoun +", "+ secondNoun;
var verbs = firstVerb +", "+ secondVerb;
var adjectives = firstAdjective +", "+ secondAdjective;

//2nd part for displaying visitor selections.
document.write('<h1>Visitor Selections</h1>');
document.write("Selected Nouns: "+nouns+</br>);
document.write("Selected Verbs: "+verbs+</br>);
document.write("Selected Adjectives: "+adjectives+</br>);
```

##Solution 

```
var adjective = prompt('Please type an adjective');
var sentence = "<h2>There once was a " + adjective;
var verb = prompt('Please type a verb');
var noun = prompt('Please type a noun');
alert('All done. Ready for the message?');
sentence += ' programmer who wanted to use JavaScript to ' + verb;
sentence += ' the ' + noun + '.</h2>';
document.write(sentence);
```
JavaScript

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <link rel="stylesheet" href="css/main.css">
  <title>The Story Maker</title>
 </head>
<body>
  <div class="container">
  <h1>The Story Maker</h1>
  <script src="story.js"></script>
  </div>
</body>
</html>
```
HTML

