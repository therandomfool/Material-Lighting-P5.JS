# Material Lighting P5.JS

- normalMaterial() Normal material for geometry is a material that is not affected by light. It is not reflective and is a placeholder material often used for debugging. Surfaces facing the X-axis, become red, those facing the Y-axis, become green and those facing the Z-axis, become blue.

- ambientMaterial() Ambient material for geometry with a given color. Ambient material defines the color the object reflects under any lighting. For example, if the ambient material of an object is pure red, but the ambient lighting only contains green, the object will not reflect any light.

- specularMaterial() Specular material for geometry with a given color. Specular material is a shiny reflective material. Like ambient material it also defines the color the object reflects under ambient lighting. For example, if the specular material of an object is pure red, but the ambient lighting only contains green, the object will not reflect any light. For all other types of light like point and directional light, a specular material will reflect the color of the light source to the viewer.

![materiallightingp5.js](assets/material.gif)