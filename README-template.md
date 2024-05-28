# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
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

![Screenshot](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- **HTML**
  - imported the [Outfit](https://fonts.google.com/selection?query=outfit) font family from Google according to `style-guide.md`
  - added a `style.css` file to be linked to the `index.html`
  - inserted a `link` tag related to stylesheet with reference to the `style.css`
  - created a section element with a `container` class that contains a `figure` tag and two `p` tags.
  - assigned a class of `line-1` and `line-2` to each of the `p` tags accordingly.
  - created a footer tag with a class `attribution` as given by the challenger.
- **STYLING**
  - created global color and width variables
  - set margin and padding to 0
  - found the given background color hex code using a tool [imagecolorpicker](https://imagecolorpicker.com/). I had to take a snapshot and upload the screenshot.
  - used a `flex` display in the `container` class and positioned the whole container in the middle of the viewport using the `position` property.
  - preset the width of the whole container to 375px - 6em using the `calc()` function.
  - calculated a fixed width for `p` tags.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- `figure` element tag

### Continued development

- responsive design
- modular css
- pattern libraries
- transitions

### Useful resources

Book: [CSS in Depth by Keith J. Grant](https://www.manning.com/books/css-in-depth-second-edition)

## Author

- Website - [Thanos Kalaitzis](https://thanosdev.netlify.app)
- Frontend Mentor - [@Thanos-M11](https://www.frontendmentor.io/profile/Thanos-M11)
- Github - [@Thanos-M11](https://github.com/Thanos-M11)
- LinkedIn - [Thanos Kalaitzis](https://www.linkedin.com/in/thanoskalaitzis/)
