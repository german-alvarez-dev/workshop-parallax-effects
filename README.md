# Parallax-web-effects

Parallax effects made with vanilla JS + VivusSVG plugin


## FYI
 - `data-attributes` can store any information on the DOM, retrieving their values with [the `.dataset` JS property](https://developer.mozilla.org/es/docs/Web/API/HTMLElement/dataset).
 - `.getBoundingClientRect()` method with its porperty `.top` returns the difference between the element top and the viewport top.
 - `ìsInViewport()` function checks whether the argumented element is inside the viewport.
 - Vivus SVG accepts a second optional argument: a callback that will trigger after the drawing process finishes [(plugin docs)](https://github.com/maxwellito/vivus#vivusjs)
 - Smooth transition effect made by the final CSS rule (yay!):
 ````css
 .parallax {
    transition: transform 10s cubic-bezier(0,1,.5,1)
 }
 ````

## External resources
 - VivusSVG: self-drawing plugin for SVG: https://github.com/maxwellito/vivus
 - Liniea IO iconset (SVG icons taken from the _SVG_ directory): https://github.com/linea-io/Linea-Iconset 
