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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot Solution](https://raw.githubusercontent.com/jimmy-20/FM-NFT_Card/master/design/Solution%20NFT.png)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Position

Starting with a "Mobile First" workflow, I started with the layout of the HTML and consequently, naming the classes with the BEM methodology.

After the layout, create a CSS style where I declare the variables with:

- Family: [Outfit](https://fonts.google.com/specimen/Outfit)
- Weights: 300, 400, 600

```
:root{
    --soft-blue: hsl(215,51%,70%);
    --cyan: hsl(178,100%,50%);
    --cyan-opacity:rgba(6, 222, 255, 0.515);

    --very-dark-blue-bg:hsl(217,54%,11%);
    --very-dark-blue-card: hsl(216,50%,16%);
    --very-dark-blue-line: hsl(215,32%,27%);
    --white: hsl(0,0%,100%);

    --font:'Outfit';
    --size-normal:18px;
    --sm:300;
    --nm:400;
    --lg:600;
}
```

Adding the corresponding styles to each element, and using the defined variables, leaving my proposal to the problem as a result.

### What I learned
The problem that stressed me the most is how to make the focus effect on the image, since when placing the "background-color" to the container it was not applied, because an image already existed, therefore, using "before" and adjusting the size to 100% I was able to achieve the effect that cost me so much,
the same result can also be achieved using div inside the container but it would only lead to dirty code if you compare it with this solution
or for yourself when you look back on this project in the future.**

![Screenshot Solution](https://raw.githubusercontent.com/jimmy-20/FM-NFT_Card/master/design/focus-image.png)
## Author

- Frontend Mentor - [@jimmy-20](https://www.frontendmentor.io/profile/jimmy-20)


