About
------

EarthSky.osl is an osl shader for rendering a sky based on Nishita's paper in 1993 entitled "Display of the Earth Taking into account Atmospheric Scattering". It's mostly written based on the following article: http://www.scratchapixel.com/lessons/3d-advanced-lessons/simulating-the-colors-of-the-sky/atmospheric-scattering/

This fork takes up on the awesome work from Ben Simonds, adding more control, a cloud layer, and blends the work with some Cycles Nodes setup to make it easy on the composition.

Features
-----

- No geometry (it's actually pretty cool!)
- Colourable sky (via hue-shiftinig for now, let's try and be accurate later, mh-kay)
- Clouds map (with no shadows for now)
- Specular map integration with the Node Group

Usage
-----

- Import text into blender.
- Enable Open Shading Language from render options.
- Use as OSL shader from script node.


To do list
----------
- Add a working cloud shadow layer
- Allow for scattering parameters tweaking (which would allow for more a accurate scattering simulation for various atmospheres)
- Sun light directly in the background / Link from scene's Sun direction to shader's SunVector
	
