# Info

This is my attempt at recreating the Pinterest bookmarklet. It detects all the inline and background images on a page over a certain size and overlays them in a grid. Each picture links to the original file. 

To get it to work add a bookmark to your browser and set the address to be:

     javascript:(function(){var s = document.createElement('script');s.src = 'http://dl.dropbox.com/u/5045906/imagesbookmarklet/bookmarklet.js';document.body.appendChild(s);})();

If you wish to edit your own version of the bookmarklet you'll have to change this location and that of the css file.

# License

Copyright (C) 2012 Tom Randle

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


