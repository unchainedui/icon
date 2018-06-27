# Unchained UI

## Icon

[![NPM Version](https://img.shields.io/npm/v/uc-icon.svg?style=flat-square)](https://www.npmjs.com/package/uc-icon)
[![NPM Downloads](https://img.shields.io/npm/dt/uc-icon.svg?style=flat-square)](https://www.npmjs.com/package/uc-icon)

SVG icon UI component

### Usage

```js
import icon from 'uc-icon'

console.log(icon('user'));
// <svg><use xlink:href="#icon-user"></use></svg>

```

### Icons

1. Define icons:

```html
<svg xmlns="http://www.w3.org/2000/svg" class="svg-icons">
  <symbol id="icon-user" viewBox="0 0 40 40"><path d="M.71.71l40 40m-40 0l40-40" /></symbol>
</svg>
```

2. Hide this SVG `display:none`.
3. Use icons. Define icons size and colors in the css.

License MIT

© velocityzen

