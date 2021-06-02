# I3S Version Compare
=======

An application that compares an Integrated Mesh and 3D Object I3S layers in version 1.6 vs Version 1.7.

To compare different layers, the app expects a webscene with bookmarks named using the following convention:
[anyName]*_scene.1*  (eg. `View.1_scene.1`) - the name of a bookmark showcasing the i3s 1.6 layer.
[anyName]*_Scene.2* - (eg. `View.2_scene.2`) - the name of the corresponding bookmark showcasing the same layer in i3s 1.7.

## [Live Version](https://tamrat-b.github.io/i3SBasis_Ktx2_demo/?stats=true)

## Supported URL parameters

* [webscene=id](https://jsapi.maps.arcgis.com/home/webscene/viewer.html?webscene=979cf94115144deab747c3f946ac78fe): Load the given webscene from the portal (default www.arcgis.com)
* portal=url: Use the given portal URL
* [animate=true](https://tamrat-b.github.io/i3SBasis_Ktx2_demo?animate=true): Run through all slides in both versions once
* [stats=true](https://tamrat-b.github.io/i3SBasis_Ktx2_demo?stats=true): Display some scene statistics
