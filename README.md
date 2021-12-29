# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Responsive NFT preview card. Uses flexbox for layout,

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Desktop view @ 1920 x 927

![](./screenshot.jpg)

### Links

- Solution URL: [Github](https://github.com/intherightdirection/nft-card)
- Live Site URL: [Github Pages](https://intherightdirection.github.io/nft-card/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Tried to toggle visibility between hidden and visible on mouse hover over the hero/item image but it would not toggle to visible from hidden. I tried to start from visible just to see and it was glitchy with every mouse movement. I ended up going with just changing opulence from 0 to 1, which seems to be how others have done this as well.

I used absolute positioning for solution for first time. I have never needed it before. I tried on earlier project but went with a different method that did not require positioning. I ended up using the same method. More explanation on this below in 'useful resources'.

### Continued development

I would like to learn more about and impliment flex-grow features for more responsiveness. Perhaps I will experiment with vh for heights so the height changes viewport changes, being as this is a simple predictive layout. 

### Useful resources

- [Simple CSS Color Overlay For Background Images](https://youtu.be/uLvhAJfx3T0) - This video was useful for 2 projects and implimented something along these lines for the active state on the hero/item image.
- [MDN Web Docs: Position](https://developer.mozilla.org/en-US/docs/Web/CSS/position) - Needed to learn more about positioning.

## Author

- Website - [Github: Jared Dunlop](https://github.com/)
- Frontend Mentor - [@intherightdirection](https://www.frontendmentor.io/profile/intherightdirection)
