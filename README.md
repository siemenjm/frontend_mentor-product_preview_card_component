# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Until this project, I had never styled elements in their focus state before. I chose to go with a box-shadow on the button, as box-shadow does not change the size of the element it is applied to, while changing the border does (causing elements to shift).

To see how you can add code snippets, see below:

```css
button:hover, button:focus {
    background-color: var(--neutral-dark-grayish-blue);
    box-shadow: 0 5px 10px var(--neutral-very-dark-blue);
}

button:focus-visible {
    outline: none;
}
```

### Continued development

Building these types of projects was extremely rewarding, starting from scratch and ending up with a beautiful product. I'd like to continue to keep doing similar projects until churning them out becomes second-nature.

## Author

- Website - [Jared Siemen](https://jaredsiemen.com)
- Frontend Mentor - [@siemenjm](https://www.frontendmentor.io/profile/siemenjm)