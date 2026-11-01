# Test Chat Bot

A single static HTML page used to test the Rival CortexOne embeddable chat widget.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## About

`index.html` renders a small "Hello there" card and loads the CortexOne embed script
(`https://cortexone.rival.io/embed/embed.js`), which adds the chat widget to the page.
It is a sandbox for checking that the widget loads and works on a plain host page.

## What's on the page

- A centered card with a floating accent blob and a hover lift
- Light and dark themes through `prefers-color-scheme` and CSS custom properties
- The CortexOne embed `<script>` tag, configured with `data-key` and `data-api` attributes
- A commented-out script tag pointing at the dev environment, for switching targets

## Run it

No build step and no dependencies. Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

To point the page at a different widget, change the `data-key` and `data-api`
attributes on the embed script tag.

## Author

**Aryan Bhandari**: [GitHub](https://github.com/aryanbha123)
