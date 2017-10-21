# svg-blobs
SVG animation tests with [svg.js](http://svgjs.com) framework

### So, what the heck is in here?

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob1.html" target="_blank">Example 1</a>:** animating SVG "blob" shapes by morphing two different shapes drawn with bezier curves. SVG data was imported from <a href="http://www.dlab.nyc/testlab/svg-blobs/img/blob1.svg" target="_blank">this file</a> generated in Adobe Illustrator and created in various layers. The layer names are referenced in this code which can be easily referenced for various operations. This example also provides a simple click event handler.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob2.html" target="_blank">Example 2</a>:** expands on previous example. This example adds targeting for multiple elements within a single SVG, and includes more goodies in the event handlers.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob2-easing.html" target="_blank">Example 2b</a>:** adds easing to animations.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob3.html" target="_blank">Example 3</a>:** adds support for multi-step animations and transforms.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob4.html" target="_blank">Example 4</a>:** feeble, yet notable attempt to reference SVG data from a customized JSON data structure, which may include additional objects, such as flags for tracking object state, etc. However might make more sense in this case to simply reference the data from external SVG file.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/lavalamp.html" target="_blank">Lava Lamp</a>:** Here's the first "practical" application of all this nonsense which, ironically, is even more nonsensical. A clipping path is introduced here to "contain" the blobs into a neat little lava lamp shape!

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob5.html" target="_blank">Example 5</a>:** *(Work in progress)* Adds capability to reference data from external SVG file. Getting tripped up on how best to reference the actual elements within the code and looking for the cleanest solution (that the framework clearly provides!) 

**More to come...**

