Convert HTML to image
=====================

Let's evaluate client-side HTML to image conversion libraries based on:

- Browser support
- Feature support
- Quality
- Performance

The libraries we use are:

- [html2canvas](http://html2canvas.hertzen.com/)
- [rasterizeHTML.js](http://cburgmer.github.io/rasterizeHTML.js/)
- [saveSvgAsPng](https://github.com/exupero/saveSvgAsPng)
- [DOM Panda](https://github.com/jankuca/dom-panda)

The test page has a series of HTML5 elements (including SVG, images, canvas).
Each element is rendered using one of these libraries for comparison.


Build
-----

1. From [html2canvas release](https://github.com/niklasvh/html2canvas/releases)
   download `html2canvas.js` and `html2canvas.svg.js` into `lib/`
2. Run `npm install rasterizehtml` and copy
   `node_modules/rasterizehtml/dist/rasterizeHTML.allinone.js` into `lib/`
