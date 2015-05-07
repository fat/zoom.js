# ZOOM.JS

Beautiful, sleek image zoom transition as seen on [Medium](https://medium.com/designing-medium/image-zoom-on-medium-24d146fc0c20).

### Demo
You can see a demo of zoom.js in action here: https://fat.github.io/zoom.js

### How To Use zoom.js

1. Link the zoom.js and zoom.css files to your site or application.

	`<link href="css/zoom.css" rel="stylesheet">`

	`<script src="js/zoom.js">`
2. zoom.js is dependent on the teeny tiny [transition.js file](https://raw.github.com/twbs/bootstrap/master/js/transition.js) from Bootstrap, so make sure to include that as well.

	`<script src="js/transition.js">`

3. To use zoom.js, simply add a `data-action="zoom"` attribute to an image element you would like to utilise the plugin. For example:

	`<img src="img/blog_post_featured.png" data-action="zoom">`


### Awesome Features

zoom.js will automatically close when the user clicks out of it, or press the escape key. 


### Browser Support

zoom.js should (in theory) work in all relevant browsers. If not, create an issue!