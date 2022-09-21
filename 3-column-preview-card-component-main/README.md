# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Column-preview-desktop (2)](https://user-images.githubusercontent.com/95522156/189554221-446e30f2-399e-4966-b55b-782b1ae14276.jpeg)
![column-preview-mobile](https://user-images.githubusercontent.com/95522156/189554222-fc19cf61-9499-494d-9c4a-5255953dac1d.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Style Background
- Give elements landmarks (main, h1, p, button)
- Create/style Flexbox (3 elements)
- create Flexbox in Flexbox (column)
- Create button
- Style elements and spacing (font-family, color, hover)
- Mobile Responsiveness [@media only screen and (max-width: 500px)]


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- I can create elements without attaching height in each element, can use padding/margin instead
- Hover on a button outline
- inspecting code for non-needed elements

```css
body {
    background-color: hsl(0, 0%, 95%);
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 100vh;
}
main {
    display: flex;
    padding: 0 5em;
    border-radius: 20px;
}
div {
    display: flex;
    flex-direction: column;
    align-items: left;
    padding: 2em;
    text-align: left;
}
```

### Continued development

- Mobile Responsiveness

## Author
- Frontend Mentor - [@ablueremote](https://www.frontendmentor.io/profile/ablueremote)
- Twitter - [@ablueremote](https://www.twitter.com/ablueremote)
