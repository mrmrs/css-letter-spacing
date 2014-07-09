# CSS LETTER SPACING

  Mobile-first classes for css-letter-spacing.
  Set the desired css-letter-spacing on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-letter-spacing
```
or download the css on github and include in your project.

## File Size


## The Code
```
.tracked       { letter-spacing:  .1em; }
.tracked-tight { letter-spacing: -.1em; }
.mega-tracked  { letter-spacing:  .2em; }

@include break(not-small) {
  .tracked-ns       { letter-spacing:  .1em; }
  .tracked-tight-ns { letter-spacing: -.1em; }
  .mega-tracked-ns  { letter-spacing:  .2em; }
}

@include break(medium) {
  .tracked-m       { letter-spacing:  .1em; }
  .tracked-tight-m { letter-spacing: -.1em; }
  .mega-tracked-m  { letter-spacing:  .2em; }
}

@include break(large) {
  .tracked-l       { letter-spacing:  .1em; }
  .tracked-tight-l { letter-spacing: -.1em; }
  .mega-tracked-l  { letter-spacing:  .2em; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

