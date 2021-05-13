# Frontend Mentor - Stats Preview Card Component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size;

### Screenshot

![Desktop](https://i.imgur.com/L4ioll5.png)
![Mobile](https://i.imgur.com/7R9dhZ5.png)

### Links

- Live Site URL: [GitHub Pages](https://courtesy-code.github.io/StatsPreviewCardComponent/) 
- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/solution-desktop-first-using-html-and-css-only-t1iyRoX53)


## My process

### Built with

- Semantic HTML5 markup;
- CSS3 custom properties;
- Flexbox;
- Media Queries;

### What I learned

One of the new things I learned doing this challenge was how to monotone an image, using a "filter" container with the color you want to apply and adding the proper `filter` propriety to the image itself.

```css
.main-section .filter {
    background-color: hsl(277, 55%, 51%);
}

.main-section .filter .image {
    -webkit-filter: grayscale(100%);
    filter: grayscale(100%);
    opacity: 0.5;
};
```

### Continued development



### Useful resources

- [Monotone an Image with CSS](https://css-tricks.com/snippets/css/monotone-image-css/) - This article taught me how to monotone images with only CSS.

## Author

- LinkedIn - [Raphael Garcia](https://www.linkedin.com/in/pro-raphael-garcia/)
- GitHub - [@courtesy-code](https://github.com/courtesy-code)
- Frontend Mentor - [@courtesy-code](https://www.frontendmentor.io/profile/courtesy-code)
