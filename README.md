# CSS WHITE SPACE

  Mobile-first classes for css-white-space.
  Set the desired css-white-space on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-white-space
```
View on [npm](https://www.npmjs.org/package/css-white-space)


## File Size

977B white-space.css
761B white-space.min.css

## The Code
```
.ws-norm    { white-space: normal; }
.ws-nowrap  { white-space: nowrap; }
.ws-pre     { white-space: pre; }
.ws-prewrap { white-space: pre-wrap; }
.ws-preline { white-space: pre-line; }

@media screen and (min-width: 48em) {
  .ws-norm-ns    { white-space: normal; }
  .ws-nowrap-ns  { white-space: nowrap; }
  .ws-pre-ns     { white-space: pre; }
  .ws-prewrap-ns { white-space: pre-wrap; }
  .ws-preline-ns { white-space: pre-line; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .ws-norm-m    { white-space: normal; }
  .ws-nowrap-m  { white-space: nowrap; }
  .ws-pre-m     { white-space: pre; }
  .ws-prewrap-m { white-space: pre-wrap; }
  .ws-preline-m { white-space: pre-line; }
}

@media screen and (min-width: 64em)  {
  .ws-norm-l    { white-space: normal; }
  .ws-nowrap-l  { white-space: nowrap; }
  .ws-pre-l     { white-space: pre; }
  .ws-prewrap-l { white-space: pre-wrap; }
  .ws-preline-l { white-space: pre-line; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

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

