_________
# Sources (MLA Format)
_________
1. “12.2: The Biot-Savart Law.” _Physics LibreTexts_, Nov. 2016, phys.libretexts.org/Bookshelves/University_Physics/University_Physics_(OpenStax)/University_Physics_II_-_Thermodynamics_Electricity_and_Magnetism_(OpenStax)/12%3A_Sources_of_Magnetic_Fields/12.02%3A_The_Biot-Savart_Law.

# Biot Savart Law
________
We need to show that the Biot-Savart Law can quantitatively describe a magnetic field produced by a tiny segment of any current carrying geometry. We are going to use the example of an infinitely long straight wire to demonstrate that the Biot-Savart Law can accurately describe magnetic fields quantitatively. 

| Variables | Meaning                            |
| --------- | ---------------------------------- |
| *l*       | length of a region in the geometry |
| *B*       | Magnetic field                     |
| *I*       | Current                            |
| µ         | permeability of free space         |
### Equations
___
**Fundamental Equation (Biot-Savart Law)**
$$d\vec{B}=\frac{\frac{\mu_{0}}{4\pi}\times(I(d\vec{l}\times \hat{r})}{r^2}$$
or → $$\vec{B}=\frac{\mu_{0}I}{4\pi}\int \frac{\sin \theta d\vec{l}}{r^2}$$
Note: Using the identity $$1+\tan^2 \theta = \sec^2 \theta$$ and $$r = \sqrt{l^2+ R^2}$$
and $$\sin \theta = \frac{R}{\sqrt{ l^2 + R^2 }}$$
We can use trig sub to integrate.

$$\begin{array}
 \\
\vec{B} = \frac{\mu_{0}I}{4\pi} \int \frac{\sin \theta d \vec{l}}{(l^2+R^2)^{\frac{1}{2}}} \rightarrow \frac{\mu_{0}I}{4\pi} \int \frac{\sin \theta d \vec{l}}{l^2+R^2} \\
 \\
\vec{B}=\frac{\mu_{0}I}{4\pi} \int \frac{\sin \theta}{1} \frac{d \vec{l}}{(l^2+R^2)} \rightarrow \frac{\mu_{0}I}{4\pi} \int \frac{R}{\sqrt{ l^2 +R^2 }} \frac{d \vec{l}}{(l^2+R^2)} \\ \\
\vec{B} = \frac{\mu_{0}I}{4\pi} \int \frac{Rd \vec{l}}{(l^2 +R^2)^\frac{3}{2}} \\
 \\
\rightarrow l = R\tan \theta \\
\rightarrow d \vec{l} = R\sec^2 \theta \\
\rightarrow l^2+R^2 = R^2\tan^2\theta = R^2(\tan^2\theta)=R^2\sec^2\theta \\
\rightarrow (R^2\sec^2\theta)^\frac{3}{2} = R^3\sec^3\theta \\ \\
 \\
\rightarrow \sin \alpha = \frac{l}{\sqrt{ l^2+R^2 }}
 \\ \\
 
\rightarrow R\int\frac{R\sec^2\theta d\theta}{R^3\sec^3\theta} = R\int\frac{d\theta}{R^2\sec \theta}  \\
\frac{1}{R}\int \frac{d\theta}{\sec \theta} = \frac{1}{R}\int \cos \theta d\theta = \frac{1}{R} \sin \alpha +C \\
\vec{B} = \frac{\mu_{0}I}{4\pi}\left[ \frac{1}{R} \sin \alpha  \right]= \frac{\mu_{0}I}{4\pi R}\left[ \frac{l}{\sqrt{ l^2+R^2 }} \right]  \\
 \\
\vec{B}= \frac{\mu_{0}I}{4\pi R}\left[ \frac{∞}{\sqrt{ ∞^2+R^2 }} - \left( -\frac{∞}{\sqrt{ (-∞)^2+R^2 }} \right) \right] = \frac{\mu_{0}I}{4\pi R}[1-(-1)] \\
 \\
 \vec{B} =  \frac{2\mu_{0}I}{4\pi R} = \boxed{\frac{\mu_{0}I}{2\pi R}}
\end{array}$$
## Geometries
_______
### Infinite Straight Long Wire 
![[Long Straight Wire.png]]
### Trigonometric Substitution Triangle
![[Screenshot 2026-03-28 134531.png]]
### Step By Step Explanation
1. Start with fundamental Biot-Savart Equation and establish trigonometric identities
2. Substitute the expressions for *r* and *sine of theta* into the integral equation
3. Simplify the expression inside of the integral which will result in the equation shown in the third line.
4. Establish trigonometric substitution equations for *l*, *dl*, and *l squared + R squared* then simplify for *R cubed times sec cubed of theta*
5. Based on the trig substitution triangle, we use *sine of alpha* to represent the angles of this triangle, giving you the equation shown above for *sine of alpha*
6. Substitute this into the integral and then simplify
7. Integrate from negative infinity to positive infinity for the answer shown in the box. 






	

‌