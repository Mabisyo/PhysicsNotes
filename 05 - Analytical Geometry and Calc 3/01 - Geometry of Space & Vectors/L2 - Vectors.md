## Geometric Approach
* A vector with an initial point A and terminal point B is represented by the line segment AB, and its length (magnitude) is denoted by |AB|
	* Two vectors are equal if they have the same magnitude and direction.
	* Vectors can be added, subtracted, and multiplied by a scalar (value). Their direction flips if multiplied by -1.
		* Vectors are added through a method called Tip To Tail, where the second vector gets placed on the tip of the first vector and the resultant vector is the one which is drawn from the tail of the first vector to the tip of the second one.![[Pasted image 20260831155903.png]]
		* Vectors can be multiplied by a constant, c(u) where c is a constant and u is a number. Two nonzero vectors u and v are parallel if v=cu.
## Algebraic Approach
* The **position** vector u = <u1,u2,u3> has its initial point at the origin and its terminal point at <u1,u2,u3>
```easy-tikz
{
  "dimension": true,
  "documentSetup": true,
  "title": "",
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
      "type": "segment3D",
      "x1": "0",
      "y1": "0",
      "z1": "0",
      "x2": "1",
      "y2": "1",
      "z2": "3",
      "color": "red",
      "thickness": "thick",
      "dashed": false,
      "arrow": "forward"
    }
  ],
  "coordinateSystem": "cartesian",
  "axis_label_x_polar": "",
  "axis_label_y_polar": "",
  "displayWidth": 340
}
```
* Between two points P1(x1,y1,z1) and P2(x2,y2,z2): $$\array{ \vec{u}= \vec{P_{1}P_{2}} = <x_{2}-x_{1},y_{2}-y_{1},z_{2}-z_{1}> \cr |\vec{u}| = |\vec{P_{1}P_{2}|} = \sqrt{ (x_{2}-x_{1})^2+(y_{2}-y_{1})^2+(z_{2}-z_{1})^2 }}$$
* Addition of vectors: $$\vec{u}+\vec{v}\space = \space< u_{1}+v_{1},u_{2}+v_{2},u_{3}+v_{3}>$$
* Scalar multiplication: $$c\vec{u}\space = \space<cu_{1},cu_{2},cu_{3}>$$
## Unit Vectors
* A unit vector is a vector of length 1.$$\hat{u}=\frac{\vec{w}}{|\vec{w}|}$$
	* EX: Find the unit vector in the direction of the vector w = <-1,2,-2>$$\array{ \hat{u} = \frac{\vec{w}}{|\vec{w}|} = \space \frac{<-1,2,-2>}{\sqrt{ (-1)^2+2^2+(-2)^2 }} = \space \frac{<-1,2,-2>}{\sqrt{ 1+4+4 }}\cr = \space \frac{<-1,2,-2>}{3} \to \space <-\frac{1}{3},\frac{2}{3},-\frac{2}{3}>}$$
* The standard basis vectors are given by: $$\vec{i}=\langle1,0,0\rangle\qquad\vec{j}=\langle0,1,0\rangle\qquad\vec{k}=\langle0,0,1\rangle$$
	* These vectors point in the direction of the positive x, y, and z coordinate axes.
	* Any nonzero vector u can be expressed as: $$\vec{u}= |\vec{u}|\left( \frac{\vec{u}}{|\vec{u}|} \right)$$