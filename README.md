# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size

### Screenshot

![Desktop screenshot](./images/screen-desktop.png)
![Mobile screenshot](./images/screen-mobile.png)

### Links

- Solution URL: [Solution](https://github.com/melissabo94/single-price-grid-component)
- Live Site URL: [Live Site](https://melissabo94.github.io/single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```css
.container {
    display: grid;
    grid-template-rows: 1fr 1.2fr;
    grid-template-columns: 1fr 1fr;
    width: 640px;
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.15);
    gap: 0;
    border-radius: 10px;
}

.intro {
    grid-column: span 2;
    background-color: white;
    padding: 40px;
    border-radius: 5px 5px 0 0;
}
```

### Useful resources

- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Very useful to learn more about Grid!

## Author

- LinkedIn - [Melissa Borgnino](https://www.linkedin.com/in/melissa-borgnino-909712198/)
- Frontend Mentor - [@melissabo94](https://www.frontendmentor.io/profile/melissabo94)

