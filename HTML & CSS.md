# 100+ HTML & CSS CONCEPTS
### BASICS 

```html
HTML Document
--------------
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
```html
HTML Headings
-------------
<!DOCTYPE html>
<html>
<body>

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>

</body>
</html>
```
```html
HTML Paragraphs
---------------
<!DOCTYPE html>
<html>
<body>

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>
```
```html
HTML Links
----------
<!DOCTYPE html>
<html>
<body>

<h2>HTML Links</h2>
<p>HTML links are defined with the a tag:</p>

<a href="https://www.w3schools.com">This is a link</a>

</body>
</html>
```
```html
HTML Images
-----------
<!DOCTYPE html>
<html>
<body>

<h2>HTML Images</h2>
<p>HTML images are defined with the img tag:</p>

<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">

</body>
</html>
```
```html
line break
----------
<!DOCTYPE html>
<html>
<body> 

<p>This is a <br> paragraph with a line break.</p>

</body>
</html>
```
```html
The href Attribute
------------------
<!DOCTYPE html>
<html>
<body>

<h2>The href Attribute</h2>

<p>HTML links are defined with the a tag. The link address is specified in the href attribute:</p>

<a href="https://www.w3schools.com">Visit W3Schools</a>

</body>
</html>
```
```html
The src Attribute
-----------------
<!DOCTYPE html>
<html>
<body>

<h2>The src Attribute</h2>
<p>HTML images are defined with the img tag, and the filename of the image source is specified in the src attribute:</p>

<img src="img_girl.jpg" width="500" height="600">

</body>
</html>
```
```html
The width and height Attributes
-------------------------------
<!DOCTYPE html>
<html>
<body>

<h2>Width and Height Attributes</h2>

<p>The width and height attributes of the img tag, defines the width and height of the image:</p>

<img src="img_girl.jpg" width="500" height="600">

</body>
</html>
```
```html
The alt Attribute
-----------------
<!DOCTYPE html>
<html>
<body>

<h2>The alt Attribute</h2>
<p>The alt attribute should reflect the image content, so users who cannot see the image get an understanding of what the image contains:</p>

<img src="img_girl.jpg" alt="Girl with a jacket" width="500" height="600">

</body>
</html>
```
```html
See what happens if we try to display an image that does not exist:
-------------------------------------------------------------------
<!DOCTYPE html>
<html>
<body>

<img src="img_typo.jpg" alt="Girl with a jacket">

<p>If we try to display an image that does not exist, the value of the alt attribute will be displayed instead. </p>

</body>
</html>
```
```html
The style Attribute
-------------------
<!DOCTYPE html>
<html>
<body>

<h2>The style Attribute</h2>
<p>The style attribute is used to add styles to an element, such as color:</p>

<p style="color:red;">This is a red paragraph.</p>

</body>
</html>
```
```html
The lang Attribute
------------------
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```
```html
specifies English as the language and United States as the country
------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```
```html
The title Attribute
-------------------
<!DOCTYPE html>
<html>
<body>

<h2 title="I'm a header">The title Attribute</h2>

<p title="I'm a tooltip">Mouse over this paragraph, to display the title attribute as a tooltip.</p>

</body>
</html>
```
```html
Single or Double Quotes?
------------------------
<!DOCTYPE html>
<html>
<body>

<h2>Single or Double Quotes?</h2>
<p>In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:</p>
<p>Move your mouse over the paragraphs below to see the effect:</p>

<p title='John "ShotGun" Nelson'>John with double quotes</p>
<p title="John 'ShotGun' Nelson">John with single quotes</p>

</body>
</html>
```
