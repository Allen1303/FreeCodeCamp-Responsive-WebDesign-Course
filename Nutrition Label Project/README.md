# Nutrition Label Project
This `README` provides a beginner-friendly explanation of the typography concepts applied in the Nutrition Label project, focusing on the most important aspects.

## Typography Concept
Typography plays a crucial role in making text content visually appealing and easy to read. In the Nutrition Label project, the following key typography concepts are applied:

## Font Family
The font family determines the overall appearance and style of the text. In this project, the "Open Sans" font family is used. It offers a clean and modern look, ensuring readability across different devices and screen sizes.

```css
body {
  font-family: "Open Sans", sans-serif;
}
```

## Font Size and Weight
Font size and weight are adjusted to create visual hierarchy and emphasize important information. Larger font sizes are used for headings and significant details, while smaller font sizes are used for less prominent text. Font weight is also varied to add emphasis and create contrast.

```css
header h1 {
  font-size: 2em; /* Larger font size for headings */
  font-weight: 800; /* Bolder font weight for emphasis */
}

.bold {
  font-weight: 800; /* Bolder font weight for important details */
}

.small-text {
  font-size: 0.85rem; /* Smaller font size for less prominent text */
}
```

## Spacing and Alignment
Consistent spacing and alignment improve readability and create a balanced layout. Proper margins, paddings, and line heights are applied to ensure sufficient space between text elements and other page elements. Text alignment is adjusted to maintain visual consistency.

```css
p {
  margin: 0; /* Remove default paragraph margins */
  display: flex; /* Align text content */
  justify-content: space-between; /* Adjust spacing between elements */
}

.divider {
  margin: 2px 0; /* Add spacing between dividers */
}

.indent {
  margin-left: 1em; /* Indent text for improved readability */
}
```

#### These typography concepts collectively contribute to creating a visually appealing and easy-to-read nutrition label.

## Acknowledgment
This project is primarily based on the design and requirements provided by FreeCodeCamp.

