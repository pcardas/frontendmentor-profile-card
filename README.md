# Frontend Mentor - Profile Card Component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).
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

## Overview

### The challenge

- Build a Profile Card Component project using the designs provided on the design folder, which contains:
  - Desktop Design
  - Desktop Preview
  - Mobile Design

### Screenshot

- [Desktop Preview](my-solution/desktop-solution.png)
- [Mobile Preview](my-solution/mobile-solution.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/1st-project-replicated-the-design-using-html-and-css-G9oeFOPNH)
- [Live Site URL](https://pcardas.github.io/frontendmentor-profile-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

It was not easy at first to set up this component, since I am new with building these components, but overall there was 1 key point which helped me out when moving up to CSS:

- Dividing HTML in 3 main parts:

```html
<div class="card-header"></div>
<div class="card-body"></div>
<div class="card-footer"></div>
```

Also, setting up the background was a pretty nice challenge. I learned more about background properties (background-image / background-repeat / background-size / background-position)

- Setting up the background:

```css
body {
  background: var(--cyan);
  background-image: url(images/bg-pattern-top.svg),
    url(images/bg-pattern-bottom.svg);
  background-repeat: no-repeat;
  background-size: contain;
  background-position: right 50vw bottom 42vh, left 46vw top 55vh;
}
```

### Continued development

Important points that I need to develop:

- Responsiveness;
- Positioning (specially with backgrounds and images)
- Nomenclature (mainly when naming classes)

### Useful resources

- [Stack Overflow](https://stackoverflow.com/) - This was my first "help line", where I got pretty nice explanations from other developers.
- [CSS Tricks](https://css-tricks.com/) - Helpful guides. On this project, it helped a lot with flex properties.
- [W3Schools](https://www.w3schools.com/) - Very nice resources. A lot of utility when comparing with other methods.

## Author

- Website - On development... Still need to grasp more concepts
- Frontend Mentor - [@pcardas](https://www.frontendmentor.io/profile/pcardas)
- Twitter - [@pcardas](https://www.twitter.com/__pcardas__)
- Codewars - [@pcardas](https://www.codewars.com/users/__pcardas__)
