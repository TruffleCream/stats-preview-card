# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)
![](./screenshot_mobile.png)

### Links

- [Solution URL](https://github.com/Ri-Raghav/stats-preview-card)
- [Live Site URL](https://ri-raghav.github.io/stats-preview-card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### **What I learned**

How to use and create psuedo-elements using CSS ::after :

```css
.img-component::after {
    position: absolute;
    content: '';
    height: 100%;
    width: 100%;
    left: 0;
    top: 0;
    background-color: hsla(277, 89%, 42%, 0.6);
}
```
Using grid system in CSS :

```css
#wrapper {
    background: hsl(244, 38%, 16%);
    display: grid;
    grid-template-columns: 1fr 1fr;
    border-radius: 20px;
    overflow: hidden;
    margin: 2rem;
}
```

## Author

- Frontend Mentor - [@R. Raghav](https://www.frontendmentor.io/profile/Ri-Raghav)
