# svg-blobs
SVG animation tests with <a href="http://www.dlab.nyc/testlab/svg-blobs/blob1.html" target="_blank">svg.js</a> library

### So, what the blob is in here?

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob1.html" target="_blank">Example 1</a>:** animating SVG "blob" shapes by morphing two different shapes drawn with bezier curves. SVG data was imported from <a href="http://www.dlab.nyc/testlab/svg-blobs/img/blob1.svg" target="_blank">this file</a> generated in Adobe Illustrator and created in various layers. The layer names can be easily referenced in the code for various operations. This example also provides a simple click event handler.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob2.html" target="_blank">Example 2</a>:** adds targeting for multiple elements within a single SVG, and includes more goodies in the event handlers.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob2-easing.html" target="_blank">Example 2b</a>:** adds easing to animations with easing plug-in.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob2-pathmorphing.html" target="_blank">Example 2c</a>:** adds better morphing support pathmorphing plug-in.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob3.html" target="_blank">Example 3</a>:** adds support for multi-step animations and transforms.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob3-audio.html" target="_blank">Example 3b</a>:** adds support for event-driven audio.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob4.html" target="_blank">Example 4</a>:** feeble, yet notable attempt to reference SVG data from a customized JSON data structure, which may include additional objects, such as flags for tracking object state, etc. However might make more sense in this case to simply reference the data from external SVG file.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/lavalamp.html" target="_blank">Lava Lamp</a>:** Here's the first "practical" application of all this nonsense which, ironically, is even more nonsensical. A clipping path is introduced here to "contain" the blobs into a neat little lava lamp shape!

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob5.html" target="_blank">Example 5</a>:** Adds capability to reference data from external SVG file. 

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob5-poly.html" target="_blank">Example 5-poly</a>:** Introducing polygons to the mix! This example takes an external SVG file and morphs 2 layers containing similar polygons. 

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob5-path.html" target="_blank">Example 5-path</a>:** Same as previous example but for SVG files only containing paths. 

**<a href="http://www.dlab.nyc/testlab/svg-blobs/blob5-path-poly.html" target="_blank">Example 5-path-poly</a>:** This example combines the last two into one version that is somewhat more path/polygon agnostic. More work to be done on cleaning up the code into something much more concise, with ability to handle all kinds of shapes that may be present in a more complex SVG.

**<a href="http://www.dlab.nyc/testlab/svg-blobs/fire.html" target="_blank">Fire</a>:** Another real-world example building on the previous examples to create an animated "fire" containing paths and polygons from a 2-layer SVG file created in Adobe Illustrator.

**More to come...**

