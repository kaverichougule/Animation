Hosted Link: https://kaverichougule.github.io/Animation/
![Uploading image.png…]()
index.html <br>
The <body> section contains the visible content of the web page. <br>
Inside the <body>, there's a <div> element with the class "container" that holds three <img> elements, each with a source and alt attribute representing different images. <br>

style.css <br>
The * selector applies a CSS reset, removing margins and padding from all elements. <br>
The body element is set to display as a flex container, centering its contents both horizontally and vertically. The background color is black, and the minimum height is set to 100vh (viewport height). <br>
The .container class styles the container of the images. It's displayed as a flex container with a width of 1100 pixels and equal spacing between its items. The -webkit-box-reflect property creates a reflection effect below the images. <br>
The .container img selector styles the individual images. They have a maximum width of 350px, a rotated perspective effect, a transition for smooth animation, a shadow, and rounded corners. <br>
On hovering over the .container, the opacity of the images is reduced to 0.3. <br>
On hovering over an image, it returns to its original perspective rotation and opacity. <br>
