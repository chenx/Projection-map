projection-map
==============

An extendable library for drawing sky projection maps, in HTML5 canvas and Javascript. 

This is an extendable library for drawing sky or GIS projection maps in HTML5 canvas and Javascript. It allows translation/rotation/zoom of the map, can draw frames on the map and display the location of selected frames. This is useful for projects in fields such as astronomy and GIS. An example image is shown below. Click here for a <a href="http://cssauh.com/xc/projectionmap/demo2.html">demo</a>.

In the code repository, 
hammer.js, map.js and map.ie.js in the javascript folder are the projection-map library files. Demo.html, demo2.html and demo.php demonstrates how to use them. Two third party libraries are used: 1) The javascript/excanvas folder contains the <a href="http://excanvas.sourceforge.net/">excanvas</a> library that provides support for IE8.0 or below, 2) The javascript/slider folder contains the library that provides <a href="http://webfx.eae.net/dhtml/slider/implementation.html">slider</a> control on the projection map interface. 

This application is a result of work on the <a href="http://pan-starrs.ifa.hawaii.edu/public/">PanSTARRS Project</a>.

To add new projections, add the coordinate transformation functions to javascript/hammer.js, 
then follow the demo page to modify html.

<img src="http://cssauh.com/xc/projectionmap/map.png" height="400">

Author
-----
X. Chen, Larry, Conrad
