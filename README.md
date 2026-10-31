# Frontend Mentor - QR Code Component

This is my solution to the [QR Code Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). The project focuses on semantic HTML, responsive CSS, and a simple, reusable layout structure.

## Overview

### The challenge

Build a QR code card that closely matches the supplied design and remains usable across mobile and desktop viewport sizes.

### Screenshot

Add a screenshot of the completed project here, for example:

```md
![Screenshot of the QR code component](./screenshot.png)
```

### Links

- **Live site (current):** https://luminalcollective.github.io/frontend-mentor/
- **Repository (current):** https://github.com/luminalcollective/frontend-mentor

> **Planned rename:** `frontend-mentor-qrcode`. After renaming the repository and confirming GitHub Pages deployment, update the links above to `https://github.com/luminalcollective/frontend-mentor-qrcode` and `https://luminalcollective.github.io/frontend-mentor-qrcode/`.

## My process

### Built with

- Semantic HTML5
- CSS custom properties for design tokens
- CSS Grid for centring the card
- Intrinsically responsive container sizing with `min()` and `calc()`
- Relative units (`rem`) and logical properties
- Google Fonts — Outfit
- Accessible focus styles

### What I learned

This challenge helped me practise separating layout responsibilities:

- `.page-layout` centres the content within the available viewport.
- `.container` limits the content width and maintains horizontal gutters.
- `.card` controls the component's background, padding, border radius, and shadow.

I also learned that responsive design does not always require media queries. A fluid container and naturally flowing content can adapt to different screen widths without changing the layout at a breakpoint.

### Continued development

I want to improve my skills in semantic HTML, the CSS box model, reusable container classes, Flexbox, Grid, accessible interaction states, and responsive design. Future Frontend Mentor challenges will help me apply these foundations to more complex page layouts.

### Useful resources

- [MDN — CSS box sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
- [MDN — CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout)
- [MDN — CSS values and units](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Values_and_units)
- [Frontend Mentor](https://www.frontendmentor.io/)

## Author

- GitHub — [@luminalcollective](https://github.com/luminalcollective)

## Acknowledgments

Challenge design and assets provided by [Frontend Mentor](https://www.frontendmentor.io/).
