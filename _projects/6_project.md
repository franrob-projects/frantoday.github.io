---
layout: page
title: HTML Body
description: An HTML body template provides a consistent structure and layout for the content of your web pages, making it easier for visitors to content.
img: assets/img/html2.jpg
importance: 4
category: code
---

This is a basic HTML file code that includes a `header`, `main section`, and `footer` with some sample content including `headings`, `paragraphs`, `links`, and a `form`. It also includes a reference to an external CSS file to style the webpage.
```
<!DOCTYPE html>
<html>
<head>
	<title>My Website</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
</head>
<body>

	<header>
		<h1>Welcome to My Website</h1>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">About</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
	</header>

	<main>
		<section>
			<h2>About Us</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin vel libero sed nisl elementum lacinia. Nullam posuere lectus et arcu hendrerit efficitur.</p>
		</section>
		<section>
			<h2>Our Services</h2>
			<ul>
				<li>Service 1</li>
				<li>Service 2</li>
				<li>Service 3</li>
			</ul>
		</section>
		<section>
			<h2>Contact Us</h2>
			<form>
				<label for="name">Name:</label>
				<input type="text" id="name" name="name"><br>

				<label for="email">Email:</label>
				<input type="email" id="email" name="email"><br>

				<label for="message">Message:</label>
				<textarea id="message" name="message"></textarea><br>

				<input type="submit" value="Submit">
			</form>
		</section>
	</main>

	<footer>
		<p>Copyright © My Website 2023</p>
	</footer>

</body>
</html>
```
Here's a breakdown of the main components of the HTML code:

1. `<!DOCTYPE html>`: This is the HTML5 document type declaration.

2. `<html>`: This is the root element of the HTML document.

3. `<head>`: This element contains metadata about the document, such as the title of the page, character encoding, viewport settings, and links to stylesheets.

4. `<title>`: My Website</title>: This element sets the title of the document that appears in the browser's tab.

5. `<meta charset="UTF-8">`: This sets the character encoding of the document to UTF-8, which can handle all types of characters.

6. `meta name="viewport" content="width=device-width, initial-scale=1.0"`>: This sets the viewport of the document to the width of the device and an initial scale of 1.0, which makes the page responsive.

7. `<link rel="stylesheet" href="style.css">`: This links to an external stylesheet file that contains the styles for the page.

8. `<body>`: This element contains the visible content of the page.

9. `<header>`: This element contains the main header of the page, which typically includes the website name/logo and the main navigation.

10. `<nav>`: This element contains the navigation links of the website.

11. `<ul> and <li>`: These elements create an unordered list of navigation links.

12. `<main>`: This element contains the main content of the page.

13. `<section>`: This element groups related content together and gives them a heading.





