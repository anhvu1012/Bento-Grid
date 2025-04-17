# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

#### Desktop Version

![](solutions/desktop_ver.png)

#### Mobile Version

![](solutions/mobile_sneakpeak.png)

### Links

- Solution URL: [GitHub Page](https://anhvu1012.github.io/Bento-Grid/)
- Live Site URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/bento-grid-using-sass-R4unM6l3I1)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [SASS](https://sass-lang.com/) - CSS Extension

### What I learned

I learned more about CSS Grid how to place certain element at certain position however I want.

```scss
main {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(10, 70px);

  .create-section {
    grid-area: 1 / 1 / 6 / 2;
  }

  .write-ai-content-section {
    grid-area: 6 / 1 / 11 / 2;
  }

  .review-section {
    grid-area: 1 / 2 / 5 / 4;
  }

  .media-schedule-section {
    grid-area: 1 / 4 / 8 / 5;
  }

  .platform-section {
    grid-area: 5 / 2 / 8 / 3;
  }

  .posting-schedule-section {
    grid-area: 5 / 3 / 8 / 4;
  }

  .audience-grow-section {
    grid-area: 8 / 2 / 11 / 3;
  }

  .follower-grow-section {
    grid-area: 8 / 3 / 11 / 5;
  }
}
```

## Author

- Frontend Mentor - [@anhvu1012](https://www.frontendmentor.io/profile/anhvu1012)
