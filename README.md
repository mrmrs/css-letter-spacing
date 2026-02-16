# css-letter-spacing

Functional CSS for letter-spacing

## Filesize

| File | Size |
|------|------|
| `dist/letter-spacing.css` | 689 bytes |
| `dist/letter-spacing.min.css` | 513 bytes (154 Gzipped) |

## Install

```sh
npm install css-letter-spacing
```

## Usage

### Import

```css
@import "css-letter-spacing";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-letter-spacing/dist/letter-spacing.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-letter-spacing/dist/letter-spacing.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.tracked` | `letter-spacing: .1em;` |
| `.tracked-tight` | `letter-spacing: -.1em;` |
| `.mega-tracked` | `letter-spacing: .2em;` |
| `.tracked-s` | `letter-spacing: .1em;` |
| `.tracked-tight-s` | `letter-spacing: -.1em;` |
| `.mega-tracked-s` | `letter-spacing: .2em;` |
| `.tracked-m` | `letter-spacing: .1em;` |
| `.tracked-tight-m` | `letter-spacing: -.1em;` |
| `.mega-tracked-m` | `letter-spacing: .2em;` |
| `.tracked-l` | `letter-spacing: .1em;` |
| `.tracked-tight-l` | `letter-spacing: -.1em;` |
| `.mega-tracked-l` | `letter-spacing: .2em;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.tracked-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/letter-spacing.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/letter-spacing.css` — formatted
- `dist/letter-spacing.min.css` — minified

## License

MIT
