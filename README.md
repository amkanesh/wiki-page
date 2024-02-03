# wiki-page
This project will help us learn the basics of **HTML** and **CSS**, as well as how to use these to create a simple webpage.

## Objective
Choose your favorite animal and create an informative wiki page about it! You do not need to write the text yourself, though you're welcome to do so--copy pasting (short) descriptions from another source is okay.
+ Difficulty: Beginner
+ Prerequisites: Basic HTML and CSS knowledge

## Setup
Create a new HTML/CSS project at [CodePen](https://codepen.io).

## HTML
First, in the `body` of the HTML tab (wrapped with `<body>` tags!), add the following:
+ A page header using the `<h1>` tag. E.g.:
```
<h1>Whale Shark</h1>
```
+ Either an ordered list or unordered list (either using `ol` or `ul`, respectively)
```
<ul>
    <li>Description</li>
    <li>Distribution and Habitat</li>
</ul>
```
+ At least two sections of your wiki page (e.g. a 'Description' section or a 'Habitat' section) using `h2`, `h3`, etc.
+ A picture of your wiki subject using the `<img>` tag. Don't forget an `alt` description!
+ Within the `img` tag, give this image an `id` of `wikipic`.
```
<img height=300px id="wikipic" src="https://earth.org/wp-content/uploads/2022/02/Untitled-design-2022-02-07T145557.876.jpg" alt="A picture of a whale shark.">
```
+ At least one hyperlink, using the `<a>` tag and `href` keywords.
```
<p>More information can be found <a href="https://en.wikipedia.org/wiki/Whale_shark">here</a> at Wikipedia.</p>
```

Protip: You can use `p` tags to group text into their own paragraphs!

## CSS
Now we move on to styling and decorating the page. Using selectors:
+ Change the color of the background OR add a background image. Make sure your text is still readable! These can be edited with the `background-color` and `background-image` attributes, respectively.
+ Change the font of your text (using the `color` attribute)
+ Change the color of your links (hint: make sure to target the `a` selector to only change link text colors)
+ Using the `wikipic` selector we created, move your image so that it's placed on the **right** side of the screen, inline with the text. (like Wikipedia!) (hint: try using the `float` attribute)

Note: you should also resize the image to better fit on the screen.

## Stretch Goals
Feel free to keep decorating your wiki page! 

An additional challenge would to be adding a horizontal navigation bar at the top of your page that links to different sections of your article. E.g. there'd be a link to the 'Description' section or 'History' section, etc. (Hint: try using a list!) You could also add an icon for your wiki at the top left corner in this navigation bar. You could also try making it a fixed navigation bar, meaning it won't move as the user scrolls through the article!

## Resources
+ https://www.w3schools.com/css/css_selectors.asp
+ https://www.w3schools.com/html/default.asp
