# Unit 8 – Electricity and Magnetism: AP Physics C

---

## 8.1 Electric Charge and Electric Force

- **Nature of Charge:** Scalar, positive or negative.  
- **Elementary Charge:** Smallest indivisible charge, e (electron/proton).  
- **Coulomb’s Law:**  $$
F = k \frac{q_1 q_2}{r^2}
$$
- Force ∝ charges, ∝ 1/r².  
- **Force Direction:**  
- Same sign → repulsion  
- Opposite sign → attraction  
- **Gravity vs Electrostatics:** Electrostatic force ≫ gravitational force.  
- **Permittivity & Polarization:** Measures how a material polarizes in an electric field.  
- **Materials:**  
- Conductors → charges move freely  
- Insulators → charges do not move freely  

---

## 8.2 Conservation and Charging

- **System Changes:** Net charge/distribution can change due to nearby charges.  
- **Charge Transfer:** Only via transfer between system & surroundings.  
- **Induction:** Polarization of systems due to nearby charges.  
- **Grounding:** Connect charged object to a large neutral body (e.g., Earth).

---

## 8.3 Electric Fields

- **Definition:**  $$
\vec{E} = \frac{\vec{F}}{q_{\rm test}}
$$
- **Field Direction:** Away from +, toward – charges.  
- **Superposition:** Net E = vector sum of all fields.  
- **Conductors in Equilibrium:**  
- Excess charge on surface  
- E_inside = 0  
- **Surface Fields:** E perpendicular to surface.

---

## 8.4 & 8.5 Charge Distributions and Flux

- **Integration:** Use integration + superposition for E from distributions.  
- **Flux Definition:** Amount passing through area.  
- **Area Vector:** Perpendicular to surface, outward for closed surfaces.

---

## 8.6 Gauss’s Law

- **Core Principle:** Flux through Gaussian surface = charge enclosed / e0.  
- **Independence of Size:** Flux depends on **enclosed charge**, not surface size.  
- **Strategic Construction:** Choose surface where E is perpendicular or parallel.  
- **Maxwell’s Equations:** Gauss’s law = Maxwell’s first equation.  
- **Examples of Conductors:** Cu, Al, Au  

---

## Conductors vs Insulators (Calculator Notes)

**Conductors:**  
- Free charges → move  
- E_inside = 0  
- Charge on surface  
- V = constant  

**Insulators:**  
- Charges stuck in place  
- E_inside ≠ 0 possible  
- Charge can reside on surface or inside  
- No natural equipotential  
- Examples: rubber, glass, plastic

---

## Quick Gauss’s Law Steps for Common Shapes

**1. Sphere (radius R, point at r):**  
- r < R → inside:  
$$
Q_{\rm enclosed} = Q \frac{r^3}{R^3}
$$
$$
E = \frac{Q_{\rm enclosed}}{4 \pi \, \varepsilon_0 \, r^2} 
  = \frac{Q \, r}{4 \pi \, \varepsilon_0 \, R^3}
$$
- r ≥ R → outside:  
$$
Q_{\rm enclosed} = Q
$$
$$
E = \frac{Q_{\rm enclosed}}{4 \pi \, \varepsilon_0 \, r^2} 
  = \frac{Q}{4 \pi \, \varepsilon_0 \, r^2}
$$
**2. Infinite line of charge (λ, distance r):**  
$$
E = \frac{\lambda}{2 \pi \varepsilon_0 r}
$$
- Gaussian cylinder → flux through curved side only.  

**3. Infinite plane / sheet (σ):**  
$$
E = \frac{\sigma}{2 \varepsilon_0}
$$
- Gaussian pillbox → flux through top & bottom faces.  

**4. Point charge potential (V):**  
$$
V = \frac{Q}{4 \pi \varepsilon_0 r}
$$
- Scalars add algebraically if multiple charges.  
  
### Total Charge from a Continuous Charge Distribution

For a continuous charge distribution, the total charge is found by integrating the **charge density** over the volume:

$$
Q_{\rm total} = \int \rho(\vec{r}) \, dV
$$
- $\rho$ = volume charge density at position \($\vec{r}$)(charge per unit volume)  
- \(dV\) = infinitesimal volume element  
- Purpose: Sums all the infinitesimal charges in a continuous distribution to find the **total charge**.  
Example:

A non-uniformly charged sphere with radius \(R\), where the charge density increases linearly with radius:

$$
\rho(r) = \rho_0 \frac{r}{R}
$$

The total charge is:

$$
\begin{aligned}
Q_{\rm total} &= \int_0^R \rho(r) \, dV \\
&= \int_0^R \rho_0 \frac{r}{R} \cdot 4 \pi r^2 \, dr \\
&= 4 \pi \frac{\rho_0}{R} \int_0^R r^3 \, dr \\
&= 4 \pi \frac{\rho_0}{R} \cdot \frac{R^4}{4} \\
&= \pi \rho_0 R^3
\end{aligned}
$$
The total charge of the sphere is:

$$
Q_{\rm total} = \pi \rho_0 R^3
$$

Using Gauss's law, the electric field outside a spherically symmetric charge distribution is:

$$
E \cdot 4 \pi r^2 = \frac{Q_{\rm total}}{\varepsilon_0}, \quad r \ge R
$$

Solve for \(E\):

$$
E = \frac{Q_{\rm total}}{4 \pi \varepsilon_0 r^2}
$$

Substitute $(Q_{\rm total}$ )= $\pi \rho_0 R^3$:

$$
E = \frac{\pi \rho_0 R^3}{4 \pi \varepsilon_0 r^2} = \frac{\rho_0 R^3}{4 \varepsilon_0 r^2}, \quad r \ge R
$$


---

## General Exam Tips

- Always check **symmetry** before choosing Gaussian surface.  
- For spheres: r < R → inside formula, r ≥ R → outside formula.  
- Flux depends **only on enclosed charge**.  
- Conductors → E_inside = 0, charge on surface.  
- Insulators → charge can stay anywhere.  
- Use **calculator-friendly letters**: `e0` for epsilon naught.
  
## Calculator Notes
- To have the ability to transfer notes onto your calculator you must first follow the steps in [[TI-84 Setup AP1]]. Then, go to []

  
  
  