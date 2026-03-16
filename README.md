# Minimal-Beamer-Grainy
This is a variation of the Minimal-Beamer-Palette template, which also gives you the option to layer textures on your slides.

To change the texture for future slides, instert the following command between frames:  `\usetexture[X]{Y}`, where X is the desired opacity (default .1) and Y is the choice of texture (from 1 to 5). 

To turn off textures, use `\notexture`.

All textures are free for commercial use. I downloaded them from *https://texturelabs.org*.


You can also change the colors in the same way as in the Minimal-Beamer-Palette template. This is the readme for that template:

A minimal beamer presentation for which it is easy to modify the color palette to custom colors.
It is easy to modify; the relevant sections to change are:

% --- COLOR PALETTE ---I went to *https://coolors.co* to pick a color palette I liked. You can use either the HEX code (TeX recognizes this as the {HTML} option) or the RGB value to change the colors. Coolors makes it easy to copy and paste HEX or RGB values from templates.

% --- BEAMER SETTINGS --- This is where I tweaked what colors applied to which text/areas.

% --- CUSTOM "SKETCHY" BOX FOR THEOREMS --- I didn't have different environments for definitions or anything, I just used the sketchybox environment.

The math font is Euler, which I quite like. It would be easy to swap this out for another font.

I collaborated with Gemini to build this Beamer template.
