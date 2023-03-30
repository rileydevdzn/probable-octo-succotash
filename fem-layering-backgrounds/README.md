<div align="center">
  <img
    src="Profile card - desktop.png"
    alt="Profile card for Victor Crest of London, who has 80 thousand followers, 803 thousand likes, and 1.4 thousand photos."
    height="300px">
</div>

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). 

### The challenge

Users should be able to:

- Build out the project to the designs provided

<div align="center">
  <img
    src="profilecard-desktop-design.jpg"
    alt="Profile card for Victor Crest of London, who has 80 thousand followers, 803 thousand likes, and 1.4 thousand photos."
    height="250px">
  <img
    src="profilecard-mobile-design.jpg"
    alt="Profile card for Victor Crest of London, identical but slightly smaller layout on mobile screen."
    height="250px">
  <p><em>Desktop and mobile designs</em></p>
</div>

### Links

- Solution URL: [Profile card component](https://rileydevdzn.github.io/fem-layering-backgrounds/)

## My process

### Built with

- Semantic HTML5 markup
- Layering multiple CSS backgrounds
- CSS variables
- CSS Grid
- Responsive design
- Realistic workflow, building from professional Figma design files (design-to-code) 

### What I learned

This project included multiple backgrounds: a background color and two images each with linear gradients, then rotated and positioned for different screen sizes. I learned a lot about working with multiple backgrounds and layering; and it took some trial and error to get the order of the background properties correct.

This layout could work well with either Flexbox or Grid. I chose to use Grid for the overall layout to practice using grid areas and then nested Flexbox inside the profile stats section.

### Continued development

Now that I've found a `background` syntax I'm comfortable with (personally, I prefer the version in the CSS Tricks article included in the resources section), I'd like to continue experimenting with multiple backgrounds to see what kind of creative ideas I can come up with.

### Useful resources

- [MDN Web Docs: CSS background](https://developer.mozilla.org/en-US/docs/Web/CSS/background) - Explains all of the background properties and their order when using the CSS `background` shorthand property.
- [MDN Web Docs: Using multiple backgrounds](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders/Using_multiple_backgrounds) - Solid introductory content for using multiple backgrounds with examples. The examples in this article outline various background properties like `background-image`, `background-repeat` and `background-position` as separate lines.
- [CSS Tricks: Stacking order of multiple backgrounds](https://css-tricks.com/stacking-order-of-multiple-backgrounds/) - Another good article, with a slightly different approach using the `background` shorthand property and using a single line for each background and its associated properties, with each background declaration separated by a comma. I find it easier to keep the order straight and keep track of all the properties using this approach when juggling multiple backgrounds.

## Author

- Frontend Mentor - [@rileydevdzn](https://www.frontendmentor.io/profile/rileydevdzn)
