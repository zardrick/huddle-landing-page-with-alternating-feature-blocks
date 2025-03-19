# Frontend Mentor - Huddle Landing Page with Alternating Feature Blocks Solution

This is a solution to the [Huddle Landing Page with Alternating Feature Blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Project Screenshot](./design/desktop-preview.jpg)

### Links

- Solution URL: [Github](https://github.com/zardrick/huddle-landing-page-with-alternating-feature-blocks)
- Live Site URL: [Live Site](https://zardrick.github.io/huddle-landing-page-with-alternating-feature-blocks)

## My Process

### Built With

- Semantic HTML5 markup
- SCSS (Sass) for styling
- Flexbox
- Mobile-first workflow

### What I Learned

This project helped me strengthen my understanding of SCSS and responsive design. One of the key takeaways was efficiently structuring SCSS using modular components. Below is an example of how I structured the SCSS files:

```scss
@use "base/variables" as *;
@use "base/global" as *;

.footer {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    padding: 3rem;
}
```

### Continued Development

In future projects, I plan to:

- Refine my SCSS workflow and explore more mixins for reusability
- Improve accessibility by ensuring all elements are keyboard navigable
- Implement animations for better user experience

### Useful Resources

- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Helped me resolve alignment issues in the footer.
- [MDN Web Docs - Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design) - Great reference for ensuring mobile responsiveness.

## Author

- Frontend Mentor - [@Zardrick](https://www.frontendmentor.io/profile/Zardrick)

