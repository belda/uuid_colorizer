# uuid_colorizer
jQuery plugin to ease visual uuid distinction

Simple plugin that you can use to make it easier for you to visualize UUIDs (32 hex character unique identifiers). 

##Usage

Assuming that you have jQuery already included put the libraries to your html <head>

```html
<link rel="stylesheet" type="text/css" href="uuid-colorizer.css">
<script src="uuid-colorizer.js"></script>
```

In order to use it put one of these to your code.

```javascript
$("#testdivover").highlight("over"); //background coloring
$("#testdivover").highlight("collapse"); //collapsable coloring to badge
$("#testdivleft").highlight("left"); //put badge on left
$("#testdivright").highlight("right"); //put badge on right
```

You can see the example at https://jsfiddle.net/74bfd0ae/4/
