# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot


- [In Galaxy Fold](Screenshot Answer\Index-Full-Galaxy Fold.jpg)
- [In Generic Laptop](Screenshot Answer\Index-Full-Generic Laptop.jpg)
- [In iPad](Screenshot Answer\Index-Full-iPad.jpg)
- [In iPhoneX](Screenshot Answer\Index-Full-iPhoneX.jpg)
- [In Pixel2](Screenshot Answer\Index-Full-Pixel 2.jpg)
- [In MotoG4](Screenshot Answer\Index-Full-MotoG4)


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
- [Styled Components](https://styled-components.com/) - For styles
- [Responsively App](https://responsively.app/) - To check responsiveness



### What I learned

I used a rather unsual way to center my component in screens bigger than 925px.
```css
body, html {
    height: 100%;
    display: grid;
}

.container {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
}
/* And for image overlay I used */
.image-overlay {
  min-height: 30vh;
  background-color: var(--accent-color);
  background-image: url(images/image-header-mobile.jpg);
  background-blend-mode: multiply;
}
 ```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Useful resources

- [Scrimba](https://www.scrimba.com) - I've been learning Front-End dev from Scrimba and it has def helped me a lot


## Author
- Frontend Mentor - [@wolfie-09](https://www.frontendmentor.io/profile/wolfie-09)


## Acknowledgments

I'd like to thank the YouTube channels I've been watching:
 - Kevin Powell
 - Clever Programmer
 - Dev Ed
 - Wes Bos
 - Web Dev Simplified
 - Karl Hadwen
 - Brian Design

