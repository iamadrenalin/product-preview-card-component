# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![Mobile design]: ./images/mobile-design.png
![Desktop design]: ./images/destop-design.png


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)



## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

- I learnt about the use of HTML <picture> and <soucre> tags, how to use them to switch images width media querry
- I also learnt about the use of CSS custom properties, global and local variables.

See code snippets below:
```html
 <picture class="product__image">
    <source srcset="images/image-product-desktop.jpg" media="(min-width:600px)">
    <img src="images/image-product-mobile.jpg" alt="">
  </picture>
```
```css
:root{
    --clr-primary: hsl(158, 36%, 37%);
    --ff-accent: 'Fraunces', serif;
    --fw-regular: 500;
}
```


### Continued development

In future projects, I to continue to focus on the semantic markup pattern as well as CSS grid and flex-box.


### Useful resources

- [Resource 1]: (https://youtu.be/B2WL6KkqhLQ) - This helped me in switching the mobile and desktop images just by writing less codes. I really liked this pattern and will use it going forward.


## Author

- Website - [Samuel Oluwadusi](https://www.your-site.com)
- Frontend Mentor - [@iamadrenalin](https://www.frontendmentor.io/profile/iamadrenalin)
- Twitter - [@iam_adrenalin](https://www.twitter.com/iam-adrenalin)


## Acknowledgments

All thanks Kevin Powell, his youtube channel has helped me alot in my development journey, God bless you sir.
