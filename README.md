# Lumira.viz-ext.3DWorld

## You can find this extension on the official **SAP Lumira Repository** on **GitHub**, right here: https://github.com/SAP/lumira-extension-viz/tree/master/3D_World

If you want to download a **pre-built and ready-to-use extension**, sneak into the **/build** folder.
Read the full article about this extension right there : http://scn.sap.com/community/lumira/blog/2015/11/09/map-your-data-on-a-3d-world!

Hi everyone. This repository is a viz extension for SAP Lumira.
It displays a 3D world where you can map your longitude/latitude data, as well as put two indicators on them (size/color).

This explanation will be updated as I update the code.

![viz](http://s4.postimg.org/itkn96gtp/Screenshot07.png)

For the moment, let's viz :) !

**Update**
- 03/06/2016 : Had not much time to work on this, but new stuff is coming soon!
- 12/01/2015 : Next feature to come is infowindow when hovering the points
- 11/19/2015 : Centered the globe above USA upon ask. Sneak the **3DWorld-master-CenteredAboveUSA** package in the **/build** folder.

**Fix**
- 11/11/2015 : Adding multiple times this extension in one story page now works as exepected

**Current limitations**
- There is no legend for the extension, I've planned to make one tho (or maybe some kind of *infowindow*)
- Even if technically the globe supports an infinity of points, the performance starts to decrease above 250/300 points. The performance decreases even faster as you put several times the extension in a Lumira Story.
