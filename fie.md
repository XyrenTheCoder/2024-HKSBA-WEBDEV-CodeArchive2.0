
### \<a> tag
+ Defines a hyperlink which is used to link one page to another
+ It takes the `href` attribute which defines the destination
```html
<a href="https://example.com>visit example.com</a>
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
<div>
            <div class="topnav">
                <img align="left" src="../media/images/codearchive.gif">
                <div>
                    <a href="../index.html" target="_self">&#x1F511;Logout</a>
                    <a href="https://forms.gle/7dtpB1RuatVe6Rtu9" target="_blank">&#x1F4AC;Feedback</a>
                    <a href="../contact.html">&#x1F5A5;&#xFE0F;Contact</a>
                    <a class="active" href="../tutorial.html" target="_self">&#x1F3E0;Home</a>
                </div>
            </div>
            <div class="sidenav">
                <br><br><br>
                <a href='../tutorial.html'><p>Main page</p></a>
                    <a href="../tutorial.html#INTRO"><p>&nbsp;&nbsp;&nbsp;Introduction</p></a>
                    <a href="../tutorial.html#WHATISHTML"><p>&nbsp;&nbsp;&nbsp;What is HTML?</p></a>
                    <a href="../tutorial.html#ELEMENTS"><p>&nbsp;&nbsp;&nbsp;Elements</p></a>
                    <a href="../tutorial.html#TAGS"><p>&nbsp;&nbsp;&nbsp;Tags</p></a>
                        <div translate='no'>
                            <a href='../childs/_comment.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Commenting in HTML</p></a></li>
                            <a href='../childs/_doctype.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DOCTYPE Declaration</p></a></li>
                            <a href='../childs/_html.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Set up document</p></a></li>
                            <a href='../childs/_head.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Head of a document</p></a></li>
                            <a href='../childs/_meta.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Set up metadata</p></a></li>
                            <a href='../childs/_script.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Using scripts</p></a></li>
                            <a href='../childs/_style.html'><p><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Styling</span></p></a></li>
                            <a href='../childs/_body.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Body container</p></a></li>
                            <a href='../childs/_footer.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Set up footer</p></a></li>
                            <a href='../childs/!global_attr.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Global attributes</p></a></li>
                            <a href='../childs/!event_attr.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Event attributes</p></a></li>
                        </div>
                        <a href="../tutorial.html#TUTORIAL"><p>&nbsp;&nbsp;&nbsp;Tutorials</p></a>
                        <a href="../tutorial.html#CONCLUSION"><p>&nbsp;&nbsp;&nbsp;Conclusion</p></a>
                <a href='../videos.html'><p>Videos</p></a>
                <a href='../quizintro.html'><p>Quizzes</p></a>
                <br><br><br><br><br><br>
            </div>

<div class="sidenav">
                <br><br><br>
                <a href='./tutorial.html'><p><span>Main page</span></p></a>
                    <a href="#INTRO"><p>&nbsp;&nbsp;&nbsp;Introduction</p></a>
                    <a href="#WHATISHTML"><p>&nbsp;&nbsp;&nbsp;What is HTML?</p></a>
                    <a href="#ELEMENTS"><p>&nbsp;&nbsp;&nbsp;Elements</p></a>
                    <a href="#TAGS"><p>&nbsp;&nbsp;&nbsp;Tags</p></a>
                        <a href='./childs/_comment.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Commenting in HTML</p></a></li>
                        <a href='./childs/_doctype.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DOCTYPE Declaration</p></a></li>
                        <a href='./childs/_html.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Set up document</p></a></li>
                        <a href='./childs/_head.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Head of a document</p></a></li>
                        <a href='./childs/_meta.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Set up metadata</p></a></li>
                        <a href='./childs/_script.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Using scripts</p></a></li>
                        <a href='./childs/_style.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Styling</p></a></li>
                        <a href='./childs/_body.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Body container</p></a></li>
                        <a href='./childs/_footer.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Set up footer</p></a></li>
                        <a href='./childs/!global_attr.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Global attributes</p></a></li>
                        <a href='./childs/!event_attr.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Event attributes</p></a></li>
                    <a href="#TUTORIAL"><p>&nbsp;&nbsp;&nbsp;Tutorials</p></a>
                        <a href='./childs/how_to_button.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ripple effect button</p></a></li>
                        <a href='./childs/how_to_iframe.html'><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Creating iframe</p></a></li>
                    <a href="#CONCLUSION"><p>&nbsp;&nbsp;&nbsp;Conclusion</p></a>
                <a href='./videos.html'><p>Videos</p></a>
                <a href='./quizintro.html'><p>Quizzes</p></a>
                <br><br><br><br><br><br>
            </div>
