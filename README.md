# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![QR Code Component Solution](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/FrankAntwi/qr-code-component)
- Live Site URL: [GitHub Pages](https://frankantwi.github.io/qr-code-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox for layout
- CSS HSL color values
- Google Fonts (Outfit family)
- Mobile-first workflow

### What I learned

During this project, I strengthened my understanding of several key CSS concepts:

**Flexbox Centering**: I learned how to properly center content both horizontally and vertically using Flexbox:

```css
body {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
```

**HSL Color System**: Working with HSL colors from the style guide helped me understand color relationships better:

```css
.main-container {
  background-color: hsl(0, 0%, 100%);
}

body {
  background-color: hsl(212, 45%, 89%);
}

h1 {
  color: hsl(218, 44%, 22%);
}
```

**Responsive Typography**: I learned to implement proper font sizing and line-height for better readability:

```css
p {
  font-size: 15px;
  line-height: 1.8;
}
```

**Spacing and Visual Hierarchy**: Understanding how to use padding and margins to create proper visual spacing and hierarchy was crucial for matching the design.

### Continued development

Areas I want to continue focusing on in future projects:

- **Responsive Design**: Implementing proper media queries for mobile-first development
- **CSS Grid**: Exploring CSS Grid for more complex layouts
- **Accessibility**: Adding proper ARIA labels and ensuring keyboard navigation
- **BEM Methodology**: Adopting better CSS naming conventions for scalability
- **CSS Variables**: Using CSS custom properties for better maintainability

## Author

- GitHub - [@FrankAntwi](https://github.com/FrankAntwi)
- Frontend Mentor - [@FrankAntwi](https://www.frontendmentor.io/profile/FrankAntwi)
