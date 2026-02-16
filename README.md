# css-white-space

Functional CSS for white-space

## Filesize

| File | Size |
|------|------|
| `dist/white-space.css` | 1597 bytes |
| `dist/white-space.min.css` | 1151 bytes (237 Gzipped) |

## Install

```sh
npm install css-white-space
```

## Usage

### Import

```css
@import "css-white-space";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-white-space/dist/white-space.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-white-space/dist/white-space.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ws-normal` | `white-space: normal;` |
| `.ws-nowrap` | `white-space: nowrap;` |
| `.ws-pre` | `white-space: pre;` |
| `.ws-prewrap` | `white-space: pre-wrap;` |
| `.ws-preline` | `white-space: pre-line;` |
| `.ws-wrap` | `white-space: wrap;` |
| `.ws-collapse` | `white-space: collapse;` |
| `.ws-preserve` | `white-space: preserve nowrap;` |
| `.ws-normal-s` | `white-space: normal;` |
| `.ws-nowrap-s` | `white-space: nowrap;` |
| `.ws-pre-s` | `white-space: pre;` |
| `.ws-prewrap-s` | `white-space: pre-wrap;` |
| `.ws-preline-s` | `white-space: pre-line;` |
| `.ws-wrap-s` | `white-space: wrap;` |
| `.ws-collapse-s` | `white-space: collapse;` |
| `.ws-preserve-s` | `white-space: preserve nowrap;` |
| `.ws-normal-m` | `white-space: normal;` |
| `.ws-nowrap-m` | `white-space: nowrap;` |
| `.ws-pre-m` | `white-space: pre;` |
| `.ws-prewrap-m` | `white-space: pre-wrap;` |
| `.ws-preline-m` | `white-space: pre-line;` |
| `.ws-wrap-m` | `white-space: wrap;` |
| `.ws-collapse-m` | `white-space: collapse;` |
| `.ws-preserve-m` | `white-space: preserve nowrap;` |
| `.ws-normal-l` | `white-space: normal;` |
| `.ws-nowrap-l` | `white-space: nowrap;` |
| `.ws-pre-l` | `white-space: pre;` |
| `.ws-prewrap-l` | `white-space: pre-wrap;` |
| `.ws-preline-l` | `white-space: pre-line;` |
| `.ws-wrap-l` | `white-space: wrap;` |
| `.ws-collapse-l` | `white-space: collapse;` |
| `.ws-preserve-l` | `white-space: preserve nowrap;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ws-normal-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/white-space.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/white-space.css` — formatted
- `dist/white-space.min.css` — minified

## License

MIT
