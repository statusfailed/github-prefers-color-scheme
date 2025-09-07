# GitHub prefers-color-scheme Demo

This repository demonstrates how SVGs can adapt to GitHub's light and dark themes using CSS `prefers-color-scheme` media queries.

## Dynamic SVG Example

The SVG below automatically changes color based on your GitHub theme preference:

![Dynamic CatGrad Logo](catgrad.svg)

- **Light mode**: Shows black text/graphics
- **Dark mode**: Shows white text/graphics

## How it works

The SVG uses CSS media queries within its `<style>` section:

```css
.st0{fill:#000000;}
@media (prefers-color-scheme: dark) {
    .st0{fill:#FFFFFF;}
}
```

This technique allows the same SVG file to display appropriately in both light and dark themes without requiring separate files or JavaScript.
