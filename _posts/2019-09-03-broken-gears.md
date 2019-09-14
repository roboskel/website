---
layout: post
title: 3D Printing Motor Gears
feature-img: assets/posts/2019-09-03-gears/gear-original-and-print.jpeg
thumbnail: assets/posts/2019-09-03-gears/gear-original-and-print.jpeg
tags: [howto, rulah, hardware failure]
author-id: oikonomou
date: 2019-09-03
---

Rulah, the rover we use for our rugged terrain navigation experiments,
had the gears in her motors wear to the point of being unuseable.
These were custom-made parts, not sold separatedly, so we had to
either replace an otherwise perfectly fine motor or to print our own
gears.

<!--more-->

We took the following steps:

 * We opened all four motors to find the least-worn gear,
   and [scanned]({{ "assets/posts/2019-09-03-gears/scan.stl" | relative_url }}) it.

 * We printed the scanned gear in resin, but both the quality of the
   scan and the printing material proved inadequate and the resin
   gears were crushed on our first test.

![Gear designed in blender]({{ "assets/posts/2019-09-03-gears/gear.png" | relative_url}})

 * We designed new gears
   in Blender following the instructions in the tutorial
   [&quot;How to Model Geometrically Correct (Involute) Gears in Blender&quot;](https://www.youtube.com/watch?v=DqBOva04lcE)
   by [Otvinta](http://www.otvinta.com).
   The the instructions is detailed and the only tricky bit is getting
   the distances right so that the gear fits the motors.
   You see the result in the image above and feel free to use our
   [design]({{ "assets/posts/2019-09-03-gears/gear.stl" | relative_url }})
   as your starting point, if you find it useful.

 * We went through
   the list of materials and explanations provided in
   [this guide](https://3dinsider.com/3d-printing-materials)
   and selected ABS, the most commonly used plastic for automotive
   parts.
   
 * We replaced the gears in _all_ motors with our prints, not only the
   one that was badly worn.

We gave been testing the new gears on rugged terrain for more than a
week now, and we see no signs of any problems.
