<h1>Platform Demo</h1>
A simple platformer with very few features (so far).

<h3>Compile</h3>
To compile on a unix-like system, run <b>make.sh</b> or <b>makeDebug.sh</b>.

<h3>Controls</h3>
WASD to move, SPACE to jump.<p>
In debug, press <b>ENTER</b> to add a new platform via the command line, or <b>R</b> to remove the last added rectangle. When adding a rectangle, X and Y are 1:1px. Size is 1:50px. Ex: "X: 250 Y: 200 Size: 3" adds a rectangle with the dimensions (250, 200, 400, 220).

<h3>Requirements</h3>
Make sure to install <a href="https://liballeg.org/">Allegro</a>. On Mac OS X 10.10, you will need to manually compile and install Allegro 5.1.9<p>
<b>git clone git://git.code.sf.net/p/alleg/allegro alleg-allegro</b>
