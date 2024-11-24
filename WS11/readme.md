# Learning CSS Advanced Features: Media Queries

## Introduction
This repository contains resources and examples for learning advanced CSS features, specifically focusing on media queries. Media queries are a powerful tool for creating responsive web designs that adapt to different screen sizes and devices.

## What are Media Queries?
Media queries are a CSS feature that allows you to apply styles based on the characteristics of the device or viewport, such as width, height, orientation, and resolution. They enable you to create responsive designs that look great on any device.

## Key Concepts
- **Viewport Width and Height**: Target styles based on the width and height of the viewport.
- **Orientation**: Apply styles based on the device's orientation (portrait or landscape).
- **Resolution**: Adjust styles for different screen resolutions and pixel densities.

## Examples
### Basic Media Query
```css
/* Apply styles for screens wider than 600px */
@media (min-width: 600px) {
    body {
        background-color: lightblue;
    }
}
```

### Orientation Media Query
```css
/* Apply styles for devices in landscape orientation */
@media (orientation: landscape) {
    body {
        background-color: lightgreen;
    }
}
```

### High-Resolution Media Query
```css
/* Apply styles for high-resolution screens */
@media (min-resolution: 2dppx) {
    body {
        background-color: lightcoral;
    }
}
```

## Resources
- [MDN Web Docs: Using Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)
- [W3Schools: CSS Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)

## Conclusion
Understanding and using media queries is essential for creating responsive web designs. This repository provides examples and resources to help you master this advanced CSS feature.

Happy coding!
