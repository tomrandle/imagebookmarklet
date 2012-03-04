This is my attempt at recreating the Pinterest bookmarklet. It detects all the inline and background images on a page over a certain size and overlays them in a grid. Each picture links to the original file. 

To get it to work add a bookmark to your browser and set the address to be:

     javascript:(function(){var s = document.createElement('script');s.src = 'http://dl.dropbox.com/u/5045906/imagesbookmarklet/bookmarklet.js';document.body.appendChild(s);})();

If you wish to edit your own version of the bookmarklet you'll have to change this location and that of the css file. 