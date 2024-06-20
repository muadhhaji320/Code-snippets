# 100+ EXERCISES of Javascript LANGUAGE
### BASICS OF Javascript
```Javascript
<!doctype html>
<html lang="en">
   <head>
        <meta charset="utf-8">
            <title>Just a Generic Page</title>
        <script>
           /* count five seconds of time? Hint:
             1000 milliseconds = 1 second.*/
            setTimeout(wakeUpUser, 5000);
            function wakeUpUser() {
            alert("Are you going to stare at this boring page forever?");
        }
        </script>
   </head>
   <body>
      <h1>Just a generic heading</h1>
      <p>Not a lot to read about here. I'm just an obligatory paragraph living in
      an example in a JavaScript book. I'm looking for something to make my life more
      exciting.</p>
   </body>
</html>
```
```javascript
// This program displays a greeting message based on the current time
// Create a new Date object representing the current date and time
var today = new Date();

// Get the current hour from the Date object
var hourNow = today.getHours();

// Declare a variable to hold the greeting message
var greeting;

// Check if the current hour is greater than 18 (6 PM)
if (hourNow > 18) {
  // If true, set the greeting to "Good evening!"
  greeting = 'Good evening!';
}
// Check if the current hour is greater than 12 (noon)
else if (hourNow > 12) {
  // If true, set the greeting to "Good afternoon!"
  greeting = 'Good afternoon!';
}
// Check if the current hour is greater than 0 (midnight)
else if (hourNow > 0) {
  // If true, set the greeting to "Good morning!"
  greeting = 'Good morning!';
}
// If none of the above conditions are true
else {
  // Set the greeting to "Welcome!"
  greeting = 'Welcome!';
}

// Write the greeting message to the document
document.write('<h3>' + greeting + '</h3>');
```
```javascript
//●statements
var age = 25;
var name = "Owen";
if (age > 14) {
    alert("Sorry this page is for kids only!");
} else {
    alert("Welcome " + name + "!");
}
```
```javascript
var scoops = 5;
//●A while statement starts with the keyword while.
while (scoops > 0) {
   document.write("Another scoop!<br>");
   scoops = scoops - 1;
}
document.write("Life without ice cream isn't the same");
```
```javascript
//●Making decisions with JavaScript
if (cashInWallet > 5) {
   order = “I’ll take the works: cheeseburger, fries and a coke”;
} else {
  order = “I’ll just have a glass of water”;
}
```
```javascript
/*●if statement executes its code block only
   if a conditional test is true.*/
if (scoops < 3) {
   alert("Ice cream is running low!");
}
```
```javascript
//●if/else if
if (scoops >= 5) {
   alert("Eat faster, the ice cream is going to melt!");
} else if (scoops < 3) {
   alert("Ice cream is running low!");
}
```
```javascript
//●when you need t o make LOTS of decisions
if (scoops >= 5) {
alert("Eat faster, the ice cream is going to melt!");
} else if (scoops == 3) {
alert("Ice cream is running low!");
} else if (scoops == 2) {
alert("Going once!");
} else if (scoops == 1) {
alert("Going twice!");
} else if (scoops == 0) {
alert("Gone!");
} else {
alert("Still lots of ice cream left, come and get it.");
}
```
```javascript
//●Making decisions with JavaScript
scoops = 5;
while (scoops > 0) {
	document.write("Another scoop!<br>");
	if (scoops < 3) {
		alert("Ice cream is running low!");
	} else if (scoops >= 5) {
		alert("Eat faster, the ice cream is going to melt!");
	}
	scoops = scoops - 1;
}
document.write("Life without ice cream isn't the same");
```
```javascript
//●Happy Birthday program
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Happy Birthday</title>
  </head>
  <body>
  <script>
	var name = "Joe";
	var i = 0;
	while (i < 2) {
		document.write("Happy Birthday to you.<br>");
		i = i + 1;
	}
	document.write("Happy Birthday dear " + name + ",<br>");
	document.write("Happy Birthday to you.<br>");
  </script>
</body>
</html>
```
```javascript
//●console.log
var message = "Howdy" + " " + "partner";
console.log(message);
```
```javascript
//●Opening the console
chrome = Inspect > Console
```
```javascript
var word = "bottles";
//●99 bottles of beer.” code.js  
var count = 99;
while (count > 0) {
	console.log(count + " " + word + " of beer on the wall");
	console.log(count + " " + word + " of beer,");
	console.log("Take one down, pass it around,");
	count = count - 1;
	if (count > 0) {
	console.log(count + " " + word + " of beer on the wall.");
} else {
	console.log("No more " + word + " of beer on the wall.");
}
}
```
```html
//●index.htm
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>My First JavaScript</title>
  </head>
  <body>
    <script>
       var word = "bottles";
       var count = 99;
       while (count > 0) {
		console.log(count + " " + word + " of beer on the wall");
		console.log(count + " " + word + " of beer,");
		console.log("Take one down, pass it around,");
		count = count - 1;
		if (count > 0) {
		console.log(count + " " + word + " of beer on the wall.");
                } else {
                    console.log("No more " + word + " of beer on the wall.");
               }
       }
    </script>
  </body>
</html>
```
```html
//●index.html
<!doctype html>
<html lang="en">
   <head>
     <meta charset="utf-8">
     <title>My First JavaScript</title>
   </head>
   <body>
     <script src="code.js">
     </script>
   </body>
</html>
```
```html
//●howdy.html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Howdy</title>
  </head>
  <body>
  <script>
message = "Howdy" + " " + "partner";
console.log(message);
  </script>
  </body>
</html>
```
```html
//●icecream.html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Icecream!</title>
  </head>
  <body>
  </body>
  <script src="code.js"></script>
<!--
  <script>
	scoops = 5;
	while (scoops > 0) {
		document.write("Another scoop!<br>");
		if (scoops < 3) {
			alert("Ice cream is running low!");
		} else if (scoops >= 5) {
			alert("Eat faster, the ice cream is going to melt!");
		}
		scoops = scoops - 1;
	}
	document.write("Life without ice cream isn't the same");
  </script>
-->
</body>
</html>
```
```html
//●kids.html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>For Kids Only</title>
<script>
var age = 25;
var name = "Owen";
if (age > 14) {
	alert("Sorry this page is for kids only!");
} else {
	alert("Welcome " + name + "!");
}
</script>
</head>
<body>
<h1>This page is for kids only!</h1>
</body>
</html>
```
