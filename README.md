# fractal-sets-explorer

_Julia and Mandelbrot sets generated in HTML5 canvas._

_Small Fractal Exporer_  is a simple Manderbrot set and Julia set generator.
You can just click on the right side of the screen (in Mandelbrot set complex
plane) to choose a start seed. The start seed point is value from the
Mandelbrot set which is used for Julia set computation. When the point lies
inside the Mandelbrot set, the Julia set is connected. Otherwise, the Julia set
is a Cantor dust of unconnected points. The result is a wonderful pictures!

>
> [Run it in browser.](https://cdn.rawgit.com/BruXy/fractal-sets-explorer/master/index.html)
>

I've create similar
[project](http://bruxy.regnet.cz/web/programming/EN/small-fractal-explorer/) a
long time ago in C and SDL library to run in XWindows. I decided to rewrite it
into JavaScritpt with using HTML5 canvas.

