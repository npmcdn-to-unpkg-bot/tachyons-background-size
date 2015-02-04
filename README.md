# TACHYONS-BACKGROUND-SIZE

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-background-size
```
or download the css on github and include in your project.

## The Code
```
@custom-media --breakpoint-not-small screen and (max-width: 48em);
@custom-media --breakpoint-medium screen and (min-width: 48em) and (max-width: 64em);
@custom-media --breakpoint-large screen and (min-width: 64em);

/*

   BACKGROUND SIZE

*/

  .bg-cv  {               background-size: cover; }
  .bg-cn  {               background-size: contain; }
  .bg-auto {              background-size: auto; }

@media (--breakpoint-not-small) {
  .bg-cv-ns {             background-size: cover; }
  .bg-cn-ns {             background-size: contain; }
  .bg-auto-ns {           background-size: auto; }
}

@media (--breakpoint-medium) {
  .bg-cv-m {              background-size: cover; }
  .bg-cn-m {              background-size: contain; }
  .bg-auto-m {            background-size: auto; }
}

@media (--breakpoint-large) {
  .bg-cv-l {              background-size: cover; }
  .bg-cn-l {              background-size: contain; }
  .bg-auto-l {            background-size: auto; }
}

```

## Author

[mrmrs](http://mrmrs.io)

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

