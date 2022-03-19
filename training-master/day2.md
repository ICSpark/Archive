# Day 2

## Objective
- Review HTML, CSS, CSS flexbox
- From Codepen to Atom
- Linking files and rendering on Google Chrome
- Chrome Inspector
- JS variables, if statement, arrays, objects
- DOM and DOM methods

## Resources
- Install Atom: https://atom.io/
- Install Emmet for Atom: https://atom.io/packages/emmet
- JSBin: https://jsbin.com/
- DOM reference: https://www.w3schools.com/js/js_htmldom.asp

## Projects
- DOM: https://github.com/junior-devleague/my-pokedex

## Table of Contents
1. **From Codepen to Atom**
  * Install Atom and the Emmet package
  * Initialize files in Atom
  * Linking HTML, CSS, JS files
  * Rendering on Google Chrome
2. **Chrome DevTools**
3. **Introduction to JS**
  * Variables
  * Data types
4. **DOM**

## From Codepen to Atom

### Install Atom and the Emmet package.
1. Go to https://atom.io/ to install Atom and follow these instructions (https://atom.io/packages/emmet) to install the Emmet package. Emmet provides you with useful shortcuts and tools.

### Initialize files in Atom
1. Create a folder ```practice``` and drag this folder to the left "Project" panel. In Atom, create the following 3 files by clicking on File -> New File.
  * index.html
  * styles.css
  * app.js
2. In your index.html file, type in ```!``` and press tab. The following should appear.
  * ```<!DOCTYPE html>```: defines this document to be HTML5
  * ```<html>```: root element of this HTML page
  * ```<head>```: element contains metainformation about this document
  * ```<title>```: element specifies title of this document  
  * ```<body>```: contains visible page content

``` html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>

</body>
</html>
```
3. All of the HTML code we have been writing in Codepen should be placed within the ```<body></body>``` tags.

### Linking HTML, CSS, JS files
1. Link your CSS file by creating a ```<link>``` element before the ```<title>``` element as follows. Within the ```href``` attribute, type in the path to your CSS file.

``` html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="styles.css">
  <title>Document</title>
</head>
<body>

</body>
</html>
```

2. Link your JS file by creating a ```<script>``` element before the ```</body>``` tag as follows. Within the ```src``` attribute, type in the path to your JS file.

``` HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="styles.css">
  <title>Document</title>
</head>
<body>

<script src="app.js"></script>
</body>
</html>
```

### Rendering on Google Chrome
1. Create a ```h1``` element within the ```body``` element that says "Hello World!".
2. Open a new tab on Google Chrome.
3. Drag the tab of your file into the search bar at the top of the page and press Enter. You should see "Hello World" displayed on a blank screen.

## Chrome DevTools
1. Google Chrome offers web developer tools to help inspect various aspects of a web page. Right click anywhere on the "Hello World" web page and select ```Inspect```.
![Google Chrome Inspector](https://github.com/ICSpark/training/blob/master/images/day2_inspector.png)

2. Click on the top left square with the arrow icon. This now allows you to hover over elements on the web page and inspect them more carefully.
![Google Chrome Inspector selecting elements](https://github.com/ICSpark/training/blob/master/images/day2_inspector_detail.png)

3. Double click on the "Hello World" text in the Elements tab of the Inspector and type in new text. This will not change the code in your actual file. This function allows you to test how changes would like on a webpage very quickly.

4. In the ```Styles``` tab of the Inspector, double click within the ```element.style {}``` to see how new styles would look like.

5. The ```Console``` tab is where you can see errors and anything that you log to it with ```console.log```. You can click on the underlined text on the right to see more details.

![Google Chrome Inspector console](https://github.com/ICSpark/training/blob/master/images/day2_inspector_console.png)

## Introduction to JS

### Variables
1. Variables are containers for storing data. Create variables as follows. Variables start with the keyword ```var```, followed by a unique identifier, the assignment operator ```=```, then data and a semicolon.  
``` js
var name = "Sarah" // String in single or double quotes.
var age = 23; // Numbers with or without decimal points.
var x = 5 + 2 + 3; // Adding numberes  
var y = "John" + " " + "Doe"; // Adding strings will concatenate them
```
2. More information can be found at https://www.w3schools.com/js/js_variables.asp.

### Data Types
1. JS variables can hold many different data types.

``` JS
var name = "Jen"; // String
var age = 14; // Number
var hasPet = true; // Boolean
var classmates = ["John", "Damien", "Shirley"]; // Arrays associate data with a position
var bestFriend = { // Objects are containers of variables
  firstName: "Lori",
  lastName: "Doe",
  age: 14
}
```

2. More information can be found at https://www.w3schools.com/js/js_datatypes.asp.

## Document Object Model (DOM)
1. DOM stands for **D** ocument **O** bject **M** odel. When loading a web page, the browser creates a DOM of the page. HTML DOM is a tree of objects. With DOM, JS can change aspects of HTML and CSS and react to HTML events.
2. The DOM provides useful methods, or actions, to perform on HTML elements. Below are a few of the common ones.

``` javascript
var title = document.getElementById('title1'); // Stores the element with id of "button" into our variable.

title.innerHTML = "Good Morning!"; // Changes the text within the title element to "Good Morning!".
```
3. Try out this project to practice DOM methods: https://github.com/junior-devleague/my-pokedex
