## 3D Rectangular Coordinate System
* 3D systems are created by adding a new axis, called the z-axis. The z-axis is inserted through the origin perpendicular to the xy-plane.
*  Points displayed in 3D space (ℝ³), will be expressed as P(a,b,c) or P(x,y,z).
	* Below P1(2,3,-2) and P2(0,-1,2) are plotted.
```easy-tikz
{
  "dimension": true,
  "documentSetup": true,
  "title": "3D Systems",
  "size_x_cm": 10,
  "size_y_cm": 10,
  "show_axis_label": true,
  "axis_label_x": "x",
  "axis_label_y": "y",
  "documentClose": true,
  "showAxis": true,
  "showLargeGrid": false,
  "showSmallGrid": false,
  "gridSize": 5,
  "xmin": "-2",
  "xmax": "2",
  "ymin": "-2",
  "ymax": "2",
  "axis_style": "box",
  "functions": [],
  "zmin": "-2",
  "zmax": "2",
  "axis_label_z": "z",
  "rotationX": 19,
  "rotationZ": 48,
  "zoom3D": 1,
  "boxAspect": "equal",
  "functions3D": [],
  "majorTickNum": 8,
  "previewSize": 760,
  "annotations": [],
  "tools": [
    {
      "type": "point3D",
      "x": "2",
      "y": "3",
      "z": "-2",
      "color": "red",
      "label": "P1"
    },
    {
      "type": "point3D",
      "x": "0",
      "y": "-1",
      "z": "2",
      "color": "red",
      "label": "P2"
    }
  ],
  "coordinateSystem": "cartesian",
  "axis_label_x_polar": "",
  "axis_label_y_polar": "",
  "displayAlign": "left",
  "displayWidth": 440
}
```
* As a result, there are now 3 planes which divide space into 8 regions called octants:
	* **xy-plane** (z=0), **zx-plane** (y=0), and **yz-plane** (x=0).
	* The first octant has all positive values.
## Distance formula in ℝ³
$$
|P_{1}P_{2}|=\sqrt{ (x_{2}-x_{1})^2 +(y_{2}-y_{1})^2+(z_{2}-z_{1})^2}
$$
* Distance between P1(2,3,-2) and P2(0,-1,2):
$$

$$