---
layout: post
title: "Circular team member avatars"
author-id: stasinos
tags: [howto]
---

A short guide on using GIMP to create the avatar images.

1. Make sure that your layer has an "alpha channel":
```
Layer → Transparency → Add alpha channel
```
If it’s grayed out it means you already have one

2. Create a circular selection with the "Ellipse select tool". Use the
   "Tool options" dialog to set the ratio to 1:1:
```
Windows → Dockable dialogs → Tool options
```

3. Once you have the required selection, invert the selection so that
   everything except your circle is selected, and delete. You should
   have your central circle left, surrounded by a checkerboard
   pattern. This checkerboard is not part of the image, it just
   indicates the transparent parts of the image.

4. Crop the image:
```
Image → Crop to content
```

5. Rescale the cropped image to 128x128 at 600dpi.

6. Export the image to a format that supports transparency, like PNG

