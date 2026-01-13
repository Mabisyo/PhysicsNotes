#physics1-mechanics-U6 
[[Physics 1]]
___________
## Rotational Kinetic Energy
- Rotational kinetic energy describes the energy of rotating objects. Understanding this concept, along with translational kinetic energy, helps explain how objects store energy through rotation and how to describe motion.
- It may be calculated using the formula:
	-$$K =\frac{1}{2}(I\omega^2)$$where K is kinetic energy, $I$ is rotational inertia, and $\omega$ is angular velocity. 
	- Rotational inertia $I$ depends on the object’s mass and its distribution relative to the rotation axis.
	- Angular velocity $\omega$ measures how quickly the object rotates in radians per second. 
### Rotational vs translational
- An object can have rotational kinetic energy without having translational kinetic energy and vice versa. 
- An object that is considered rolling is not in equilibrium translationally or rotationally. 
- An object “rolling without slipping” is the description we typically work with since the point of contact is always considered to be instantaneously at rest.

## Things we consider when working with rolling motion
 - We choose the point instantaneously at rest, or in contact, with the surface to be the axis of rotation. Let’s think about why?
 - Choosing the axis of rotation to be the point in contact eliminates the torque of friction, the torque of Mgcos(θ), and any normal force. This is because all the line of action of these forces intersect the axis of rotation we chose. 
   
  ![](RollingWoSlipping1.png)
   - This is the general free body diagram for a rolling object. As you can see the only torque we need to take into consideration is the parallel component of gravity since we chose, Point P, as our A.O.R. 

## Considering the geometric figure rotating
![](PossibleRotationalInertias.jpg)
- Now although this may be overwhelming, keep in mind the CollegeBoard typically tells you what the rotational inertia of the object is. 
  
  ## The Parallel Axis Theorem
- General formula$$ I = I\tiny CM \normalsize + mx^2$$
- Above is the parallel axis theorem which states that the Rotational Inertia of any object I, rotated parallel to the position of the center of mass, can be found by summing the rotational inertia of the center of mass plus the mass of the rotation axis times the distance between them squared. 

- The words above may sound confusing so lets practice!

![](RollingProblem1.png)

- First, lets choose a coordinate system and point to be our axis of rotation. Notice the similarities from the previous explanation. 
 ![](RollingWoSlipping1.png)
 - We spoke earlier on why choosing a point where the rolling object is instantaneously at rest is beneficial. Now the problem asks for the acceleration of the cylinder’s center of mass so lets begin by summing the torques.

$$
\tau^{Mg\sin(\theta)} + \tau^{Mg\cos(\theta)} + \tau^{f_s} = \tau^{\text{net}}
$$
- Since the torques of Mgcos(theta) and the force of static friction are 0, we are left with. 
$$
\tau^{Mg\sin(\theta)} + 0 + 0 = \tau^{\text{net}}
$$
- Then we know that torque is the cross product of radius with force so we know.
$$
|r| \cdot |Mg\sin(\theta)| \cdot \sin(\phi)
$$
- Of course, since the angle between the radius and Mgsin(θ) is 90 degrees when drawn Tail to tail, then sin(Φ) is equal to 1. 

- Using Newton’s second law for Torque’s. We have:
- $$
R \cdot (Mg\sin(\theta)) = I\alpha
$$
- Let’s tackle the main problem here first: The Rotational Inertia. Since the axis of rotation is not the center of mass but is at a position parallel to it, then we can use the parallel axis theorem!
$$ I = I\tiny CM \normalsize + mx^2$$
Substitute Rotational inertia of center of mass using [this image.](PossibleRotationalInertias.jpg): 
$$
I = \frac{1}{2}MR^2 + mx^2
$$
Substitute x as the radius because it is the distance between the center of mass and point P.
$$
I = \frac{1}{2}MR^2 + mR^2
$$
Combine:
$$
I = \frac{3}{2}MR^2
$$
Substitute back into original torque equation:
$$
R \cdot (Mg\sin(\theta)) = \frac{3}{2}MR^2\alpha
$$
Since we want the linear acceleration of the center of mass convert α to a.
$$
R \cdot (Mg\sin(\theta)) = \frac{3}{2}MR^2 \cdot \frac{a}{R}
$$
Cancel The R’s on the right:
$$
R \cdot (Mg\sin(\theta)) = \frac{3}{2}MR \cdot a
$$
Divide by R:
$$
(Mg\sin(\theta)) = \frac{3}{2}Ma
$$
Cancel Masses: $$
g\sin(\theta) = \frac{3}{2}a
$$
Solve for a: 
$$
\frac{2}{3}g\sin(\theta) = a
$$
The acceleration of every point is the same so we can be safe that this is the acceleration of the center of mass!

## In Summary
- When needing to find acceleration and dealing with problems about rolling, it is important to choose an axis of rotation, which like P, will eliminate the need of multiple torques.
- However, this has a consequence, we will then need to evaluate the new rotational inertia using the parallel axis theorem so don’t forget.
- Everything else is cold algebra and manipulation. 