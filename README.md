# CSS BORDER STYLE

  Mobile-first classes for css-border-style.
  Set the desired css-border-style on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-border-style
```
View on [npm](https://www.npmjs.org/package/css-border-style)


## File Size

8.8K border-style.css
7.2K border-style.min.css
895B minified and gzipped

## The Code
```
.ba-none {   border-style: none; }
.ba-hidden { border-style: hidden; }
.ba-dotted { border-style: dotted; }
.ba-dashed { border-style: dashed; }
.ba-solid {  border-style: solid; }
.ba-double { border-style: double; }
.ba-groove { border-style: groove; }
.ba-ridge {  border-style: ridge; }
.ba-inset {  border-style: inset; }
.ba-outset { border-style: outset; }

.bt-none {   border-top-style: none; }
.bt-hidden { border-top-style: hidden; }
.bt-dotted { border-top-style: dotted; }
.bt-dashed { border-top-style: dashed; }
.bt-solid {  border-top-style: solid; }
.bt-double { border-top-style: double; }
.bt-groove { border-top-style: groove; }
.bt-ridge {  border-top-style: ridge; }
.bt-inset {  border-top-style: inset; }
.bt-outset { border-top-style: outset; }

.bb-none {   border-bottom-style: none; }
.bb-hidden { border-bottom-style: hidden; }
.bb-dotted { border-bottom-style: dotted; }
.bb-dashed { border-bottom-style: dashed; }
.bb-solid {  border-bottom-style: solid; }
.bb-double { border-bottom-style: double; }
.bb-groove { border-bottom-style: groove; }
.bb-ridge {  border-bottom-style: ridge; }
.bb-inset {  border-bottom-style: inset; }
.bb-outset { border-bottom-style: outset; }

.bl-none {   border-left-style: none; }
.bl-hidden { border-left-style: hidden; }
.bl-dotted { border-left-style: dotted; }
.bl-dashed { border-left-style: dashed; }
.bl-solid {  border-left-style: solid; }
.bl-double { border-left-style: double; }
.bl-groove { border-left-style: groove; }
.bl-ridge {  border-left-style: ridge; }
.bl-inset {  border-left-style: inset; }
.bl-outset { border-left-style: outset; }

.br-none {   border-right-style: none; }
.br-hidden { border-right-style: hidden; }
.br-dotted { border-right-style: dotted; }
.br-dashed { border-right-style: dashed; }
.br-solid {  border-right-style: solid; }
.br-double { border-right-style: double; }
.br-groove { border-right-style: groove; }
.br-ridge {  border-right-style: ridge; }
.br-inset {  border-right-style: inset; }
.br-outset { border-right-style: outset; }

@media screen and (min-width: 48em) {
  .ba-none-ns {   border-style: none; }
  .ba-hidden-ns { border-style: hidden; }
  .ba-dotted-ns { border-style: dotted; }
  .ba-dashed-ns { border-style: dashed; }
  .ba-solid-ns {  border-style: solid; }
  .ba-double-ns { border-style: double; }
  .ba-groove-ns { border-style: groove; }
  .ba-ridge-ns {  border-style: ridge; }
  .ba-inset-ns {  border-style: inset; }
  .ba-outset-ns { border-style: outset; }

  .bt-none-ns {   border-top-style: none; }
  .bt-hidden-ns { border-top-style: hidden; }
  .bt-dotted-ns { border-top-style: dotted; }
  .bt-dashed-ns { border-top-style: dashed; }
  .bt-solid-ns {  border-top-style: solid; }
  .bt-double-ns { border-top-style: double; }
  .bt-groove-ns { border-top-style: groove; }
  .bt-ridge-ns {  border-top-style: ridge; }
  .bt-inset-ns {  border-top-style: inset; }
  .bt-outset-ns { border-top-style: outset; }

  .bb-none-ns {   border-bottom-style: none; }
  .bb-hidden-ns { border-bottom-style: hidden; }
  .bb-dotted-ns { border-bottom-style: dotted; }
  .bb-dashed-ns { border-bottom-style: dashed; }
  .bb-solid-ns {  border-bottom-style: solid; }
  .bb-double-ns { border-bottom-style: double; }
  .bb-groove-ns { border-bottom-style: groove; }
  .bb-ridge-ns {  border-bottom-style: ridge; }
  .bb-inset-ns {  border-bottom-style: inset; }
  .bb-outset-ns { border-bottom-style: outset; }

  .bl-none-ns {   border-left-style: none; }
  .bl-hidden-ns { border-left-style: hidden; }
  .bl-dotted-ns { border-left-style: dotted; }
  .bl-dashed-ns { border-left-style: dashed; }
  .bl-solid-ns {  border-left-style: solid; }
  .bl-double-ns { border-left-style: double; }
  .bl-groove-ns { border-left-style: groove; }
  .bl-ridge-ns {  border-left-style: ridge; }
  .bl-inset-ns {  border-left-style: inset; }
  .bl-outset-ns { border-left-style: outset; }

  .br-none-ns {   border-right-style: none; }
  .br-hidden-ns { border-right-style: hidden; }
  .br-dotted-ns { border-right-style: dotted; }
  .br-dashed-ns { border-right-style: dashed; }
  .br-solid-ns {  border-right-style: solid; }
  .br-double-ns { border-right-style: double; }
  .br-groove-ns { border-right-style: groove; }
  .br-ridge-ns {  border-right-style: ridge; }
  .br-inset-ns {  border-right-style: inset; }
  .br-outset-ns { border-right-style: outset; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .ba-none-m {   border-style: none; }
  .ba-hidden-m { border-style: hidden; }
  .ba-dotted-m { border-style: dotted; }
  .ba-dashed-m { border-style: dashed; }
  .ba-solid-m {  border-style: solid; }
  .ba-double-m { border-style: double; }
  .ba-groove-m { border-style: groove; }
  .ba-ridge-m {  border-style: ridge; }
  .ba-inset-m {  border-style: inset; }
  .ba-outset-m { border-style: outset; }
  .bt-none-m {   border-top-style: none; }
  .bt-hidden-m { border-top-style: hidden; }
  .bt-dotted-m { border-top-style: dotted; }
  .bt-dashed-m { border-top-style: dashed; }
  .bt-solid-m {  border-top-style: solid; }
  .bt-double-m { border-top-style: double; }
  .bt-groove-m { border-top-style: groove; }
  .bt-ridge-m {  border-top-style: ridge; }
  .bt-inset-m {  border-top-style: inset; }
  .bt-outset-m { border-top-style: outset; }
  .bb-none-m {   border-bottom-style: none; }
  .bb-hidden-m { border-bottom-style: hidden; }
  .bb-dotted-m { border-bottom-style: dotted; }
  .bb-dashed-m { border-bottom-style: dashed; }
  .bb-solid-m {  border-bottom-style: solid; }
  .bb-double-m { border-bottom-style: double; }
  .bb-groove-m { border-bottom-style: groove; }
  .bb-ridge-m {  border-bottom-style: ridge; }
  .bb-inset-m {  border-bottom-style: inset; }
  .bb-outset-m { border-bottom-style: outset; }
  .bl-none-m {   border-left-style: none; }
  .bl-hidden-m { border-left-style: hidden; }
  .bl-dotted-m { border-left-style: dotted; }
  .bl-dashed-m { border-left-style: dashed; }
  .bl-solid-m {  border-left-style: solid; }
  .bl-double-m { border-left-style: double; }
  .bl-groove-m { border-left-style: groove; }
  .bl-ridge-m {  border-left-style: ridge; }
  .bl-inset-m {  border-left-style: inset; }
  .bl-outset-m { border-left-style: outset; }
  .br-none-m {   border-right-style: none; }
  .br-hidden-m { border-right-style: hidden; }
  .br-dotted-m { border-right-style: dotted; }
  .br-dashed-m { border-right-style: dashed; }
  .br-solid-m {  border-right-style: solid; }
  .br-double-m { border-right-style: double; }
  .br-groove-m { border-right-style: groove; }
  .br-ridge-m {  border-right-style: ridge; }
  .br-inset-m {  border-right-style: inset; }
  .br-outset-m { border-right-style: outset; }
}

@media screen and (min-width: 64em)  {
  .ba-none-l {   border-style: none; }
  .ba-hidden-l { border-style: hidden; }
  .ba-dotted-l { border-style: dotted; }
  .ba-dashed-l { border-style: dashed; }
  .ba-solid-l {  border-style: solid; }
  .ba-double-l { border-style: double; }
  .ba-groove-l { border-style: groove; }
  .ba-ridge-l {  border-style: ridge; }
  .ba-inset-l {  border-style: inset; }
  .ba-outset-l { border-style: outset; }
  .bt-none-l {   border-top-style: none; }
  .bt-hidden-l { border-top-style: hidden; }
  .bt-dotted-l { border-top-style: dotted; }
  .bt-dashed-l { border-top-style: dashed; }
  .bt-solid-l {  border-top-style: solid; }
  .bt-double-l { border-top-style: double; }
  .bt-groove-l { border-top-style: groove; }
  .bt-ridge-l {  border-top-style: ridge; }
  .bt-inset-l {  border-top-style: inset; }
  .bt-outset-l { border-top-style: outset; }
  .bb-none-l {   border-bottom-style: none; }
  .bb-hidden-l { border-bottom-style: hidden; }
  .bb-dotted-l { border-bottom-style: dotted; }
  .bb-dashed-l { border-bottom-style: dashed; }
  .bb-solid-l {  border-bottom-style: solid; }
  .bb-double-l { border-bottom-style: double; }
  .bb-groove-l { border-bottom-style: groove; }
  .bb-ridge-l {  border-bottom-style: ridge; }
  .bb-inset-l {  border-bottom-style: inset; }
  .bb-outset-l { border-bottom-style: outset; }
  .bl-none-l {   border-left-style: none; }
  .bl-hidden-l { border-left-style: hidden; }
  .bl-dotted-l { border-left-style: dotted; }
  .bl-dashed-l { border-left-style: dashed; }
  .bl-solid-l {  border-left-style: solid; }
  .bl-double-l { border-left-style: double; }
  .bl-groove-l { border-left-style: groove; }
  .bl-ridge-l {  border-left-style: ridge; }
  .bl-inset-l {  border-left-style: inset; }
  .bl-outset-l { border-left-style: outset; }
  .br-none-l {   border-right-style: none; }
  .br-hidden-l { border-right-style: hidden; }
  .br-dotted-l { border-right-style: dotted; }
  .br-dashed-l { border-right-style: dashed; }
  .br-solid-l {  border-right-style: solid; }
  .br-double-l { border-right-style: double; }
  .br-groove-l { border-right-style: groove; }
  .br-ridge-l {  border-right-style: ridge; }
  .br-inset-l {  border-right-style: inset; }
  .br-outset-l { border-right-style: outset; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

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

