# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://rafaeltakano.github.io/frontendmentor-qr-code-component-main/](https://rafaeltakano.github.io/frontendmentor-nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to properly do an image overlay, I still think it looks a little
bit 'hacky' but it's backed by W3Schools.

```css
.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: 0.3s ease;
  background-color: red;
}

.container:hover .overlay {
  opacity: 1;
}

.icon {
  color: white;
  font-size: 100px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}
```

## Author

- LinkedIn - [Rafael Takano](https://www.linkedin.com/in/rafaeltakano1/)
- Frontend Mentor - [@rafaeltakano](https://www.frontendmentor.io/profile/rafaeltakano)
