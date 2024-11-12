# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

[Add your screenshot here]

### Links

- Solution URL: [Add your GitHub repo URL]
- Live Site URL: [Add your live site URL]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid for nutrition layout
- Mobile-first workflow
- Custom CSS normalize
- Responsive design principles
- CSS counters for ordered lists
- Google Fonts (Young Serif & Outfit)

### What I learned

- Creating a color system using CSS variables

```
:root {
--rose-800: #7a284e;
}
```

- Custom ordered list styling with CSS counters

`ol li::before { content: counter(list-counter) "."; counter-increment: list-counter; }`

### Useful resources

- [CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - Helped with color system implementation
- [CSS Counters](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Counter_Styles/Using_CSS_counters) - Used for custom ordered list numbers
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Helpful for nutrition grid layout

### Continued development

I want to continue refining my design systems application within CSS - learning semantic styling for fonts, spacing, colors, etc.

## Author

- Website - [Galo Naranjo](https://github.com/galonaranjo)
- Frontend Mentor - [@galonaranjo](https://www.frontendmentor.io/profile/galonaranjo)
- Twitter - [@galonaranjo\_](https://www.twitter.com/galonaranjo_)
