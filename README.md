# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

### Links

- Solution URL: [Code](https://github.com/Ghost-Writer-2/Frontend_Mentor_Projects.git)
- Live Site URL: [Live Preview]( https://ghost-writer-2.github.io/Frontend_Mentor_Projects/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
While solving the QR code challenge I had problems centering the qr code image. After a little online search, I learned that images act funny in a div because we're forcing an inline element (img) inside a block element (div). I learned two ways to tackle this problem but I used the one I preferred 👇👇👇👇👇

👇 To see how you can add code snippets, see below 👇:

```html
  <div class="inner qr-code">
    <img id="qr-code" src="image-qr-code.png" alt="qr_code">
  </div>
```
```css
  .qr-code {
    margin-top: 10px;
    width: 95%;
    height: 100%;
  }

  #qr-code {
    padding: 5px;
    display: block;
    margin: auto;
    box-sizing: border-box;
    width: 100%;
    border-radius: 15px;
    object-fit: contain;
  }

```

### Continued development

I want to improve my responsive layout skills, my JavaScript knowledge and learn to use frameworks and libraries.


### Useful resources

- [freeCodeCamp](https://www.freecodecamp.org/news/how-to-center-an-image-in-a-div-css/) -  This is an amazing article which helped me finally understand how to center images in a div. I'd recommend it to anyone having problems with that.

## Author

- Frontend Mentor - [@Ghost-writer-2](https://www.frontendmentor.io/profile/Ghost-Writer-2)
