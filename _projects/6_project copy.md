---
layout: page
title: HTML Nav
description: An HTML nav template is important for creating a clear and organized menu structure that makes it easy for visitors to navigate content.
img: assets/img/html.jpg
importance: 4
category: code
---
This is an HTML code for a website's navigation bar with four links: `Home`, `About`, `Contact`, and `Blog`.

```
<!DOCTYPE html>
<html>
<head>
	<title>My Website</title>
	<style>
		/* Style the navigation bar */
		nav {
			background-color: #333;
			overflow: hidden;
		}
		
		/* Style the links inside the navigation bar */
		nav a {
			float: left;
			color: white;
			text-align: center;
			padding: 14px 16px;
			text-decoration: none;
		}
		
		/* Change the color of links on hover */
		nav a:hover {
			background-color: #ddd;
			color: black;
		}
		
		/* Add a color to the active/current link */
		nav .active {
			background-color: #4CAF50;
			color: white;
		}
	</style>
</head>
<body>

	<nav>
		<a href="#" class="active">Home</a>
		<a href="#">About</a>
		<a href="#">Contact</a>
		<a href="#">Blog</a>
	</nav>

</body>
</html>
```
Here's a breakdown of the code:

1. The first line of the code specifies the document type as HTML5 using the `<!DOCTYPE html>` declaration.

2. The `<html>` element is the root element of the HTML page and contains all the other HTML elements.

3. The `<head>` element contains metadata about the document, including the title of the page, which is specified using the `<title>` element. In this case, the title is `My Website`. The `<style>` element is used to define styles for the navigation bar.

4. The `<body>` element contains the visible content of the page.

5. The navigation bar is created using the `<nav>` element. Inside the `<nav>` element, there are four links created using the `<a>` element. 
The href attribute specifies the URL that the link should go to, and the text between the opening and closing `<a>` tags is the text that appears as the link. The first link has a class of `active`, which is used to style the currently active link differently.