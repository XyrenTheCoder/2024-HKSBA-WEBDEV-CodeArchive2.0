
### \<style> tag
+ Used for defining style information for a document (in css)
```html
<html>
	<head>
		<style>
			h1 {color: red};
			p {color: cyan};
		</style>
	</head>
</html>
```

### \<a> tag
+ Defines a hyperlink which is used to link one page to another
+ It takes the `href` attribute which defines the destination
```html
<a href="https://example.com>visit example.com</a>
```

### \<b> tag
+ Makes text bold
```html
<p> normal text <b> bold text </b> </p>
```

### \<br> tag
+ Moves text to the next line
+ It is an empty tag, which means it has no closing tag
```html
<p> line 1 <br> line 2 <br> line 3 </p>
```

### \<button> tag
+ Creates a clickable button
+ Inside the \<button> tag, one can place text and tags like \<a>, \<b>, \<br> and \<img>
```html
<button type="button"> click me </button>
```

### \<div> tag
+ Defines a division or a section inside an html document
```html
<html>
	<head>
		<style>
			.div1 {
				border: 5px outset red;
				text-align: center;
			}
		</style>
	</head>
	<body>
		<div class="div1">
			<p> this is a paragraph inside a div element </p>
		</div>
	</body>
</html>
```

### \<em> tag
+ Used for defining emphasized text
```html
<p> normal text <em> emphasized text </em> </p>
```

### \<embed> tag
+ Defines a container for an external resource, such as a web page, a video or an image
```html
<embed type="image/jpg"  src="image.jpg"  width="300"  height="200">
```

### \<fieldset> tag
+ Specifies a set of related form fields.
```html
<form action="/action_page.php">  
	<fieldset>  
		<legend>caption</legend>  
		<label for="fname">First name:</label>  
		<input type="text" id="fname" name="fname"><br><br>  
		<label for="lname">Last name:</label>  
		<input type="text" id="lname"  name="lname"><br><br>
		<input type="submit" value="Submit"> 
	</fieldset>  
</form>
```

### \<form> tag
+ Defines an html form for user input
```html
<form action="/action_page.php"  method="get">  
	<label for="fname">First name:</label>  
	<input type="text"  id="fname"  name="fname"><br><br>  
	<label for="lname">Last name:</label>  
	<input type="text"  id="lname"  name="lname"><br><br>  
	<input type="submit"  value="Submit">  
</form>
```

### \<h1> - \<h6> tag
+ Used to define html headings
+ \<h1> is the largest and \<h6> is the smallest
```html
<h1>This is heading 1</h1>  
<h2>This is heading 2</h2>  
<h3>This is heading 3</h3>  
<h4>This is heading 4</h4>  
<h5>This is heading 5</h5>  
<h6>This is heading 6</h6>
```

### \<hr> tag
+ Displays a horizontal line, usually used for defining a thematic break
```html
<p> text </p>
<hr>
<p> text </p>
```

### \<i> tag
+ Displays text in *italic*
```html
<p><i>Lorem ipsum</i> is the most popular filler text in history.</p>
```

### \<iframe> tag
+ Defines an inline frame.
+ An inline frame is used to embed another document within the current html document
```html
<iframe src="https://example.com"  title="example"></iframe>
```

### \<img> tag
+ Used for embedding an image inside the html document
```html
<img src="image.jpg"  alt="image"  width="500"  height="600">
```

### \<input> tag
+ Specifies an input field where the user can enter data.
```html
<form action="/action_page.php"  method="get">  
	<label for="fname">First name:</label>  
	<input type="text"  id="fname"  name="fname"><br><br>  
	<label for="lname">Last name:</label>  
	<input type="text"  id="lname"  name="lname"><br><br>  
	<input type="submit"  value="Submit">  
</form>
```

### \<li>, \<ol> and \<ul> tags
+ \<ol>: Defines an ordered list
+ \<ul>: Defines an unordered list
+ \<li>: Defines a list item
```html
<ol>  
	<li>coffe</li>  
	<li>tea</li>  
	<li>milk</li>  
</ol>

<ul>  
	<li>coffe</li>  
	<li>tea</li>  
	<li>milk</li>  
</ul>
```

### \<p> tag
+ Defines a paragraph
```html
<p> never gonna give you up </p>
```

### \<strong> tag
+ Used for defining text with strong importance
```html
<strong> this is important text </strong>
```

### \<table>, \<td>, \<tr> and \<th> tags
+ \<table>: defines an html table
+ \<td>: defines a table cell
+ \<tr>: defines a table row
+ \<th>: defines a table header
```html
<table>  
	<tr>  
		<th>Month</th>  
		<th>Savings</th>  
	</tr>  
	<tr>  
		<td>January</td>  
		<td>$0</td>  
	</tr>
</table>
```

### \<title> tag
+ Defines the title of the documen
+ Placed inside the \<head> tag
```html
<html>
	<head>
		<title> title </title>
	</head>
<head>
```

### \<u> tag
+ Defines text with underline
```html
<u> underlined text </u>
```