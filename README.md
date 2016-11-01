# css-letter-spacing 1.0.6

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

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-letter-spacing
```

ssh:
```
git clone git@github.com:tachyons-css/css-letter-spacing.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-letter-spacing";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-letter-spacing@1.0.6/css/css-letter-spacing.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-letter-spacing">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

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

ISC

