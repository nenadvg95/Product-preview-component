# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview
This is a product preview card component challenge from Frontend mentor  https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub
### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process
I divided container into two divs and tried to use classes in order to write less css and less repeat myself in order to achieve layout on the right side of the card.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
I learned how to use media querry in order to change the picture on different screen sizes as follows:
@media(min-width:600px){
    .container{
        grid-template-columns: 1fr 1fr;
    }
    .image-container img{
        content: url(./images/image-product-desktop.jpg);
    }
}


## Author
https://github.com/nenadvg95?tab=repositories my github page

