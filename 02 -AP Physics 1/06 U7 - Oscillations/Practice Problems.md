## Problem 1: Mass–Spring System (SHM Basics)

**Problem Statement:**  
A 0.50‑kg mass is attached to a spring with a spring constant k=200 N/mk = 200\,\mathrm{N/m}k=200N/m. The mass is displaced 0.10 m from equilibrium and then released from rest.

1. Calculate the angular frequency ω\omegaω.
    
2. Determine the period TTT of the oscillation.
    
3. Find the total mechanical energy of the system.
    

**Solution:**

1. **Angular Frequency:**  
    Use the relation:
    
    ω=km\omega = \sqrt{\frac{k}{m}}ω=mk​​
    
    Substitute:
    
    ω=200 N/m0.50 kg=400 s−2=20 rad/s.\omega = \sqrt{\frac{200\,\mathrm{N/m}}{0.50\,\mathrm{kg}}} = \sqrt{400\,\mathrm{s^{-2}}} = 20\,\mathrm{rad/s}.ω=0.50kg200N/m​​=400s−2​=20rad/s.
2. **Period:**  
    The period is given by:
    
    T=2πω=2π20=0.314 s.T = \frac{2\pi}{\omega} = \frac{2\pi}{20} = 0.314\,\mathrm{s}.T=ω2π​=202π​=0.314s.
3. **Total Mechanical Energy:**  
    With amplitude A=0.10 mA = 0.10\,\mathrm{m}A=0.10m, the energy is:
    
    E=12kA2=12(200)(0.10)2=12(200)(0.01)=1.0 J.E = \frac{1}{2} k A^2 = \frac{1}{2}(200)(0.10)^2 = \frac{1}{2}(200)(0.01) = 1.0\,\mathrm{J}.E=21​kA2=21​(200)(0.10)2=21​(200)(0.01)=1.0J.

---

## Problem 2: Energy Distribution in SHM

**Problem Statement:**  
A 0.30‑kg mass is attached to a spring with k=180 N/mk = 180\,\mathrm{N/m}k=180N/m and undergoes SHM with amplitude A=0.05 mA = 0.05\,\mathrm{m}A=0.05m.

1. Calculate the maximum potential energy and maximum kinetic energy.
    
2. Find the kinetic energy when the mass is at a displacement x=0.03 mx = 0.03\,\mathrm{m}x=0.03m.
    

**Solution:**

1. **Maximum Energies:**  
    At the extreme displacement (x=Ax = Ax=A), the kinetic energy is zero and the potential energy is maximum:
    
    Umax⁡=12kA2=12(180)(0.05)2=12(180)(0.0025)=0.225 J.U_{\max} = \frac{1}{2} k A^2 = \frac{1}{2}(180)(0.05)^2 = \frac{1}{2}(180)(0.0025) = 0.225\,\mathrm{J}.Umax​=21​kA2=21​(180)(0.05)2=21​(180)(0.0025)=0.225J.
    
    In an ideal (undamped) oscillator the total energy is constant so the maximum kinetic energy is equal to the maximum potential energy:
    
    Kmax⁡=Umax⁡=0.225 J.K_{\max} = U_{\max} = 0.225\,\mathrm{J}.Kmax​=Umax​=0.225J.
2. **Kinetic Energy at x=0.03 mx = 0.03\,\mathrm{m}x=0.03m:**  
    First, compute ω\omegaω:
    
    ω=km=1800.30=600≈24.49 rad/s.\omega = \sqrt{\frac{k}{m}} = \sqrt{\frac{180}{0.30}} = \sqrt{600} \approx 24.49\,\mathrm{rad/s}.ω=mk​​=0.30180​​=600​≈24.49rad/s.
    
    The total energy is:
    
    E=12mω2A2=12(0.30)(600)(0.0025)=0.225 J.E = \frac{1}{2} m\omega^2A^2 = \frac{1}{2}(0.30)(600)(0.0025) = 0.225\,\mathrm{J}.E=21​mω2A2=21​(0.30)(600)(0.0025)=0.225J.
    
    When at displacement xxx, the potential energy is:
    
    U(x)=12kx2=12(180)(0.032)=12(180)(0.0009)=0.081 J.U(x) = \frac{1}{2} k x^2 = \frac{1}{2}(180)(0.03^2) = \frac{1}{2}(180)(0.0009) = 0.081\,\mathrm{J}.U(x)=21​kx2=21​(180)(0.032)=21​(180)(0.0009)=0.081J.
    
    Then, the kinetic energy is:
    
    K(x)=E−U(x)=0.225−0.081=0.144 J.K(x) = E - U(x) = 0.225 - 0.081 = 0.144\,\mathrm{J}.K(x)=E−U(x)=0.225−0.081=0.144J.

---

## Problem 3: Damped Oscillations

**Problem Statement:**  
A 1.0‑kg mass is attached to a spring with k=50 N/mk = 50\,\mathrm{N/m}k=50N/m. The system experiences a damping force proportional to the velocity with a damping constant b=2.0 kg/sb = 2.0\,\mathrm{kg/s}b=2.0kg/s. The mass is displaced to an amplitude A=0.20 mA = 0.20\,\mathrm{m}A=0.20m and released from rest.

1. Determine the damped angular frequency ω′\omega'ω′.
    
2. Write the expression for the displacement x(t)x(t)x(t).
    

**Solution:**

1. **Damped Angular Frequency:**  
    The formula for ω′\omega'ω′ is:
    
    ω′=km−(b2m)2.\omega' = \sqrt{\frac{k}{m} - \left(\frac{b}{2m}\right)^2}.ω′=mk​−(2mb​)2​.
    
    Substitute the values:
    
    km=501=50 s−2,b2m=22⋅1=1 s−1.\frac{k}{m} = \frac{50}{1} = 50\,\mathrm{s^{-2}}, \quad \frac{b}{2m} = \frac{2}{2\cdot1} = 1\,\mathrm{s^{-1}}.mk​=150​=50s−2,2mb​=2⋅12​=1s−1.
    
    Thus:
    
    ω′=50−(1)2=50−1=49=7 rad/s.\omega' = \sqrt{50 - (1)^2} = \sqrt{50 - 1} = \sqrt{49} = 7\,\mathrm{rad/s}.ω′=50−(1)2​=50−1​=49​=7rad/s.
2. **Displacement Expression:**  
    The general form for damped oscillations is:
    
    x(t)=Ae−b2mtcos⁡(ω′t+ϕ).x(t) = A e^{-\frac{b}{2m}t} \cos(\omega' t + \phi).x(t)=Ae−2mb​tcos(ω′t+ϕ).
    
    Since the mass is released from rest at maximum displacement, we choose the phase constant ϕ=0\phi = 0ϕ=0 (because x(0)=Ax(0)=Ax(0)=A when cos⁡(0)=1\cos(0)=1cos(0)=1 and v(0)=0v(0)=0v(0)=0). With A=0.20 mA = 0.20\,\mathrm{m}A=0.20m and b2m=1 s−1\frac{b}{2m} = 1\,\mathrm{s^{-1}}2mb​=1s−1, we have:
    
    x(t)=0.20 e−tcos⁡(7t).x(t) = 0.20\,e^{-t}\cos(7t).x(t)=0.20e−tcos(7t).

---

## Problem 4: Forced Oscillations and Resonance

**Problem Statement:**  
A 2.0‑kg mass is attached to a spring with k=32 N/mk = 32\,\mathrm{N/m}k=32N/m and is subject to damping with b=4.0 kg/sb = 4.0\,\mathrm{kg/s}b=4.0kg/s. A driving force F(t)=10cos⁡(ωdrive t)F(t) = 10\cos (\omega_\text{drive}\,t)F(t)=10cos(ωdrive​t) N is applied.

1. Find the steady‑state amplitude of the oscillations when the driving frequency is ωdrive=3 rad/s\omega_\text{drive} = 3\,\mathrm{rad/s}ωdrive​=3rad/s.
    
2. Determine the driving frequency that would produce the maximum steady‑state amplitude (the resonant frequency).
    

**Solution:**

1. **Steady‑State Amplitude for ωdrive=3 rad/s\omega_\text{drive} = 3\,\mathrm{rad/s}ωdrive​=3rad/s:**  
    The amplitude AsteadyA_\text{steady}Asteady​ in forced oscillations is given by:
    
    Asteady=F0(k−mωdrive2)2+(bωdrive)2,A_\text{steady} = \frac{F_0}{\sqrt{\left(k - m\omega_\text{drive}^2\right)^2 + \left(b\omega_\text{drive}\right)^2}},Asteady​=(k−mωdrive2​)2+(bωdrive​)2​F0​​,
    
    where F0=10 NF_0 = 10\,\mathrm{N}F0​=10N.  
    Compute:
    
    - k−mωdrive2=32−2(32)=32−18=14 N/mk - m\omega_\text{drive}^2 = 32 - 2(3^2) = 32 - 18 = 14\,\mathrm{N/m}k−mωdrive2​=32−2(32)=32−18=14N/m.
        
    - bωdrive=4×3=12 N⋅s/mb\omega_\text{drive} = 4 \times 3 = 12\,\mathrm{N\cdot s/m}bωdrive​=4×3=12N⋅s/m.  
        Thus,
        
    
    Asteady=10142+122=10196+144=10340≈1018.44≈0.54 m.A_\text{steady} = \frac{10}{\sqrt{14^2 + 12^2}} = \frac{10}{\sqrt{196 + 144}} = \frac{10}{\sqrt{340}} \approx \frac{10}{18.44} \approx 0.54\,\mathrm{m}.Asteady​=142+122​10​=196+144​10​=340​10​≈18.4410​≈0.54m.
2. **Resonant (Optimal) Driving Frequency:**  
    In a damped system the resonant frequency is given by:
    
    ωres=km−(b2m)2.\omega_{\text{res}} = \sqrt{\frac{k}{m} - \left(\frac{b}{2m}\right)^2}.ωres​=mk​−(2mb​)2​.
    
    Here,
    
    km=322=16 s−2,b2m=42⋅2=1 s−1.\frac{k}{m} = \frac{32}{2} = 16\,\mathrm{s^{-2}}, \quad \frac{b}{2m} = \frac{4}{2\cdot2} = 1\,\mathrm{s^{-1}}.mk​=232​=16s−2,2mb​=2⋅24​=1s−1.
    
    Then,
    
    ωres=16−1=15≈3.87 rad/s.\omega_{\text{res}} = \sqrt{16 - 1} = \sqrt{15} \approx 3.87\,\mathrm{rad/s}.ωres​=16−1​=15​≈3.87rad/s.
    
    This is the driving frequency that maximizes the steady‑state amplitude.
    

---

## Final Notes

These problems help test your understanding of:

- Deriving the angular frequency and period from the differential equation of motion.
    
- Determining energy distributions in a simple mass–spring oscillator.
    
- Incorporating damping into the equations for oscillatory motion.
    
- Handling forced oscillations and understanding resonance conditions.
    

Try solving these by hand and then compare with the detailed solutions provided. Happy studying!