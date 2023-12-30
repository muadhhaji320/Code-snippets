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
