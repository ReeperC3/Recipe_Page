# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](/assets/images/image-omelette.jpeg)

### Links

- Solution URL: [Github](https://github.com/reeperc3/Recipe_Page)
- Live Site URL: [Github Pages](https://reeperc3.github.io/Recipe_Page)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

More work on media queries and responsive styling. Also more of guessing the measurements.

```css
@media screen and (max-width: 480px) {
  .recipe {
    padding: 0px 40px 40px 40px;
    width: min(700px, calc(100vw - 80px));
    margin-top: 0;
    border-radius: 0;
  }

  .recipe img {
    width: 100vw;
    margin-left: -20px;
    border-radius: 0;
  }

  body {
    background-color: var(--white);
  }

  h1 {
    font-size: 32px;
  }
}
```
