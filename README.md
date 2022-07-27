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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Design preview for the Product preview card component coding challenge](./design/desktop-design.jpg)
![Design preview for the Product preview card component coding challenge](./design/mobile-design.jpg)


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/product-preview-card-component-OC68nyXzy3)
- Live Site URL:(https://oshanikumarathunga.github.io/frontend-mentor-Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- @media queries


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
   box-sizing: border-box;

body{
    height: 100vh;
    background-color:  hsl(30, 38%, 92%);
    display: grid;
    place-items: center; 
}


@media only screen and (max-width:506px){
.card{
    min-width: auto;
    width: 65%;
    display: flex;
    flex-direction: column;
    border-radius: 10px;
    margin: 30px;
}
.image{
    min-width: auto;
    width: 100%;
    
}
.image img{
   content:  url(./images/image-product-mobile.jpg);
   width: 100%;
   height: 260px;
   border-radius: 10px 10px 0 0 ;

```

### Continued development

1.I want more focus on CSS Grid system,@media queries,@keyframes,transforms.
2.Moreover I want learn more about CSS styles


### Useful resources

- [Resource 1](https://www.w3schools.com/css/css3_box-sizing.asp) - This helped me for learn about box-sizing in CSS.The CSS box-sizing property allows us to include the padding and border in an element's total width and height.
- [Resource 2](https://www.w3schools.com/cssref/css3_pr_border-radius.asp) - This is an amazing article which helped me finally understand border-radius in CSS . 
- [Resource 2](https://www.youtube.com/watch?v=yU7jJ3NbPdA) - This  article helpes me to understand @media queries in CSS .


