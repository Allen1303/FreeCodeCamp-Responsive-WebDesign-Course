# Rothko Painting Project
Welcome to the Rothko Painting project! This` README.md` file will guide you through the entire project, providing detailed explanations of the HTML and CSS code used. By the end of this walkthrough, you'll have a clear understanding of how to create this artistic representation using basic HTML and CSS.

## Table of Contents
+ `Project Overview`
+ `Getting Started`
+ `HTML Walkthrough`
+ `CSS Walkthrough`
+ `Key Code Snippets`
+ `Acknowledgment`
+ `Project Overview`
This project aims to create a visual representation inspired by Rothko paintings using simple HTML markup and CSS styles. The canvas is divided into three colored rectangles, each with unique styles and transformations.

## Getting Started
To create this project, follow these steps:

Create a new `HTML file` (e.g., index.html) and a CSS file (e.g., style.css).
Copy the provided HTML code into your `HTML` file and the CSS styles into your `CSS file`.
Open your HTML file in a web browser to see the Rothko-inspired painting.
HTML Walkthrough

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="shortcut icon" href="images/color-palette.png" type="image/x-icon" />
    <link rel="stylesheet" href="style.css" />
    <title>Rothko Painting</title>
  </head>
  <body>
    <div class="frame">
      <div class="canvas">
        <div class="one"></div>
        <div class="two"></div>
        <div class="three"></div>
      </div>
    </div>
  </body>
</html>
```

This `HTML` structure includes a frame and a canvas div containing three colored rectangles (one, two, and three). The CSS file (`style.css`) provides the styling for these elements.

## CSS Walkthrough
```css
.frame {
  /* Border styling */
  border: 50px solid black;
  width: 500px;
  padding: 50px;
  margin: 20px auto;
}

.canvas {
  width: 500px;
  height: 600px;
  background-color: #4d0f00;
  overflow: hidden;
  filter: blur(2px);
}

.one {
  width: 425px;
  height: 150px;
  background-color: #efb762;
  margin: 20px auto;
  box-shadow: 0 0 3px 3px #efb762;
  border-radius: 9px;
  transform: rotate(-0.6deg);
}

.two {
  width: 475px;
  height: 200px;
  background-color: #8f0401;
  margin: 0 auto;
  margin-bottom: 20px;
  box-shadow: 0 0 3px 3px #8f0401;
  border-radius: 8px 10px;
  transform: rotate(0.4deg);
}

.three {
  width: 91%;
  height: 28%;
  background-color: #b20403;
  margin: auto;
  filter: blur(2px);
  box-shadow: 0 0 5px 5px #b20403;
  border-radius: 30px 25px 60px 12px;
  transform: rotate(-0.2deg);
}

.one,
.two {
  filter: blur(1px);
}
```

This CSS file provides styling for the frame, canvas, and three rectangles (one, two, and three). Styles include border, width, height, background color, shadow effects, border radius, and transformations.

## Key Code Snippets
Here are some key code snippets illustrating the application of styles:

### Setting the border and width for the frame:

```css
.frame {
  border: 50px solid black;
  width: 500px;
  /* ... */
}
```

### Styling the canvas with background color, overflow, and blur effect:

```css
.canvas {
  width: 500px;
  height: 600px;
  background-color: #4d0f00;
  overflow: hidden;
  filter: blur(2px);
  /* ... */
}
```

### Defining the styles for the first rectangle (one):

```css
.one {
  width: 425px;
  height: 150px;
  background-color: #efb762;
  /* ... */
}
```
## Acknowledgment
Special thanks to freeCodeCamp for providing valuable learning resources and challenges.


