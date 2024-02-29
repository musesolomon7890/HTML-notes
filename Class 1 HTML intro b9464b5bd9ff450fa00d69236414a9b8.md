# Class 1 HTML intro

# Paragraph in HTML

adding paragraphs to a web page

```html
<p1> Paragraph <p1>
```

# Links in HTML

adding links to a webpage

```html
<a href "www.google.com"> Google </a>
```

# Images in HTML

adding images to a web page

```html
<img src = "image/dog.jpeg" alt = "Picture of a dog">
```

# Videos in HTML

adding videos in html

```html
<video width ="720" height="1080" controls>
<source src = "prank.mp4" type="video/mp4">
<source src = "prank.ogg" type="video/ogg">
```

# div in html

adding div elements that take all available width of the code within

```html
<div>
<h1> this is a div element </h1>
</div>
```

# iframe in html

used to display a webpage within a webpage

```html
<iframe src = "https://twitter.com" title="twitter"></iframe>
```

# html favicon

A favicon image is displayed to the left of the page title in the browser tab

```html
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
```

# HTML table

how to create tables in html

```html
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
</table>
```

# HTML forms

how to create forms in html

```html

<input type="text">	Displays a single-line text input field
<input type="radio">	Displays a radio button (for selecting one of many choices)
<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
<input type="submit">	Displays a submit button (for submitting the form)
<input type="button">	Displays a clickable buttonThe <input type="text"> defines a single-line input field for text input.
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
The <label> Element
Notice the use of the <label> element in the example above.

The <label> tag defines a label for many form elements.

The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focuses on the input element.

The <label> element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <label> element, it toggles the radio button/checkbox.

The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.
<p>Choose your favorite Web language:</p>

<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
```

# HTML css

how to add css to html

```html
<h1 style="color:blue;">A Blue Heading</h1> inline
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head> internal
<head>
  <link rel="stylesheet" href="styles.css">
</head>
external
```

# html colors

how to color html elements

```html
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>e
```

# html audio

how to add audio to html

```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
</audio>
```

# html comments

adding comments on html

```html
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->
```

# html classes

The HTML `class` attribute is used to specify a class for an HTML element.

Multiple HTML elements can share the same class.

```html
<body>

<div class="city">
  <h2>London</h2>
  <p>London is the capital of England.</p>
</div>

<div class="city">
  <h2>Paris</h2>
  <p>Paris is the capital of France.</p>
</div>

<div class="city">
  <h2>Tokyo</h2>
  <p>Tokyo is the capital of Japan.</p>
</div>

</body>
```

# html id

The HTML `id` attribute is used to specify a unique id for an HTML element.

```html
</style>
</head>
<body>

<h1 id="myHeader">My Header</h1>

</body>
</html>
```