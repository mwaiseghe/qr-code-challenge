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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

#### Web View

![Final Output](/images/desktop.png)

#### Mobile View

![Mobile View](/images/mobile.png)

### Built with

- Vanilla CSS

### What I learned

Learn't a lot, centring a div is the most and the use of media queries for resposive design

```html
<h1>Some HTML code I'm proud of</h1>
```

```css

/* Responsiveness */
@media only screen and (max-width:600px){  
    .card {
        background-color: white;
        border-radius: 5%;
        padding: 10px;
        margin: auto;
        width: 85%;
    }

    .card-text {
        text-align: center;
        font-size: 24px;
        padding-left: 30px;
        padding-right: 30px;
   }

    .qr-container {
        background-color: hsl(212, 45%, 89%);
        padding: 15vh 5px 20% 10px;
    }

    #qr-bold-text {
        font-weight: bold;
        font-size: 24px;
    }
}
```

```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

### Continued development

### Useful resources

- [W3Schools](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)

## Author

- Website - [Gift Mwaiseghe](https://itsregalo.github.io/)
- Frontend Mentor - [@mwaiseghe](https://www.frontendmentor.io/profile/mwaiseghe)
- Twitter - [@itsregalo](https://www.twitter.com/itsregalo)


## Acknowledgments

I acknowledge the TheJitu and all of my fellow trainees cohort 17 for phsyching me up into this
