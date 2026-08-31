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
\array{|P_{1}P_{2}| = \sqrt{ (0-2)^2+ (-1-3)^2 +(2-(-2))^2} \cr = \sqrt{ 4+16+16 } = \sqrt{ 36 }=6 \space units }
$$
* To find the distance of a point to a plane, look at the coordinate point of the one left out of the plane.
	*  Finding the distance from (1,-2,3) to the xy-plane means look at the |z| coordinate since the xy-plane means z=0. In this case, z=3 and that is the distance from the point to the xy-plane.
* To find the distance of a point to an axis, you need to use the distance formula between the point and a point that lies on the axis you want to reach. To do this we use a coordinate with the same value for the corresponding axis and 0s for the rest.
	* Finding the distance from (1,-2,3) to the z-axis means you need to first select a point to use in the distance formula. Match the axis value for both points, so both points should have z=3. Your second point should only have a value for the axis you want to find the distance towards, everything else should be 0.
	* $$\array{ (1,0,0) \to (1,-2,3) \cr \sqrt{ (1-0)^2+(-2-0)^2+(3-3)^2} \cr = \sqrt{ 1+4+0 } = \sqrt{ 5 }}$$
## Equation of a Sphere
* The standard equation for the sphere of radius r and center (a,b,c) is: $$(x-a)^2+(y-b)^2+(z-c)^2=r^2$$
* Consider the Points P1(2,3,-2) and P2(0,-1,2). Find an equation of the sphere for which the line segment P1P2 is a diameter:$$\array{ center: \frac{(2,3,-2)+(0,-1,2)}2 = \frac{(2,2,0)}{2} = (1,1,0)\cr radius: \frac{|P_{1}P_{2}|}{2} = \frac{ \sqrt{ (0-2)^2+(-1-3)^2+(2-(-2))^2 }}2 = 3 \cr equation: (x-1)^2+(y-1)^2+(z-0)^2=3^2}$$
	 EX: Find the center and radius of the sphere:$$x^{2}+y^{2}+z^{2}-2x+6y-8z=-1.$$
		Group like terms: $$(x^2-2x)+(y^2+6y)+(z^2-8z)=-1$$ and then complete the square, adding the values to both sides of the equation, to get the standard equation of a sphere:$$\array{ (x^2-2x+1)+(y^2+6y+9)+(z^2-8z+16)=-1+1+9+16 \cr (x-1)^2+(y+3)^2+(z-4)^2=25 \cr center: (1,-3,4) \space \space \space \space \space \space \space radius: \sqrt{ 25 }=5}$$
## Surfaces in 3D Space
* Graph y=2 in 2D and 3D space:
```easy-tikz
{
  "dimension": false,
  "documentSetup": true,
  "title": "y=2 2D",
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
  "xmin": "0",
  "xmax": "5",
  "ymin": "0",
  "ymax": "5",
  "axis_style": "box",
  "functions": [],
  "zmin": "-5",
  "zmax": "5",
  "axis_label_z": "z",
  "rotationX": 30,
  "rotationZ": 45,
  "zoom3D": 1,
  "boxAspect": "true",
  "functions3D": [],
  "majorTickNum": 8,
  "previewSize": 760,
  "annotations": [],
  "tools": [
    {
      "type": "horizontalLine",
      "y": "2",
      "color": "red",
      "thickness": "thick",
      "dashed": false,
      "label": ""
    }
  ],
  "coordinateSystem": "cartesian",
  "axis_label_x_polar": "",
  "axis_label_y_polar": "",
  "displayWidth": 350,
  "displayAlign": "center"
}
```
```easy-tikz
{
  "dimension": true,
  "documentSetup": true,
  "title": "y=2 3D",
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
  "xmin": "-0.5",
  "xmax": "10",
  "ymin": "-0.5",
  "ymax": "5",
  "axis_style": "box",
  "functions": [],
  "zmin": "-5",
  "zmax": "5",
  "axis_label_z": "z",
  "rotationX": 30,
  "rotationZ": 45,
  "zoom3D": 1,
  "boxAspect": "equal",
  "functions3D": [],
  "majorTickNum": 8,
  "previewSize": 760,
  "annotations": [],
  "tools": [
    {
      "type": "plane3D",
      "axis": "y",
      "value": "2",
      "color": "red",
      "fillOpacity": 0.4
    }
  ],
  "coordinateSystem": "cartesian",
  "axis_label_x_polar": "",
  "axis_label_y_polar": "",
  "displayWidth": 340,
  "displayAlign": "center"
}
```
