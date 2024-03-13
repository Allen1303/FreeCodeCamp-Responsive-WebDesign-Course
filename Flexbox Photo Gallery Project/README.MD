# FlexBox Photo Gallery Project
Welcome to the `FlexBox` Photo Gallery project! In this walkthrough, we'll explore the concept of `FlexBox` in CSS and how it's applied to create a responsive `photo gallery`. This project is beginner-friendly, and we'll guide you through the `HTML` markup and `CSS styles` used.

## Table of Contents
+ `FlexBox Concept`
+ `Project Walkthrough`
+ `HTML Markup`
+ `CSS Styles`
+ `Key FlexBox Concepts`
+`Acknowledgments`
## FlexBox Concept
`FlexBox`, or the Flexible Box Layout, is a layout model in CSS that allows the design of complex layouts and alignment of items within a container with ease. It provides a more efficient and predictable way to distribute space among items in a container, even when their size is unknown or dynamic.

`FlexBox` introduces properties like display: flex, flex-direction, justify-content, align-items, and more, which help control the layout and alignment of elements.

## Project Walkthrough
### HTML Markup
The HTML structure is straightforward, consisting of a header and a gallery of cat photos.
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- meta and link tags -->
  </head>
  <body>
    <header class="header">
      <h1>css flexbox photo gallery</h1>
    </header>
    <div class="gallery">
      <!-- Images go here -->
    </div>
  </body>
</html>
```
## CSS Styles
### Let's break down the key CSS styles applied to the project:
```css
* {
  box-sizing: border-box;
  font-family: "Montserrat Subrayada", sans-serif;
}

body {
  /* Styles for the body */
}

.gallery img {
  /* Styles for the gallery images */
}

.header {
  /* Styles for the header */
}

.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  /* Other styles for padding, margin, and gap */
}
```
The .gallery class utilizes FlexBox properties to create a row-based layout with wrapping, allowing the images to adjust dynamically based on the container's width.

## Key FlexBox Concepts
+ `display: fle`x;: Turns the container into a flex container, enabling flex properties.
+ `flex-directio`n: Defines the main axis along which the flex items are placed.
+ `flex-wrap`: Controls whether the flex container should wrap its content or not.
+ `justify-content`: Aligns items on the main axis.
+ `align-items`: Aligns items on the cross axis.
## Acknowledgments
Special thanks to `FreeCodeCamp` for providing the photo gallery challenge. Check them out at `FreeCodeCamp` for more interactive coding challenges and tutorials.