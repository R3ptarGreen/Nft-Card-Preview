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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot-NFT%20Preview%20Card.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned how to make a cool hover on a image, below I show you what I did:

```css
.nft{
    display: flex;
    width: 100%;
    height: 307px;
    border-radius: 10px;
    position: relative;
    cursor: pointer;
} 
.view{
    position: absolute;
    width: 100%;
    height: 100%;
    text-align: center;
    padding-top: 45%;
    background: hsl(178, 100%, 50%, 0.3);
    border-radius: 10px;
    transition: all 1s ease;
    opacity: 0;
    visibility: hidden;
}
.nft:hover > .view{
    opacity: 1;
    visibility: visible;
}
.nft-img img{
    width: 100%;
    height: 100%;
    border-radius: 10px;
    position: absolute;
    transition: all 1s ease;
}
```

### Continued development

I would like improve more my css skills especially on grid display and animations with images

### Useful resources

- [Overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This helped me a lot how to make the overlay for the image. I really liked this page

## Author

- Frontend Mentor - [@R3ptarGreen](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

I'm studying by myself in FreeCodeCamp and I'm improving my skills with Frontend Mentor
