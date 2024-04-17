![Piano Project](piano_image.jpg)
# Piano Project Readme
This readme explains the HTML code structure and CSS styles used to create a simple piano illustration. By following along and building this project, you'll learn valuable web development skills!

## Skills Learned:

#### Basic HTML Structure:
Creating a basic webpage structure using HTML elements like div, img, and link.
Understanding the purpose of the head and body sections in HTML.

## Applying CSS Styles:
Using CSS selectors to target specific elements and style their appearance.
Implementing properties like `background-color`, `width`, `height`, `margin`, and `padding` to control the layout of the webpage elements.
Utilizing pseudo-elements like `::after` to add visual details to existing elements.
### Responsive Design Concepts:
Implementing media queries to adjust the layout of the piano illustration for different screen sizes.
Code Breakdown:

#### The code for this project consists of both HTML and CSS. Here are some snippets with explanations to illustrate the key concepts:

1. HTML Structure - Building Blocks:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Piano Project</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div id="piano"></div>
  </body>
</html>
```

#### This code defines the basic structure of the webpage. Here's a breakdown:

`DOCTYPE html`: Declares the document type as` HTML`.
html: The root element of the `HTML document`.
head: Contains meta information about the document, including the character encoding, title, and a link to the external CSS stylesheet `(style.css)`.
body: Contains the visible content of the webpage, including the main container element `(div id="piano")` for the piano illustration.

```html
<body>
  <div id="piano">
    <img class="logo" src="images/piano_logo.svg" alt="Piano Illustration Logo" />

    <div class="keys">
      <div class="key"></div>
      <div class="key black--key"></div>
      <div class="key"></div>
      <div class="key black--key"></div>
    </div>
  </div>
</body>
```

body: This is the main container for all of the visible content on the webpage.
`div id="piano"`: This is the piano container, acting as a wrapper for the logo and keys.
img class="logo": This embeds an image representing the logo of the piano illustration.
div class="keys": This container holds all of the individual piano key elements.
div class="key": Each div with this class represents a single white piano key.
`div class="key black--key"`: These div elements, with both the key and `black--key classes`, create black piano keys positioned on top of white keys using CSS.

## 2. CSS Styling - Adding Visuals:

```css
#piano {
  position: relative;
  border-radius: 15px;
  background-color: rgba(121, 103, 70, 0.863);
  width: 992px;
  height: 290px;
  margin: 80px auto;
  padding: 90px 20px 0 20px;
}
```

#### This code styles the main piano container element with the ID piano. It uses various CSS properties to achieve the desired look:
`position: relative;:` Enables absolute positioning of child elements (like the logo) within the piano container.
`border-radius: 15px;:` Adds rounded corners to the piano container.
`background-color:` Sets a semi-transparent brown background color for the piano body.
`width and height:` Define the dimensions of the piano container.
`margin: 80px auto;:` Adds margin around the piano for better positioning on the page.
`padding:` Sets padding within the piano container, creating space for the piano keys.

```html
<div class="keys">
  <div class="key"></div>
  <div class="key black--key"></div>
</div>
```

#### The piano keys are created using multiple `div elements` with classes key and `black--key`. Here's what this achieves:

The element with class key represents a white piano key.
The element with classes key `black--key` represents a black piano key. An additional black pseudo-element is styled using CSS to create the dark key on top of the white key element. 4. `Media Queries for Responsiveness:`

```css
@media (max-width: 768px) {
  #piano {
    width: 358px;
  }
  .keys {
    width: 318px;
  }
  .logo {
    width: 150px;
  }
}
```
 This code demonstrates a `media query` that adjusts the layout for smaller screens `(less than 768px wide)`. It reduces the width of the piano container (#piano), the piano keys container (keys), and the logo (logo) to ensure they fit well on smaller devices.

## Acknowledgement:

A big thanks to FreeCodeCamp `https://www.freecodecamp.org/` for providing the resourse and guidance to create this project. The Piano Project is a fun and educational way to learn web development skills, for beginners looking to improve their skkills.