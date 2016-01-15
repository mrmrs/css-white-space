# css-white-space 0.0.6

Css module of single purpose classes for white space

#### Stats

226 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-white-space
```

#### With Git

```
git clone https://github.com/tachyons-css/css-white-space
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-white-space";
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
<link rel="stylesheet" href="path/to/module/css/css-white-space">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   WHITE SPACE
*/
.ws-norm { white-space: normal; }
.ws-nowrap { white-space: nowrap; }
.ws-pre { white-space: pre; }
.ws-prewrap { white-space: pre-wrap; }
.ws-preline { white-space: pre-line; }
@media screen and (min-width: 48em) {
 .ws-norm-ns { white-space: normal; }
 .ws-nowrap-ns { white-space: nowrap; }
 .ws-pre-ns { white-space: pre; }
 .ws-prewrap-ns { white-space: pre-wrap; }
 .ws-preline-ns { white-space: pre-line; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ws-norm-m { white-space: normal; }
 .ws-nowrap-m { white-space: nowrap; }
 .ws-pre-m { white-space: pre; }
 .ws-prewrap-m { white-space: pre-wrap; }
 .ws-preline-m { white-space: pre-line; }
}
@media screen and (min-width: 64em) {
 .ws-norm-l { white-space: normal; }
 .ws-nowrap-l { white-space: nowrap; }
 .ws-pre-l { white-space: pre; }
 .ws-prewrap-l { white-space: pre-wrap; }
 .ws-preline-l { white-space: pre-line; }
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

