---
title: Auto Crop
categories: [Tutorials]
name: "Auto Crop"
artifact: sc.fiji:Fiji_Plugins
source-url: https://github.com/fiji/Fiji_Plugins/blob/-/src/main/java/fiji/selection/Select_Bounding_Box.java
initial-release-date: "2020-02-04"
---

This plugin can find the smallest bounding box of an image (or a rectangular part defined by a selection) by cropping as much background as possible.

In the version labeled with *(guess background color)*, the plugin tries to determine the background color by looking at the pixels on the border of the image, while *Auto Crop* uses the currently selected background color which can be changed by double-clicking on the pipette symbol or using the {% include bc path='Image | Color | Color Picker...' %}.

Instead of cropping right away, you can set the selection to the rectangle that would be cropped to using {% include bc path='Edit | Selection | Select Bounding Box' %}.
