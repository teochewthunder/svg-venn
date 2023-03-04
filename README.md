# Venn Diagram SVG
Just a simple demonstration of SVG elements such as paths, curves and tspans.

## Circles
Use the circle tag. It's important to take note of the center co-ordinates and radius, because every other element we use will be relative to those. The color scheme will be a simpe red, blue and green, and lowered opacity.

## Circle Intersects
Use the path tag, with `a` in the `d` attributes for the curves. What I did was lower the opacity for everything and define an outline so that I could shift pixels to get it as close as possible. The colors are combined, with lowered opacities - purple for the red and blue intersects, olive green for the green and red intersects, and royal blue for the blue and green intersects. The final result is that the intersecting area right in the middle is a totally different color from the rest.

## Text
For one-liner text, it's a simple text tag. For multi-liners, we use tspan wthin the text tags with `dx` and `dy` attributes.
