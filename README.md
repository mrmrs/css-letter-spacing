# css-letter-spacing 0.0.6

Css module of single purpose classes for letter spacing

#### Stats

195 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-letter-spacing
```

#### With Git

```
git clone https://github.com/tachyons-css/css-letter-spacing
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-letter-spacing";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-letter-spacing">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   LETTER SPACING
*/
.tracked { letter-spacing: .1em; }
.tracked-tight { letter-spacing: -.1em; }
.mega-tracked { letter-spacing: .2em; }
@media screen and (min-width: 48em) {
 .tracked-ns { letter-spacing: .1em; }
 .tracked-tight-ns { letter-spacing: -.1em; }
 .mega-tracked-ns { letter-spacing: .2em; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .tracked-m { letter-spacing: .1em; }
 .tracked-tight-m { letter-spacing: -.1em; }
 .mega-tracked-m { letter-spacing: .2em; }
}
@media screen and (min-width: 64em) {
 .tracked-l { letter-spacing: .1em; }
 .tracked-tight-l { letter-spacing: -.1em; }
 .mega-tracked-l { letter-spacing: .2em; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

