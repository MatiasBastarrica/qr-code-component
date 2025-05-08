# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Qr code coponent Solution](https://www.frontendmentor.io/solutions/qr-component-using-flexbox-YVzp-tyyd-)
- Live Site URL: [Qr code component Site](https://matiasbastarrica.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

One of my major learnings was the centering of an element across both vertically and horizontally. The combination of flexbox and a fixed width on the container helped me achieve this task.

In this project I wanted to keep the default attribution section that frontendmentor provides, but I realized later on in the development that this element got me into trouble when I was trying to center my qr-component. Because I was using the body as my flex-container, both the attribuiton element and the qr-component were the flex-items. This made the centering of the qr-component in the center of the viewport a difficult task because I couldn't position the attribution element at the bottom of the page. In order to solve this I decided to wrap my qr-component in a div with a class of "container" and instead of the body, this div would be my flex-container.

### Continued development

I would like to continue practice using flexbox in my future projects.

### Useful resources

- [CSS Variables - The var() Function](https://www.w3schools.com/css/css3_variables.asp) - This helped me to understand the correct use of CSS Variables.

- [HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp) - This is an amazing article which helped me finally understand HTML Semantic Elements. I'd recommend it to anyone still learning this concept, specially the chart at the bottom of page.

- [CSS box-shadow Property](https://www.w3schools.com/cssref/css3_pr_box-shadow.php) - This helped me to understand the correct use of the box-shadow property in CSS.

## Author

- Frontend Mentor - [@MatiasBastarrica](https://www.frontendmentor.io/profile/MatiasBastarrica)
