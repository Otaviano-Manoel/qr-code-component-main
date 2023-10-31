# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


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

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![screen desktop](./src/images/screenshot-desktop.png)
![screen mobile](./src/images/screenshot-mobile.png)

### Links

- Solution URL: [Solution URL here](https://www.frontendmentor.io/solutions/utilizei-o-positionabsolute-para-centralizar-no-centro-da-tela-z2muDrt1yH)
- Live Site URL: [Live site URL here](https://otaviano-manoel.github.io/qr-code-position-absolute/)

## My process

### Built with

<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" alt="HTML5"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" alt="CSS"/></code>


### What I learned

I would like to highlight the way I center the panel where the QR code is using the position: absolute property, which I didn't know how to use very well.

```css
main {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
```

I learned it through DevQuest, and I really liked the outcome.

### Continued development

In my next project, I will use the `display: flex` for element alignment.

### Useful resources
- [W3Schools](https://www.w3schools.com/css/default.asp) - 
I used W3Schools to clarify my doubts and I really liked their examples, which clarify how to use CSS properties.

- [MDN Web Docs](https://developer.mozilla.org/pt-BR/) - I'd like you to get to know MDN Web Docs, which helped me a lot in understanding HTML tags.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Otaviano-Manoel)