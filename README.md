# Primitive UI

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![primitive-ui on NPM](https://img.shields.io/npm/v/primitive-ui.svg?color=green&label=primitive-ui)](https://www.npmjs.com/package/primitive-ui)

A minimalist front-end design toolkit built with Sass for developing responsive web apps. Primitive also provides helpful, browser-consistent styling for default HTML elements - buttons, forms, tables, lists, and typography.

### [View documentation](https://taniarascia.github.io/primitive)

## Installation

### CSS quick start (easy)

- [Download the stylesheet](https://taniarascia.github.io/primitive/css/main.css) or use the CDN URL: [https://unpkg.com/primitive-ui/dist/css/main.css](https://unpkg.com/primitive-ui/dist/css/main.css).
- Save the stylesheet and link to it in the head of your project.

```html
<link rel="stylesheet" href="https://unpkg.com/primitive-ui/dist/css/main.css" />
```

It's all set to go and your HTML elements will be given sensible default styling.

### Gulp usage
You can use gulp and customize it as well if you want

- Build CSS: `yarn gulp css`
- Watch modifications and recompile: `yarn gulp watch`

(If you don't use `yarn`, replace with `npx`)

### Sass integration (recommended)

The beauty of Primitive is the ease with which you can create unique designs in a beautiful, simple system.

```bash
# Clone the repo
git clone https://github.com/taniarascia/primitive.git

# Watch for file changes
npm run sass:watch

# Build a minified production build
npm run sass:build
```

Now you can begin modifying variables in `variables.scss`. This file will define your colors, typography, sizes, breakpoints, buttons, borders, and more. Define all your variables here to keep your project organized.

You can view `dist/test.html` or `docs/template.html` to see some example elements as you make changes.

## Acknowledgements

- Dave Gamache for building [Skeleton CSS](http://getskeleton.com/), the original inspiration for building Primitive and understanding responsive CSS.

## Contributing

Please feel free to fork, comment, critique, or submit a pull request.

## Author

- [Tania Rascia](https://www.taniarascia.com)

## License

This project is open source and available under the [MIT License](LICENSE.md).
