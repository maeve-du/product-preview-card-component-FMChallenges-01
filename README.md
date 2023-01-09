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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Mobile
<img src="https://github.com/maeve-du/product-preview-card-component-FMChallenges-01/raw/master/assets/16732832218315.png" width="400px">


Desktop
<img src="https://github.com/maeve-du/product-preview-card-component-FMChallenges-01/raw/master/assets/16732826088603.png" width="800">

### Links

- Solution URL: [GitHub](https://github.com/maeve-du/product-preview-card-component-FMChallenges-01)
- Live Site URL:  [GitHub Pages](https://maeve-du.github.io/product-preview-card-component-FMChallenges-01/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

1. Learned how to set different picture resources for different device's screen sizes

    ```HTML
    <picture>
      <source srcset="./images/image-product-mobile.jpg"
              media="(max-width: 600px)">
      <img src="./images/image-product-desktop.jpg" alt="product-image" class="card__image">
    </picture>
    ```

2. Learned more about grid and flexbox

3. Use grid system to put elements in the center of a container
    ```CSS
    html,
    body {
      width: 100vw;
      height: 100vh;
      background-color: #F2EAE2;
    }
    
    main {
      width: 100%;
      height: 100%;
      display: grid;
      place-items: center;
    }
    ```
    

## Author

- Website - [@maeve-du](https://github.com/maeve-du)
- Frontend Mentor - [@maeve-du](https://www.frontendmentor.io/profile/maeve-du)
