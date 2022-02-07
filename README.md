# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![desktop screenshot of my QR-code solution](.solution_Screenshots/desktop-screenshot.png)
![mobile screenshot of my QR-code solution](.solution_Screenshots/mobile-screenshot.jpg)

### Links

- Solution URL: [https://github.com/darmijo15/qr-code-component-main/](https://github.com/darmijo15/qr-code-component-main/)
- Live Site URL: [https://darmijo15.github.io/qr-code-component-main/](https://darmijo15.github.io/qr-code-component-main/)

## My process

### Built with

- HTML5 markup
- CSS
- Flexbox

### What I learned

One aspect that gave me some trouble was figuring out how to include the attribution on my webpage without it displaying in my solution screenshot. The solution to this problem was to create a div with the class name "body" and insert the html structure into this div while placing the attribution-div outside of the body-div.

```html
<body>
  <div class="body">HTML structure for my solution</div>
  <div class="attribution">
    Attribution giving credit to FrontendMentor for designing the challenge.
  </div>
</body>
```

I then applied all of the body styling to the body-div rather than the body tag. Using a height of 100vh, this resulted in my solution occupying the entire height of the viewport with room to scroll down to see the attribution tag.

```css
body {
  margin: 0;
}
.body {
  height: 100vh;
  display: flex;
  flex-flow: column wrap;
  justify-content: center;
  align-items: center;
}
```

This provides yet another way for me to place/style footers in future webpages I design.

## Author

- GitHub - [Daniel Armijo](https://github.com/darmijo15/)
- Frontend Mentor - [@darmijo15](https://www.frontendmentor.io/profile/darmijo15)

## Acknowledgments

Special thanks to [Walter Sono](https://www.frontendmentor.io/profile/waltersono) for [suggesting the footer-solution](https://www.frontendmentor.io/solutions/flexbox-solution-8LbxpifYr) on a previous post!
