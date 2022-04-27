# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly


### Links

- Solution URL: [Add solution URL here](https://github.com/Doileo/base-apparel)
- Live Site URL: [Add live site URL here](https://doileo.github.io/base-apparel/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- JavaScript

### What I learned
The challenge of this project was to figure out how to validate the email using JavaScript. One of the ways was to use Regex pattern to validate the email. 


```html
<form action="#">
  <div class="input-box">
      <input class="input text-desaturated fs-400" type="text" placeholder="Email Address">
      <img class="error-icon" src="./images/icon-error.png" alt="An error icon">
      <button class="btn" type="submit"><i class="fas fa-chevron-right"></i></button>
    </div>
    <p class="text"></p>
</form>
```
```js
form.addEventListener("submit", (e)=>{
    e.preventDefault();
    let pattern = /^[^ ]+@[^ ]+\.[a-z]{2,3}$/;
}
```

### Continued development

Defenitely it's a good idea to grasp more information and best practices about using the Regex pattern.

### Useful resources

- [Example resource 1](https://dev.to/codemediaweb/simple-email-validation-in-javascript-css-57i6) - This helped me for understanding how Regex pattern works. I really liked this pattern and will use it going forward.


## Author

- Website - [Doina](https://doileo.github.io/base-apparel/)
- Frontend Mentor - [@Doileo](https://www.frontendmentor.io/profile/Doileo)
- Twitter - [@DLeovchin](https://twitter.com/DLeovchin)

