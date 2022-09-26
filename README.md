# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [Check Solution Code Here](https://github.com/youssefmagdy21/frontendmentor-qr-code-component)
<!-- - Live Site URL: [Add live site URL here](https://your-live-site-url.com) -->

## My process

### Built with

- HTML
- CSS

### What I learned

I used the flexbox method to center a div _vertically and horizontally_

```html
<div class="center-container">
  <div class="qr-card-container"></div>
</div>
```

```css
.center-container {
  width: 100%;
  height: inherit; /*inherit body height which is set to 100% to fell the whole page*/
  display: flex;
  justify-content: center;
  align-items: center;
}
.qr-card-container {
  background-color: hsl(0, 0%, 100%);
  width: 250px;
}
```

### Useful resources

- [Center Div CSS](https://blog.hubspot.com/website/center-div-css) - This helped me for centering the div. It's really helpful as it shows many methods to center elements in html/css
- [Box Shadow](https://www.w3schools.com/cssref/css3_pr_box-shadow.asp) - This helped me review how to add a box-shadow to an element.

## Author

- GitHub - [Youssef Magdy](https://github.com/youssefmagdy21/)
- Frontend Mentor - [@youssefmagdy21](https://www.frontendmentor.io/profile/youssefmagdy21)
