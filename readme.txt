Ed Hebert
DGMD E-27 Assignment 3

For this assignment, I focused on SVG graphics and their utility in modern web imagery and animation.

My assignment is presented in three main parts - "icon", "logo", and "waves". The interactive presentation can be navigated by clicking on any imagery present on any html page. All links lead to the next html "slide" in my presentation.

/icon/index.html - the first "slide" in my interactive presentation. It shows the comparable file size of a raster and vector icon, sized at 100px square. Both are pretty small file size.

/icon/bigbulb.html - this page scales those icons to 700px square, and reveals the "scalable" component of SVGs, and that the 3KB SVG still looks razor sharp at full screen size, whereas the raster .png file cannot be scaled without serious visual consequences.

/icon/hoverbulb.html - the properties of that same SVG file are now being manipulated with CSS. Just as we can use CSS to change text color or page properties, we can also use it to manipulate the properties of SVG graphics! Here, I'm changing the stroke weight and color of the lightbulb filament, as well as the opacity of a background element to manipulate the appearance of a graphic on hover. Still just one 3KB SVG file!

/logo/index.html - this page demonstrates further possibilities of SVG manipulation using CSS. Here I've built a responsive logo image that changes its look completely at different browser widths. Using CSS tools like media queries, it's possible to rearrange the visibility, position, or appearance of a graphic to customize it to a device or other custom viewing situation.

/waves/index.html - here I demonstrate how SVG graphics can be used to create a lightweight, rich-media animation experience. All assets on this full-page animation are vectors, and weigh in at well under 100KB. Also, I'm using SVGs as both background images and an embedded object (the lighthouse). Verbally, my presentation explained how I embedded CSS code directly into the SVG itself to animate the lighthouse's beacon. With an SVG linked via an <object> tag, it's possible to bring in interactive animation components of the SVG for exciting rich-media visuals.

