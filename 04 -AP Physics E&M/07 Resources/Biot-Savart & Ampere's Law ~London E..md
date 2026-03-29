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
### Situation (Visual)
![[Long Straight Wire.png|416]]
### Derivation
___
**Fundamental Equation (Biot-Savart Law)**
$$d\vec{B}=\frac{\frac{\mu_{0}}{4\pi}\times(I(d\vec{l}\times \hat{r})}{r^2}$$
or → $$\vec{B}=\frac{\mu_{0}I}{4\pi}\int \frac{\sin \theta d\vec{l}}{r^2}$$
Note: Using the identity $$1+\tan^2 \theta = \sec^2 \theta$$ and establishing *r* based on the situation’s geometry$$r = \sqrt{l^2+ R^2}$$
and finally establishing the value of *sine of theta* based on the situation’s geometry $$\sin \theta = \frac{R}{\sqrt{ l^2 + R^2 }}$$
We can then integrate to find the equation for a infinitely long straight wire using Biot-Savart’s Law
1. First we will plug in all the values established above into the integral equation $$\begin{array}
\vec{B} = \frac{\mu_{0}I}{4\pi} \int \frac{\sin \theta d \vec{l}}{(l^2+R^2)^{\frac{1}{2}}} \rightarrow \frac{\mu_{0}I}{4\pi} \int \frac{\sin \theta d \vec{l}}{l^2+R^2} \\
 \\
\vec{B}=\frac{\mu_{0}I}{4\pi} \int \frac{\sin \theta}{1} \frac{d \vec{l}}{(l^2+R^2)} \rightarrow \frac{\mu_{0}I}{4\pi} \int \frac{R}{\sqrt{ l^2 +R^2 }} \frac{d \vec{l}}{(l^2+R^2)} \\ \\
\vec{B} = \frac{\mu_{0}I}{4\pi} \int \frac{Rd \vec{l}}{(l^2 +R^2)^\frac{3}{2}}
\end{array}$$
2. Once we have plugged these values into the integral, we can now approach the trigonometric substitution. We will have to “create” a new triangle to visualize the expressions that will need to be substituted into the equation to evaluate the integral. ![[Screenshot 2026-03-28 134531.png|418]]
   Now that we have our triangle, we can put this visualization on paper: $$\begin{array}
\rightarrow l = R\tan \theta \\
\rightarrow d \vec{l} = R\sec^2 \theta \\
\rightarrow l^2+R^2 = R^2\tan^2\theta = R^2(\tan^2\theta)=R^2\sec^2\theta \\
\rightarrow (R^2\sec^2\theta)^\frac{3}{2} = R^3\sec^3\theta \\ \\
 \\
\rightarrow \sin \alpha = \frac{l}{\sqrt{ l^2+R^2 }} \\
\end{array}$$
3. Now we have our expressions to substitute in the integral. Before integrating, we need to simplify the expression: $$\begin{array}
\rightarrow R\int\frac{R\sec^2\theta d\theta}{R^3\sec^3\theta} = R\int\frac{d\theta}{R^2\sec \theta}  \\
\frac{1}{R}\int \frac{d\theta}{\sec \theta} = \frac{1}{R}\int \cos \theta d\theta
\end{array}$$
4. The integral expression has been simplified, now we can integrate to get a result of:
    $$\frac{1}{R} \sin \alpha +C $$
    Since we did trigonometric substitution, we temporarily ignored the bounds.
5. Let us bring everything together by substituting our *sin alpha* value mentioned above into the equation, combining our constant values, and reintroducing our bounds (-∞, ∞): $$\vec{B} = \frac{\mu_{0}I}{4\pi}\left[ \frac{1}{R} \sin \alpha  \right]= \frac{\mu_{0}I}{4\pi R}\left[ \frac{l}{\sqrt{ l^2+R^2 }} \right]$$ $$\vec{B}= \frac{\mu_{0}I}{4\pi R}\left[ \frac{∞}{\sqrt{ ∞^2+R^2 }} - \left( -\frac{∞}{\sqrt{ (-∞)^2+R^2 }} \right) \right] = \frac{\mu_{0}I}{4\pi R}[1-(-1)]$$
6. Our final result will be the following: $$ \boxed{\frac{\mu_{0}I}{2\pi R}}$$
# Ampere’s Law
__________
**Ampere’s Law relates a line integral of B around a closed loop to the current passing through the surface bounded by that loop. This Law significantly reduces the amount of derivation needed to quantitatively describe the magnetic field produced by a tiny segment of any current carrying geometry. The same example will be used: An infinitely long, straight current carrying wire.**

| Variables  | Meaning                                                                      | Units   |
| ---------- | ---------------------------------------------------------------------------- | ------- |
| ∮ B⃗ · dI⃗ | Closed line integral of B along the Amperian Loop                            | T*m     |
| μ₀         | Permeability of free space                                                   | T*(m/A) |
| I_enc      | Net current threading the surface bounded by the loop (sign from RHR)        | A       |
| dI⃗        | Infinitesimal length element along the closed path (vector, tangent to path) | m       |

### Situation (Visual)
![[Pasted image 20260329182103.png|318]]

### Derivation
________
We need to keep in mind that the Magnetic Field is constant everywhere and that Ampere’s Law is reliant on symmetry. 
1. We start off with Ampere’s Law: $$\oint \vec{B} \cdot d \vec{I}=\mu_{0} I_{enc}$$ or → $$\oint \vec{B} \cdot d \vec{I}\cos \theta=\mu_{0} I_{enc}$$
2. Since B and *dl* are parallel everywhere, *theta* is equal to zero, thus making *cosine of theta* equal to one, giving us the following result: $$\oint Bdl(1)=\mu_{0}I_{enc}$$
3. Since our magnetic field is constant, B is a constant and can therefore be brought to the outside of the integral: $$B\oint dl=\mu_{0}I_{enc}$$
4. We are working with a loop (circle). The integral of *dl* in this case would be equal to the circumference of a circle: $$ B(2\pi r)=\mu_{0}I_{enc}$$
5. Now we can solve for our magnetic field, B: $$\frac{B(2\pi r)}{2\pi r}=\frac{\mu_{0}I}{2\pi r}$$ $$B = \frac{\mu_{0}I}{2\pi r}$$