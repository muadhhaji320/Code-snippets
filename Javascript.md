# 100+ EXERCISES of Javascript LANGUAGE
### BASICS OF Javascript
```Javascript
EXERCISE(1)
[] count five seconds of time? Hint:
1000 milliseconds = 1 second.
-------------------------------
<!doctype html>
<html lang="en">
   <head>
        <meta charset="utf-8">
            <title>Just a Generic Page</title>
        <script>
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
[] How to make a statement
------------------------------
var age = 25;
var name = "Owen";
if (age > 14) {
    alert("Sorry this page is for kids only!");
} else {
    alert("Welcome " + name + "!");
}
```
```javascript
[] A while statement starts with the keyword while.
---------------------------------------------------
var scoops = 5;
while (scoops > 0) {
   document.write("Another scoop!<br>");
   scoops = scoops - 1;
}
document.write("Life without ice cream isn't the same");
```
```javascript
[] Making decisions with JavaScript
-----------------------------------
if (cashInWallet > 5) {
   order = “I’ll take the works: cheeseburger, fries and a coke”;
} else {
  order = “I’ll just have a glass of water”;
}
```
```javascript
[] The if statement executes its code block only if a conditional test is true.
-------------------------------------------------------------------------------
if (scoops < 3) {
   alert("Ice cream is running low!");
}
```
```javascript
[] We can have one test, and then another test with if/else if
--------------------------------------------------------------
if (scoops >= 5) {
   alert("Eat faster, the ice cream is going to melt!");
} else if (scoops < 3) {
   alert("Ice cream is running low!");
}
```
```javascript
[] when you need t o make LOTS of decisions
-------------------------------------------
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
[] Happy Birthday program
-------------------------
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
[] A closer look at console.log
---------------------------------
var message = "Howdy" + " " + "partner";
console.log(message);
```
