# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
      - [Mobile design](#mobile-design)
      - [Desktop design](#desktop-design)
    - [Links](#links)
  - [My process](#my-process)
    - [Key Implementation Details](#key-implementation-details)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

This mini project is a responsive recipe page built using semantic HTML and modern CSS. It displays essential recipe details such as the **recipe name, a brief description, preparation time, ingredients, step-by-step instructions, and nutritional values** of the meal.

The design is clean, minimalistic, and mobile-first, ensuring that the page is visually appealing and functions well across a wide range of screen sizes and devices.
Key Focus Areas:

- Semantic HTML structure for accessibility

- Grid for clean, responsive layout

- Basic styling to achieve a visually appealing recipe page.

- A mobile-friendly design.

### Screenshot

#### Mobile design

![Mobile Design](design/mobile-design.png)

#### Desktop design

  ![Desktop Design](design/desktop-design.png)

### Links

- Solution URL: [https://github.com/Randy-22/recipe-page](https://github.com/Randy-22/recipe-page)
- Live Site URL: [https://randy-22.github.io/recipe-page/](https://randy-22.github.io/recipe-page/)

## My process

This project was built using **semantic HTML5 and modern CSS3** to create a clean, responsive recipe Page. All styles were applied through an **external CSS file** to maintain separation of structure and design.

The HTML uses CSS Grid which was applied to the body to center the `.recipe` component both vertically and horizontally on the page. The card displays a featured image, article tags, publishing date, heading, description, and author information—all structured for accessibility and clarity.

### Key Implementation Details

- Responsive Layout with media queries:
I implemented CSS media queries using @media (max-width: 375px) to ensure the page displays properly on small screens, such as mobile devices. This allows the layout, spacing, and typography to adapt for better readability and usability on compact viewports. Key adjustments include removing extra padding and margins, setting elements to full width, and eliminating border radii to make the design fit edge-to-edge on smaller screens.

- Grid Centering:
The `body` uses CSS grid to center the `recipe` in the viewport, creating a balanced and professional layout across all devices.

- BEM Naming Convention:
Class names are structured following the **BEM (Block Element Modifier)** methodology. This improves code organization, prevents style conflicts, and enhances reusability for future components.

- Global variables:
One key aspect of this project was the implementation of CSS global variables, which helped promote reusability and maintainability across the codebase.

- Typography:
I used the  `"Outfit", sans-serif` for setting font of non headers and used `"Young Serif", sans-serif` for setting font of the headings. All these fonts are from Google Fonts for modern readability.

### Built with

- Semantic HTML5 markup
- CSS3 custom properties
- Grid
- Google Fonts

### What I learned

One important lesson I learned from this project is that **custom styling for each element on a webpage can be challenging and confusing** if not planned carefully. What really helped me manage this complexity was using **BEM (Block Element Modifier)** naming conventions for my HTML elements. This approach made it easier to structure and apply consistent styles across the project.

I also realized that **setting margins and padding requires thoughtful planning**. Every spacing decision affects the overall layout, so it’s important to be precise and consistent to maintain visual balance and avoid clutter.

Another key takeaway was learning how to use the `:not(:last-child)`**pseudo-class**.This powerful selector allowed me to style all rows of a table except the last one, which was exactly what I needed to control the border styling.

Finally, I discovered the `::marker` **pseudo-element**, which is incredibly useful for styling list item markers. It gave me more control over the appearance of bullet points and numbers in lists, helping to better match the overall design theme.

To see how you can add code snippets, see below:

```css
.recipe__nutrition table tr:not(:last-child) {
  border-bottom: 1px solid var(--clr-page);
}
```

### Useful resources

- [CSS Grid Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/) - This site provides user friendly and a simple way to really grasp the concept of CSS grid.
- [CSS ::marker pseudo-element](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker) - Learn more about the marker pseudo-element.
- - [CSS :not(:last-child)](https://developer.mozilla.org/en-US/docs/Web/CSS/:last-child) - Learn more about this.

## Author

- github - [Randy Sekyere](https://github.com/Randy-22)
- Frontend Mentor - [@Randy-22](https://www.frontendmentor.io/profile/Randy-22)
