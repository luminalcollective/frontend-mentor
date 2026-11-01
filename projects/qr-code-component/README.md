# Frontend Mentor — QR Code Component

My solution to the [QR Code Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). This project explores semantic HTML, responsive CSS, reusable layout patterns, and accessibility fundamentals.

## Overview

### The challenge

Recreate the supplied QR code card design using HTML and CSS, with a layout that remains readable and usable across mobile and desktop screen sizes.

### Screenshot

![Completed QR Code Component design](./images/qrcode-screenshot.jpeg)

### Links

- **Live demo:** [QR Code Component](https://luminalcollective.github.io/frontend-mentor/projects/qr-code-component/)
- **Source files:** [QR Code Component folder](https://github.com/luminalcollective/frontend-mentor/tree/main/projects/qr-code-component)
- **Portfolio homepage:** [Frontend Mentor Projects](https://luminalcollective.github.io/frontend-mentor/)
- **Challenge:** [Frontend Mentor — QR Code Component](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H)

## Built with

- Semantic HTML5, including `main`, `article`, headings and `footer`
- CSS custom properties for colours, typography, spacing and sizing
- Flexbox for the overall page and footer layout
- CSS Grid for centring the card
- Intrinsically responsive container sizing using `min()` and `calc()`
- Relative units (`rem`) and logical CSS properties
- Google Fonts — Outfit (400 and 700)
- Visible keyboard focus indicators and increased-contrast preference support

No JavaScript or build tools are required.

## My process

### Layout structure

I separated the page into distinct responsibilities:

- `.page-layout` uses CSS Grid to centre the component in the available page space.
- `.container` sets the maximum width while preserving horizontal gutters.
- `.card` controls the component's padding, background, rounded corners, shadow and text alignment.
- `.qr-code` keeps the image responsive and square.
- `.attribution` provides challenge credit and an author link.

The `body` uses Flexbox so the main content can expand while the attribution remains part of the overall page layout.

### What I learned

This challenge helped me understand that responsive design does not always require media queries. A fluid container and naturally wrapping content can adapt to different screen widths without changing the layout at a breakpoint.

I also learned how CSS custom properties make a stylesheet easier to maintain, why semantic HTML matters, and how visible focus indicators and text wrapping contribute to accessibility.

The supplied 375px mobile and 1440px desktop designs are reference sizes, not mandatory CSS breakpoints.

### Accessibility and testing

The implementation includes semantic landmarks, alternative text for the QR image, keyboard-visible focus styling and an increased-contrast preference adjustment.

These measures do not, by themselves, establish WCAG 2.2 AA conformance.

Further testing should include:

- Keyboard-only navigation
- Browser zoom and text resizing
- Narrow viewport testing, including 320px
- Screen-reader testing
- Automated checks using axe DevTools or Lighthouse
- Verification of the QR code destination and an accessible alternative link

## Project structure

```text
projects/qr-code-component/
├── index.html
├── README.md
├── css/
│   └── style.css
└── images/
    ├── image-qr-code.png
    ├── favicon-32x32.png
    └── qrcode-screenshot.jpeg
```

This project belongs to the [Frontend Mentor portfolio repository](https://github.com/luminalcollective/frontend-mentor). Other challenges are organised in separate folders under `projects/`.

## Continued development

I want to strengthen my understanding of the CSS box model, semantic HTML, reusable container classes, Flexbox, Grid, responsive layouts and accessibility testing.

Future Frontend Mentor challenges will help me apply these foundations to more complex interfaces.

## Useful resources

- [MDN — CSS box sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
- [MDN — CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout)
- [MDN — CSS values and units](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Values_and_units)
- [W3C — WCAG 2.2](https://www.w3.org/TR/WCAG22/)
- [Frontend Mentor](https://www.frontendmentor.io/)

## Author

- GitHub — [@luminalcollective](https://github.com/luminalcollective)

## Acknowledgments

Challenge design and assets provided by [Frontend Mentor](https://www.frontendmentor.io/).