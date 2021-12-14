# Vertical Slider

## Table of contents

- [Overview](#overview)
  - [About](#About)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### About

Users should be able to slide the image and its description vertically .


### Screenshot

![](./images/img1.png)
![](./images/img2.png)

### Links

- Solution URL: [https://github.com/NandodkarAmogh/JavaScript-Weight-Converter](https://github.com/NandodkarAmogh/JavaScript-Weight-Converter)
- Live Site URL: [https://vanilla-js-weight-converter.netlify.app/](https://vanilla-js-weight-converter.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- JavaScript

### What I learned

I learned to use JavaScript event listeners and DOM manipulation.

```js
document.getElementById('lbsInput').addEventListener('input', (e) => {
    document.getElementById('output').style.visibility = 'visible';
    let lbs = e.target.value;
    document.getElementById('gramsOutput').innerHTML=lbs/0.0022046;
    document.getElementById('kgOutput').innerHTML=lbs/2.2046;
    document.getElementById('ouncesOutput').innerHTML=lbs*16;
})
```

## Author

- Live Site - [Amogh Nandodkar](https://amoghnandodkar.netlify.app/)
- GitHub -  [Amogh Nandodkar](https://github.com/NandodkarAmogh)


