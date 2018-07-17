# 3d printed bearing removal tool

Simple tool to pull ball bearings out of their socket.
![bearing puller](https://raw.githubusercontent.com/bzed/3d-bearing-removal-tool/master/images/bearing-puller.png)

## Short howto
The provided STL files support type 6000 bearings. If you need something else, use OpenSCAD and modify the variables on top of the file.
Also you'll need a bolt, washers and a screw for the bolt. You might want to make sure that the washer on the closed side of the tool is at least as large as the tool.

## 3d printing
I've used PETG, 0.2mm layer height, 50% Tri-Hexagon infill, 3mm walls (basically you want the walls that take the load to be solid, the washer you put on top will spread the preasure on them), no fan. Might need a brim if printed in PETG.

## CUBE Stereo 120 HPA my 2015 mode
The main reason for me to create this project was to be able to remove the pivot bearings of my CUBE Stereo 120 HPA, model year 2015. Unfortunately the frame was built in a way that normal/commercial tools can't be used as the frame is not completely flat around the bearing.
So the OpenSCAD file has an option to enable the "cube bike" mode which basically removes a bit material on 1/4 of the tool. YOu can enable/disable the feature as needed and modify the height of the removed material.

![cube stereo mode](https://raw.githubusercontent.com/bzed/3d-bearing-removal-tool/master/images/bearing-puller_workaround.png)

## tool in use
![tool in use](https://raw.githubusercontent.com/bzed/3d-bearing-removal-tool/master/images/bearing-puller-cube-bike.png)

## copyright & license
Copyright © 2018 Bernd Zeimetz <bernd@bzed.de>

License: [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)
