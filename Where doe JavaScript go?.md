# Where doe JavaScript go?

how javascript works in a browsers. 

- HTML - Framework
- CSS - Styling 
- JavaScript - Interaction


Executing the program is a common phrase that programers use. 

into a file - scripts.js
inline - at the very bottom of the HTML file


Link a JavaScript file to a web page using the `<script>` tag and the src property.

```
<script src="scripts.js"></script>
```


Insert JavaScript directly into a web page inside `<script>` tags:


```
<script>
alert("Hello there.");
</script>
```

Never link to a file and include JavaScript inside the same `<script>` tag.


```
<script src="file.js">
   alert("Hello there.");
</script>
```


