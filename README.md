# fractal-sets-explorer

_Julia and Mandelbrot sets generated in HTML5 canvas._

_Small Fractal Exporer_  is a simple Mandelbrot set and Julia set generator.
You can just click on the right side of the screen (in Mandelbrot set complex
plane) to choose a start seed. The start seed point is a value from the
Mandelbrot set which is used for Julia set computation. When the point lies
inside the Mandelbrot set, the Julia set is connected. Otherwise, the Julia set
is a Cantor dust of unconnected points. The result is a wonderful picture!

>
> [Run it in browser.](http://htmlpreview.github.io/?https://github.com/BruXy/fractal-sets-explorer/blob/master/index.html)
>

I've created a similar
[project](http://bruxy.regnet.cz/web/programming/EN/small-fractal-explorer/) a
long time ago in C and SDL library to run in XWindows. I decided to rewrite it
into JavaScritpt using HTML5 canvas.

