# Welcome to Working with Javascript

Javascript is another language like HTML and CSS. In fact it is similar in that it is also a plain text language. Unlike HTML and CSS, Javascript (JS) is used to create interactivity on the webpage. This simply means that you as the user can interact with the webpage. JS changes how the page behaves. 

Here is an example of a scipt from the Jon Duckett "Javascript & JQuery" book:

    ```var today = new Date();
```var hourNow = today.getHours();
var greeting;```

```if (hourNow > 18) {
    greeting = 'Good evening!';
} else if (hourNow > 12) {
    greeting = 'Good afternoon!';
} else if (hourNow > 0) {
    greeting = 'Good morning!';
} else {
    greeting = 'Welcome!';
}```

```document.write('<h3>' + greeting + '</h3>');```

## Javascript Link

When adding JS files to your HTML page a link must be written in the HTML. This lets the browser know to run the script located in a stored location. This is done by adding a script element in the HTML file.

**Example:** 

 ```<script src="js/add-content.js"></script>```
 
If problems are created when adding the script file it may be necessary to put the script file line down lower in the HTML file structure.