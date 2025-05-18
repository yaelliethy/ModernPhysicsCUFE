
# 📘 Modern Physics – Ultimate Study Guide  
**Based on final revision materials**  
**All topics, formulas, laws, graphs, and theoretical insights included**  
**GitHub-compatible equation formatting**

---

## 🔹 **Topic 1: Special Relativity**  

### ✅ Key Concepts:  
- Speed of light $c = 3 \times 10^8\, \text{m/s}$ is constant for all observers.  
- **Time dilation**: $\Delta t = \gamma \Delta t_0$  
- **Length contraction**: $L = L_0 / \gamma$  
- **Relativistic momentum**: $p = \gamma mv$  
- **Energy-momentum relation**: $E^2 = (pc)^2 + (mc^2)^2$  
- **Kinetic energy**: $K = (\gamma - 1)mc^2$  
- **Velocity addition**: $u' = \frac{u - v}{1 - uv/c^2}$  

### 📈 Graphs:  
1. **Classical vs Relativistic Momentum vs Velocity**  
   ![Classical vs Relativistic Momentum](/graphs/momentum_comparison.png)  
2. **Energy vs Velocity**  
   ![Energy vs Velocity](/graphs/energy_comparison.png)  
3. **Regions of Mechanics**  
   ![Regions of Mechanics](/graphs/mechanics_regions.png)  

### 💡 Theoretical Insight:  
- **Mass-energy equivalence**: $E = mc^2$ explains nuclear reactions.  
- **Derivation of Lorentz factor $\gamma$**:  
  From Einstein's postulates:  
  $$\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}$$  
  Derived using invariance of spacetime interval in inertial frames.

---

## 🔹 **Topic 2: Photoelectric Effect & Compton Scattering**  

### ✅ Photoelectric Effect:  
- **Einstein Equation**:  
  $$K_{\text{max}} = hf - \phi$$  
- **Stopping Potential**:  
  $$eV_s = K_{\text{max}} = hf - \phi$$  
- **Threshold Frequency**:  
  $$f_c = \frac{\phi}{h}$$  

### ✅ Compton Scattering:  
- **Compton Wavelength**:  
  $$\lambda_c = \frac{h}{m_e c} = 0.00243\, \text{nm}$$  
- **Compton Shift**:  
  $$\Delta \lambda = \lambda_c (1 - \cos\theta)$$  
- **Recoil Electron KE**:  
  $$K_e = hc\left( \frac{1}{\lambda} - \frac{1}{\lambda'} \right)$$  
- **Derivation from Conservation Laws**:  
  1. Energy: $\frac{hc}{\lambda} = \frac{hc}{\lambda'} + K_e$  
  2. Momentum (x/y):  
     $$\frac{h}{\lambda} = \frac{h}{\lambda'} \cos\theta + p_e \cos\phi \quad \text{(x-direction)}$$  
     $$0 = \frac{h}{\lambda'} \sin\theta - p_e \sin\phi \quad \text{(y-direction)}$$  
  Solve these → derive $\Delta \lambda$  

### 📈 Graphs:  
1. **Stopping Potential vs Frequency**  
   ![Stopping Potential vs Frequency](/graphs/stopping_potential.png)  
2. **Photoelectric Current vs Applied Voltage**  
   ![Photoelectric Current vs Voltage](/graphs/photoelectric_iv_curve.png)  
3. **Compton Shift vs Scattering Angle**  
   ![Compton Shift vs Angle](/graphs/compton_shift.png)  

---

## 🔹 **Topic 3: Wave-Particle Duality & Uncertainty Principle**  

### ✅ De Broglie Hypothesis:  
- **Matter waves**:  
  $$\lambda = \frac{h}{p} = \frac{h}{mv}$$  
- **Accelerated electrons**:  
  $$\lambda = \frac{h}{\sqrt{2meV}}, \quad V \text{ in volts}$$  

### ✅ Heisenberg Uncertainty Principle:  
- **Position-Momentum**:  
  $$\Delta x \cdot \Delta p \geq \frac{\hbar}{2}$$  
- **Energy-Time**:  
  $$\Delta E \cdot \Delta t \geq \frac{\hbar}{2}$$  
- **Normalization Condition**:  
  $$\int_{-\infty}^{\infty} |\psi(x)|^2 dx = 1$$  
  Ensures total probability is 1.  

### 📈 Graphs:  
1. **De Broglie Wavelength vs Particle Speed**  
   ![De Broglie Wavelength vs Speed](/graphs/de_broglie_wavelength.png)  
2. **Uncertainty Principle (ΔxΔp ≥ ħ/2)**  
   ![Uncertainty Principle](/graphs/heisenberg_uncertainty.png)  

---

## 🔹 **Topic 4: Quantum Mechanics – Particle in a Box**  

### ✅ Infinite Square Well:  
- **Energy Levels**:  
  $$E_n = \frac{n^2 h^2}{8mL^2}$$  
- **Wavefunctions**:  
  $$\psi_n(x) = \sqrt{\frac{2}{L}} \sin\left(\frac{n\pi x}{L}\right)$$  
- **Probability Density**:  
  $$P(x) = |\psi_n(x)|^2$$  

### ✅ Finite Potential Well:  
- **Wavefunction Decay**:  
  $$\psi(x) \propto e^{-\alpha x}, \quad \alpha = \sqrt{\frac{2m(U_0 - E)}{\hbar^2}}$$  

### 📈 Graphs:  
1. **Energy Levels in Infinite Square Well**  
   ![Energy Levels](/graphs/particle_in_box_energy_levels.png)  
2. **Probability Density for Ground State**  
   ![Ground State Probability](/graphs/probability_density.png)  

---

## 🔹 **Topic 5: Step Potential & Tunneling**  

### ✅ Transmission & Reflection Coefficients:  
- **For $E < U_0$**:  
  $$T \propto e^{-2\alpha L}, \quad \alpha = \sqrt{\frac{2m(U_0 - E)}{\hbar^2}}$$  
- **For $E > U_0$**:  
  $$R = \left(\frac{k_1 - k_2}{k_1 + k_2}\right)^2, \quad T = \frac{4k_1 k_2}{(k_1 + k_2)^2}$$  

### 📈 Graphs:  
1. **Transmission vs Barrier Thickness**  
   ![Tunneling Transmission](/graphs/tunneling_transmission.png)  

---

## 🔹 **Topic 6: Atomic Structure & Spectra**  

### ✅ Hydrogen Atom:  
- **Bohr Radius**:  
  $$a_0 = 0.0529\, \text{nm}$$  
- **Energy Levels**:  
  $$E_n = -\frac{13.6 Z^2}{n^2} \text{eV}$$  
- **Rydberg Formula**:  
  $$\frac{1}{\lambda} = R_H \left( \frac{1}{n_f^2} - \frac{1}{n_i^2} \right)$$  

### ✅ Spectral Series:  
| Series | Transition To | Wavelength Range |  
|--------|---------------|------------------|  
| **Lyman** | $n_f = 1$ | UV |  
| **Balmer** | $n_f = 2$ | Visible |  
| **Paschen** | $n_f = 3$ | Infrared |  

### 📈 Graphs:  
1. **Hydrogen Energy Levels with Transitions**  
   ![Hydrogen Energy Levels](/graphs/hydrogen_energy_levels.png)  
2. **Franck-Hertz Current vs Voltage**  
   ![Franck-Hertz](/graphs/franck_hertz.png)  

---

## 🔹 **Topic 7: Quantum Numbers & Pauli Exclusion Principle**  

### ✅ Quantum Numbers:  
| Name | Symbol | Range | Meaning |  
|------|--------|-------|---------|  
| Principal | $n$ | $1, 2, 3, ...$| Energy level |  
| Azimuthal | $\ell$ | $0$ to $n-1$ | Orbital shape (s, p, d, f) |  
| Magnetic | $m_\ell$ | $-\ell$ to $+\ell$ | Orientation |  
| Spin | $m_s$ | $\pm \frac{1}{2}$ | Spin direction |  

### ✅ Pauli Exclusion Principle:  
- No two electrons share the same four quantum numbers.  
- Max electrons per shell: $2n^2$ (e.g., M shell: 18 electrons).  

### 📈 Graphs:  
1. **s, p, d Orbital Shapes**  
   ![s Orbital](/graphs/s_orbital.png)  
   ![p Orbital](/graphs/p_orbital.png)  
   ![d Orbital](/graphs/d_orbital.png)  

---

## 🔹 **Topic 8: Molecular Bonding & Crystal Structures**  

### ✅ Bond Types:  
- **Covalent**: Shared electrons (e.g., diamond)  
- **Ionic**: Transferred electrons (e.g., NaCl)  
- **Metallic**: Delocalized electrons  
- **Van der Waals**: Weak dipole forces  

### ✅ Crystal Structures:  
| Structure | Atoms/Unit Cell | APF | Lattice Constant |  
|----------|------------------|-----|------------------|  
| SC       | 1                | 0.52 | $a = 2r$ |  
| BCC      | 2                | 0.68 | $a = \frac{4r}{\sqrt{3}}$ |  
| FCC      | 4                | 0.74 | $a = 2\sqrt{2} r$ |  

### ✅ Lennard-Jones Potential:  
- $U(r) = \frac{A}{r^{12}} - \frac{B}{r^6}$  
- Minimum at $r_0 = \left(\frac{2A}{B}\right)^{1/6}$, $U_{\text{min}} = -\frac{B^2}{4A}$  

### 📈 Graphs:  
1. **Lennard-Jones Potential vs Interatomic Distance**  
   ![Lennard-Jones](/graphs/lennard_jones.png)  
2. **Miller Plane (101) in Cubic Lattice**  
   ![Miller Plane (101)](/graphs/miller_plane_101.png)  

---

## 🔹 **Topic 9: Solid State Physics**  

### ✅ Crystallography:  
- **Miller Indices**: Intercepts → reciprocals → integers → enclose in (hkl).  
- **Density**:  
  $$\rho = \frac{nM}{a^3 N_A}$$  
- **Atomic Packing Factor (APF)**:  
  $$\text{APF} = \frac{\text{Volume of atoms in unit cell}}{\text{Unit cell volume}}$$  

### 📈 Graphs:  
1. **Miller Plane (101) in Cubic Lattice**  
   ![Miller Plane (101)](/graphs/miller_plane_101.png)  

---

## 🔹 **Topic 10: Band Theory of Solids**  

### ✅ Energy Bands:  
- **Valence Band**: Filled or partially filled.  
- **Conduction Band**: Free electrons reside here.  
- **Forbidden Gap**: $E_g$ determines material type:  
  - Insulator: $E_g > 5\, \text{eV}$  
  - Semiconductor: $E_g \approx 1\, \text{eV}$  
  - Metal: No gap (overlapping bands)  

### ✅ Carrier Dynamics:  
- **Drift Current**:  
  $$J = q n \mu_n E$$  
- **Diffusion Current**:  
  $$J = q D \frac{dn}{dx}$$  

### 📈 Graphs:  
1. **Energy Band Diagram (Thermal Equilibrium)**  
   ![Band Diagram Equilibrium](/graphs/band_diagram_equilibrium.png)  
2. **Carrier Concentration vs Temperature**  
   ![Carrier Concentration](/graphs/carrier_concentration_vs_temp.png)  

---

## 🔹 **Topic 11: p-n Junctions & Semiconductors**  

### ✅ p-n Junction:  
- **Built-in Voltage**:  
  $$V_{bi} = \frac{kT}{q} \ln\left(\frac{N_A N_D}{n_i^2}\right)$$  
- **Depletion Width**:  
  $$W = \sqrt{\frac{2\epsilon(V_{bi} - V)}{q} \left(\frac{1}{N_A} + \frac{1}{N_D}\right)}$$  
- **Bias Effects**:  
  - **Forward Bias**: Lowers barrier → large current  
  - **Reverse Bias**: Raises barrier → small saturation current  

### ✅ Tunnel Diode/Zener Diode:  
- **Tunnel Diode**: Negative resistance region due to quantum tunneling.  
- **Zener Diode**: Reverse breakdown via tunneling.  

### 📈 Graphs:  
1. **p-n Junction I-V Curve**  
   ![p-n I-V Curve](/graphs/pn_junction_iv_curve.png)  
2. **Energy Band Diagram (Forward/Reverse Bias)**  
   ![Forward Bias Band Diagram](/graphs/forward_bias_band_diagram.png)  

---

## 🔹 **Chapter-by-Chapter Formula Summary**  

### 📌 Chapter 1: Special Relativity  
- Lorentz factor:  
  $$\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}$$  
- Energy-momentum relation:  
  $$E^2 = (pc)^2 + (mc^2)^2$$  

### 📌 Chapter 2: Photoelectric & Compton  
- Photoelectric:  
  $$K_{\text{max}} = hf - \phi$$  
- Compton shift:  
  $$\Delta \lambda = \lambda_c (1 - \cos\theta)$$  

### 📌 Chapter 3: Wave-Particle Duality  
- De Broglie wavelength:  
  $$\lambda = h/p$$  
- Heisenberg uncertainty:  
  $$\Delta x \cdot \Delta p \geq \frac{\hbar}{2}$$  

### 📌 Chapter 4: Particle in a Box  
- Energy levels:  
  $$E_n = \frac{n^2 h^2}{8mL^2}$$  

### 📌 Chapter 5: Step Potential & Tunneling  
- Transmission coefficient:  
  $$T \propto e^{-2\alpha L}, \quad \alpha = \sqrt{\frac{2m(U_0 - E)}{\hbar^2}}$$  

### 📌 Chapter 6: Atomic Structure  
- Hydrogen energy levels:  
  $$E_n = -\frac{13.6 Z^2}{n^2} \text{eV}$$  
- Rydberg formula:  
  $$\frac{1}{\lambda} = R_H \left( \frac{1}{n_f^2} - \frac{1}{n_i^2} \right)$$  

### 📌 Chapter 7: Quantum Numbers  
- Pauli exclusion: No two electrons share $n, \ell, m_\ell, m_s$.  

### 📌 Chapter 8: Molecular Bonding  
- Lennard-Jones potential:  
  $$U(r) = \frac{A}{r^{12}} - \frac{B}{r^6}$$  

### 📌 Chapter 9: Solid State Physics  
- Miller indices: Found via intercepts → reciprocals → integers → enclose in (hkl).  

### 📌 Chapter 10: Band Theory  
- Carrier concentration:  
  $$n_i = A T^{3/2} e^{-E_g/(2kT)}$$  

### 📌 Chapter 11: p-n Junctions  
- Drift/diffusion currents:  
  $$J = q n \mu_n E, \quad J = q D \frac{dn}{dx}$$  

---

## 📊 **Graph Checklist**  
All graphs are stored in the `/graphs` directory:  

| Topic | Graph |  
|-------|-------|  
| Special Relativity | Classical vs Relativistic Momentum vs Velocity |  
| Special Relativity | Energy vs Velocity |  
| Special Relativity | Regions of Mechanics |  
| Photoelectric Effect | Stopping Potential vs Frequency |  
| Photoelectric Effect | Photoelectric Current vs Voltage |  
| Compton Scattering | Compton Shift vs Scattering Angle |  
| Particle in a Box | Infinite Square Well Energy Levels |  
| Particle in a Box | Probability Density for n=1, n=2 |  
| Tunneling | Transmission vs Barrier Thickness |  
| Hydrogen Atom | Hydrogen Energy Levels with Transitions |  
| Franck-Hertz | Current vs Voltage |  
| Band Theory | Energy Band Diagram (Equilibrium) |  
| Band Theory | Carrier Concentration vs Temperature |  
| p-n Junctions | p-n Junction I-V Curve |  
| p-n Junctions | Energy Band Diagram (Forward/Reverse Bias) |  
| Blackbody Radiation | Blackbody Spectrum at 3000 K, 5000 K, 7000 K |  

---

## 🧠 **Theoretical Foundations**  
### ✅ Wave-Particle Duality:  
- Double-slit experiment shows interference with single particles.  

### ✅ Quantum Tunneling:  
- Explains alpha decay and tunnel diodes.  

### ✅ Atomic Stability:  
- Heisenberg principle prevents electron collapse into nucleus.  

---

## 🔁 **Key Derivations**  
1. **Compton Shift**: From conservation of energy and momentum.  
2. **Hydrogen Energy Levels**: From Bohr model and Schrödinger equation.  
3. **Tunneling Transmission**: $T \propto e^{-2\alpha L}$.  
4. **Carrier Concentration**: $n_i = A T^{3/2} e^{-E_g/(2kT)}$.  

---

## 📋 **Formula Summary Table**  

| Topic | Formula |  
|-------|---------|  
| Relativistic Momentum | $p = \gamma mv$ |  
| Compton Shift | $\Delta \lambda = \lambda_c (1 - \cos\theta)$ |  
| De Broglie | $\lambda = h/p$ |  
| Energy-Time Uncertainty | $\Delta E \cdot \Delta t \geq \hbar/2$ |  
| Hydrogen Energy | $E_n = -\frac{13.6 Z^2}{n^2} \text{eV}$ |  
| Carrier Concentration | $n_i = A T^{3/2} e^{-E_g/(2kT)}$ |  
| Built-in Voltage | $V_{bi} = \frac{kT}{q} \ln\left(\frac{N_A N_D}{n_i^2}\right)$ |  
| Drift Current | $J = q n \mu_n E$ |  
| Diffusion Current | $J = q D \frac{dn}{dx}$ |  
| Blackbody Peak | $\lambda_{\text{max}} T = 2.898 \times 10^{-3}\ \text{m} \cdot \text{K}$
 |  

---

