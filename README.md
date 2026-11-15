# CSS Infinite Scroll Animation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-infinite-scroll-animation/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable recreation of the 11.13-second supplied video.

## Run
1. Extract the ZIP.
2. Open `index.html` in a browser.
3. The image strip scrolls continuously from right to left.
4. Hover over the gallery to pause the animation.

No JavaScript or build tools are required. The animation is pure HTML and CSS.

## Video-derived CSS details
The recording visibly shows these source declarations:
- `.scroll-container`: `overflow: hidden`, `width: 100%`, `padding: 20px 0`, `position: relative`
- `.scroll-content`: `display: flex`, `gap: 16px`, `padding-right: 24px`, `width: max-content`, `animation: scroll-left 25s linear infinite`
- `.item`: `flex-shrink: 0`, `width: 150px`, `aspect-ratio: 2 / 1`, `border-radius: 14px`, `overflow: hidden`
- `.item img`: full width/height, `object-fit: cover`, `object-position: center`, `display: block`
- Hover: pause the scrolling animation; item scales to `1.04` and border color changes
- `@keyframes scroll-left`: translate from `0` to `-50%`

The video does not show every line of the original HTML and CSS at readable resolution. The project preserves the legible CSS values and reconstructs the remaining markup. The sample photos load from Unsplash, so an internet connection is needed to display them; the CSS animation itself works offline.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
