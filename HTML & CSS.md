# 100+ HTML & CSS CONCEPTS
### BASICS 

```html
<!--●HTML Document->
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
<!DOCTYPE html>
<html>
<body>

<!--●HTML Headings->
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
<!DOCTYPE html>
<html>
<body>

<!--●HTML Paragraphs->
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>HTML Links</h2>
<p>HTML links are defined with the a tag:</p>

<!--●HTML Links->
<a href="https://www.w3schools.com">This is a link</a>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>HTML Images</h2>
<p>HTML images are defined with the img tag:</p>

<!--●HTML Images->
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body> 

<!--●line break->
<p>This is a <br> paragraph with a line break.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>The href Attribute</h2>

<p>HTML links are defined with the a tag. The link address is specified in the href attribute:</p>

<!--●The href Attribute->
<a href="https://www.w3schools.com">Visit W3Schools</a>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>The src Attribute</h2>
<p>HTML images are defined with the img tag, and the filename of the image source is specified in the src attribute:</p>

<!--●The src Attribute->
<img src="img_girl.jpg" width="500" height="600">

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>Width and Height Attributes</h2>

<p>The width and height attributes of the img tag, defines the width and height of the image:</p>

<!--●The width and height Attributes->
<img src="img_girl.jpg" width="500" height="600">

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>The alt Attribute</h2>
<p>The alt attribute should reflect the image content, so users who cannot see the image get an understanding of what the image contains:</p>

<!--●The alt Attribute->
<img src="img_girl.jpg" alt="Girl with a jacket" width="500" height="600">

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<!--●See what happens if we try to display an image that does not exist:->
<img src="img_typo.jpg" alt="Girl with a jacket">

<p>If we try to display an image that does not exist, the value of the alt attribute will be displayed instead. </p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>The style Attribute</h2>
<p>The style attribute is used to add styles to an element, such as color:</p>

<!--●The style Attribute->
<p style="color:red;">This is a red paragraph.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html lang="en"> <!--●The lang Attribute->
<body>
...
</body>
</html>
```
```html
<!DOCTYPE html>
<!--●specifies English as the language and United States as the country->
<html lang="en-US">
<body>
...
</body>
</html>
```
```html

-------------------
<!DOCTYPE html>
<html>
<body>

<h2 title="I'm a header">The title Attribute</h2> <!--●The title Attribute->

<p title="I'm a tooltip">Mouse over this paragraph, to display the title attribute as a tooltip.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>Single or Double Quotes?</h2>
<p>In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:</p>
<p>Move your mouse over the paragraphs below to see the effect:</p>

<!--Single or Double Quotes?->
<p title='John "ShotGun" Nelson'>John with double quotes</p>
<p title="John 'ShotGun' Nelson">John with single quotes</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h1 style="font-size:60px;">Heading 1</h1> <!--CSS font-size property->

<p>You can change the size of a heading with the style attribute, using the font-size property.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>

<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr> <!--HTML Horizontal Rules->

<h2>This is heading 2</h2>
<p>This is some other text.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<p>The pre tag preserves both spaces and line breaks:</p>

<pre> <!--HTML <pre> Element->
   My Bonnie lies over the ocean.

   My Bonnie lies over the sea.

   My Bonnie lies over the ocean.
   
   Oh, bring back my Bonnie to me.
</pre>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<p>I am normal</p>
<!--HTML Styles->
<p style="color:red;">I am red</p> 
<p style="color:blue;">I am blue</p>
<p style="font-size:50px;">I am big</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>

<!--Set the background color for a page to powderblue:->
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<!--Set background color for two different elements:->
<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<!--Set Text Color for two different elements->
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<!--Fonts->
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<!--Text Size->
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<!--Text Alignment->
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<!--HTML Text Formatting->
<p><b>This text is bold</b></p>
<p><i>This text is italic</i></p>
<p>This is<sub> subscript</sub> and <sup>superscript</sup></p>

</body>
</html>
```
```html
<!DOCTYPE html>
<html>
<body>

<p>This text is normal.</p>

<p><b>This text is bold.</b></p> <!--.●HTML <b> for bold text.->

</body>
</html>
```
```html

----------------------
<!DOCTYPE html>
<html>
<body>

<p>This text is normal.</p>

<p><strong>This text is important!</strong></p> <!--●HTML <strong> element->

</body>
</html>
```
