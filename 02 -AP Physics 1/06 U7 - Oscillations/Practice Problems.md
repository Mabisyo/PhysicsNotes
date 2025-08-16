_______
#physics1-mechanics-U7 
[[Physics 1]]
____________
## Problem 1: Mass–Spring System (SHM Basics)

**Problem Statement:**  
A 0.50‑kg mass is attached to a spring with a spring constant $k = 200\,\mathrm{N/m}$. The mass is displaced 0.10 m from equilibrium and then released from rest.

1. Calculate the angular frequency $\omega$.
    
2. Determine the period T of the oscillation.
    
3. Find the total mechanical energy of the system.
    

**Solution:**

1. **Angular Frequency:**  
    Use the relation:
    
    $\omega = \sqrt{\frac{k}{m}}$
    
    Substitute:
    
    $\omega = \sqrt{\frac{200\,\mathrm{N/m}}{0.50\,\mathrm{kg}}} = \sqrt{400\,\mathrm{s^{-2}}} = 20\,\mathrm{rad/s}.$
2. **Period:**  
    The period is given by:
    
    $T = \frac{2\pi}{\omega} = \frac{2\pi}{20} = 0.314 \quad .$
3. **Total Mechanical Energy:**  
    With amplitude A=0.10 m, the energy is:
    
    $E = \frac{1}{2} k A^2 = \frac{1}{2}(200)(0.10)^2 = \frac{1}{2}(200)(0.01) = 1.0\,\mathrm{J}.$

---

## Problem 2: Energy Distribution in SHM

**Problem Statement:**  
A 0.30‑kg mass is attached to a spring with k=180 N/m and undergoes SHM with amplitude A=0.05 m.

1. Calculate the maximum potential energy and maximum kinetic energy.
    
2. Find the kinetic energy when the mass is at a displacement x=0.03 m.
    

**Solution:**

1. **Maximum Energies:**  
    At the extreme displacement (x=A), the kinetic energy is zero and the potential energy is maximum:
    
    $\quad \quad U_{max} = \frac{1}{2}kA^2 = \frac{1}{2}(180)(0.05)^2 = \frac{1}{2}(180)(0.0025) = 0.225 J$
    
    In an ideal (undamped) oscillator the total energy is constant so the maximum kinetic energy is equal to the maximum potential energy:
    
    $K_{\max} = U_{\max} = 0.225\,\mathrm{J}$.
2. **Kinetic Energy at x = 0.03m 
    First, compute ω:
    
    $\omega = \sqrt{\frac{k}{m}} = \sqrt{\frac{180}{0.30}} = \sqrt{600} \approx 24.49\,\mathrm{rad/s}$.
    
    The total energy is:
    
    $E = \frac{1}{2} m\omega^2A^2 = \frac{1}{2}(0.30)(600)(0.0025) = 0.225\,\mathrm{J}$.
    
    When at displacement xxx, the potential energy is:
    
    $\quad \quad U(x) = \frac{1}{2} k x^2 = \frac{1}{2}(180)(0.03^2) = \frac{1}{2}(180)(0.0009) = 0.081\,\mathrm{J}$.
    
    Then, the kinetic energy is:
    
    $K(x) = E - U(x) = 0.225 - 0.081 = 0.144\,\mathrm{J}$.

---

## Problem 3: Damped Oscillations

**Problem Statement:**  
A 1.0‑kg mass is attached to a spring with k=50 N/m. The system experiences a damping force proportional to the velocity with a damping constant b=2.0 kg/s. The mass is displaced to an amplitude A=0.20 m and released from rest.

1. Determine the damped angular frequency ω.
    
2. Write the expression for the displacement x(t).
    

**Solution:**

1. **Damped Angular Frequency:**  
    The formula for ω′\omega'ω′ is:
    
    $\omega' = \sqrt{\frac{k}{m} - \left(\frac{b}{2m}\right)^2}$
    
    Substitute the values:
    
    $\frac{k}{m} = \frac{50}{1} = 50\,\mathrm{s^{-2}}, \quad \frac{b}{2m} = \frac{2}{2\cdot1} = 1\,\mathrm{s^{-1}}$.
    
    Thus:
    
    $\omega' = \sqrt{50 - (1)^2} = \sqrt{50 - 1} = \sqrt{49} = 7\,\mathrm{rad/s}$.
2. **Displacement Expression:**  
    The general form for damped oscillations is:
    
    $x(t) = A e^{-\frac{b}{2m}t} \cos(\omega' t + \phi)$.
    
    Since the mass is released from rest at maximum displacement, we choose the phase constant ϕ=0 (because x(0)=A when cos⁡(0)=1 and v(0)=0). With A=0.20 m and $\frac{b}{2m} = 1\,\mathrm{s^{-1}}$, we have:
    
    $x(t) = 0.20\,e^{-t}\cos(7t)$.

---

## Problem 4: Forced Oscillations and Resonance

**Problem Statement:**  
A 2.0‑kg mass is attached to a spring with k=32 N/m and is subject to damping with b=4.0 kg/s. A driving force $F(t) = 10\cos (\omega_\text{drive}\,t)$ N is applied.

1. Find the steady‑state amplitude of the oscillations when the driving frequency is $\omega_\text{drive} = 3\,\mathrm{rad/s}$.
    
2. Determine the driving frequency that would produce the maximum steady‑state amplitude (the resonant frequency).
    

**Solution:**

1. **Steady‑State Amplitude for$ $\omega_\text{drive} = 3\,\mathrm{rad/s}$  
    The amplitude $A_\text{steady}​$ in forced oscillations is given by:
    
    $A_\text{steady} = \frac{F_0}{\sqrt{\left(k - m\omega_\text{drive}^2\right)^2 + \left(b\omega_\text{drive}\right)^2}}$
    
    where $F_0 = 10\,\mathrm{N}$.  
    Compute:
    
    - $k - m\omega_\text{drive}^2 = 32 - 2(3^2) = 32 - 18 = 14\,\mathrm{N/m}$.
        
    - $b\omega_\text{drive} = 4 \times 3 = 12\,\mathrm{N\cdot s/m}$.  
        Thus,
        
    
    $\quad \quad A_\text{steady} = \frac{10}{\sqrt{14^2 + 12^2}} = \frac{10}{\sqrt{196 + 144}} = \frac{10}{\sqrt{340}} \approx \frac{10}{18.44} \approx 0.54\,\mathrm{m}.$
2. **Resonant (Optimal) Driving Frequency:**  
    In a damped system the resonant frequency is given by:
    
    $\omega_{\text{res}} = \sqrt{\frac{k}{m} - \left(\frac{b}{2m}\right)^2}​$.
    
    Here,
    
    $\frac{k}{m} = \frac{32}{2} = 16\,\mathrm{s^{-2}}, \quad \frac{b}{2m} = \frac{4}{2\cdot2} = 1\,\mathrm{s^{-1}}.$
    
    Then,
    
    $\omega_{\text{res}} = \sqrt{16 - 1} = \sqrt{15} \approx 3.87\,\mathrm{rad/s}.$
    
    This is the driving frequency that maximizes the steady‑state amplitude.
    

---

## Final Notes

These problems help test your understanding of:

- Deriving the angular frequency and period from the differential equation of motion.
    
- Determining energy distributions in a simple mass–spring oscillator.
    
- Incorporating damping into the equations for oscillatory motion.
    
- Handling forced oscillations and understanding resonance conditions.
    

Try solving these by hand and then compare with the detailed solutions provided. Happy studying!