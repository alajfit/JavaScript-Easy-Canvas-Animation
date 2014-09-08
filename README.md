JavaScript-Easy-Canvas-Control
==============================

The allows for JavaScript canvas rotation and fps counter to be setup and used instantly

## Using the Function

Insert the code or a link anywhere on your page, it is modular and doesnt activate until all images and scripts have been loaded.

The initial variable can be set to true or false, if set to true the function will try to update an element containing the id fps, if an element is not found containing fps the fps will not be shown.

Once the code has been loaded it will attempt on each animation call to fire an 'update','render' and 'check' function from the Global scope.

If a canvas element is not found in the DOM when the page has fully loaded the animation function will not fire.
