# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![](./images/desktop_top.png)
![](./images/desktop_btm.png)
![](./images/mobile.png)


### Links

- Solution URL: [Github](https://github.com/AlejandroLaLoggia/fylo-landing-page-with-two-column)
- Live Site URL: [Github page](https://alejandrolaloggia.github.io/fylo-landing-page-with-two-column/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS grid
- Mobile-first workflow
- Figma


### What I learned

I put into practice the hover media query to detect mobile devices and it doesn't generate problems.

```css
@media (hover: hover) {

    .btn:hover {
        background-color: hsl(224, 87%, 70%);
        
    }

    .section_2_link:hover,
    .section_2_link:hover::after
    {
        color: hsl(170, 64%, 60%);
    }
    
    .link_section_2_container:hover{
        border-bottom:2px solid hsl(170, 64%, 60%);
    }

}
```

### Useful resources

- [Dorian Desings](https://www.youtube.com/watch?v=T6tQbmQ0Rws) - video tutorial on the use of hover media query.
- [mozilla.org](https://developer.mozilla.org/es/docs/Web/CSS/@media/hover) - official documentation
- [mozilla.org](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas) - CSS grid-area official documentation 

## Author

- Github - [@AlejandroLaLoggia](https://github.com/AlejandroLaLoggia)
- Frontend Mentor - [@AlejandroLaLoggia](https://www.frontendmentor.io/profile/AlejandroLaLoggia)
