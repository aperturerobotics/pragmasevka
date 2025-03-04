# @aptre/pragmasevka

[![npm version](https://img.shields.io/npm/v/@aptre/pragmasevka.svg)](https://www.npmjs.com/package/@aptre/pragmasevka)
[![license](https://img.shields.io/badge/license-OFL--1.1-blue.svg)](https://github.com/aperturerobotics/pragmasevka/blob/main/LICENSE)

A modern, condensed monospace font with increased x-height, optimized for code and terminal use.

This package provides an easy way to include the Pragmasevka font in your web projects. The font is based on [Iosevka](https://github.com/be5invis/Iosevka) and is available from the [upstream repository](https://github.com/shytikov/pragmasevka/).

![Comparison with PragmataPro](https://github.com/shytikov/pragmasevka/blob/main/sample.png?raw=true)
*Comparison with PragmataPro (black, image from [Wikipedia](https://en.wikipedia.org/wiki/PragmataPro))*

## Installation

```bash
# npm
npm install @aptre/pragmasevka

# yarn
yarn add @aptre/pragmasevka

# pnpm
pnpm add @aptre/pragmasevka
```

## Usage

```js
// Import in JS/TS
import '@aptre/pragmasevka';
```

```css
@import "@aptre/pragmasevka/font.css";

/* Use in CSS */
font-family: 'Pragmasevka', monospace;
```

## Features

Pragmasevka is a customized build of Iosevka with the following improvements:

- **Adjusted x-height** for better readability
- **Optimized line height** for dense code display
- **Refined weight** for both regular and bold variants
- **Enhanced punctuation marks** for better code scanning
- **Carefully selected programming ligatures**
- **Condensed design** that maximizes screen real estate

## Included Font Variants

This package includes:
- Regular
- Bold
- Bold Italic

## Font Files

The font files are included in this package. If you need the original font files directly, you can download them from the [upstream repository](https://github.com/shytikov/pragmasevka/).

## Browser Support

The package uses WOFF2 format which is supported in all modern browsers.

## Related Fonts

- [NRK-Mono](https://github.com/N-R-K/NRK-Mono) - A condensed variant based on JetBrains Mono
- [Iosvmata](https://github.com/N-R-K/Iosvmata) - A more extended version of Pragmasevka

## License

This package is licensed under the [SIL Open Font License 1.1 (OFL-1.1)](https://scripts.sil.org/OFL).

Original font created by Renzhi Li (aka. Belleve Invis, belleve@typeof.net).

Pragmasevka variant created by [Alexey Shytikov](https://github.com/shytikov).
