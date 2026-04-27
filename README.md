# Seven-level-Cascaded-H-Bridge-Multi-Level-Inverter-using-EC-techniques
# ⚡ Harmonic Reduction in Multilevel Inverters using SHE & Optimization Techniques

---

## 🔍 Overview
This project focuses on the design and analysis of a **7-level Cascaded H-Bridge (CHB) Multilevel Inverter** with the objective of reducing harmonic distortion in output waveforms. The work combines **Selective Harmonic Elimination (SHE)** and **Total Harmonic Distortion (THD) minimization** techniques, enhanced using advanced optimization algorithms such as **Particle Swarm Optimization (PSO)**, **Artificial Bee Colony (ABC)**, and **Differential Evolution (DE)**.

The system is modeled and simulated in **MATLAB/Simulink**, and performance is evaluated through FFT-based harmonic analysis.

---

## 🎯 Objectives
- Design a 7-level CHB multilevel inverter  
- Eliminate lower-order harmonics using SHE  
- Minimize overall THD in output voltage and current  
- Apply optimization algorithms to solve nonlinear switching equations  
- Analyze system performance under varying modulation indices  

---

## ⚡ Multilevel Inverter Overview
Multilevel inverters convert DC to AC using multiple voltage levels, improving waveform quality and reducing harmonic distortion. Among various topologies, the **Cascaded H-Bridge (CHB)** inverter is preferred due to:
- Reduced component count  
- Modular structure  
- Absence of clamping diodes and balancing capacitors  

---

## 🧠 Methodology

### 1. System Design
- Developed a **7-level CHB inverter model**
- Each phase consists of cascaded H-bridge cells
- Switching devices calculated as:
  - Switches = (m − 1) × 2 = 12  
  - DC sources = (m − 1) / 2 = 3  

### 2. Harmonic Reduction Techniques
- **Selective Harmonic Elimination (SHE):**
  - Eliminates specific lower-order harmonics (e.g., 3rd, 5th)
- **THD Minimization:**
  - Reduces total harmonic distortion across waveform  

### 3. Optimization Techniques
To solve nonlinear transcendental equations for switching angles:
- Particle Swarm Optimization (PSO)  
- Artificial Bee Colony (ABC)  
- Differential Evolution (DE)  

### 4. Simulation & Analysis
- Modeled using MATLAB/Simulink  
- FFT analysis performed on:
  - Pole voltage  
  - Line voltage  
  - Output current  

---

## 📊 Key Results
- Pole Voltage THD ≈ **31.68%**  
- Line Voltage THD ≈ **14.46%**  
- Improved harmonic performance using combined SHE + THD approach  
- DE algorithm showed better accuracy and convergence  

---

## 📈 Performance Analysis
- THD varies with modulation index (MI = 0.57, 0.8)  
- At lower MI, some voltage levels are not visible due to switching angle limits  
- Combined SHE + THD provides:
  - Better harmonic elimination  
  - Reduced need for external filters  

---

## 🛠️ Tools & Technologies
- **MATLAB**
- **Simulink**
- Power Electronics Design
- Optimization Algorithms (PSO, ABC, DE)
- FFT Analysis

---

## 🔬 Core Concepts
- Multilevel Inverters  
- Cascaded H-Bridge Topology  
- Fourier Series Analysis  
- Harmonic Elimination  
- Optimization Techniques  

---

## 📷 Simulation Results
*(Add your waveform images / FFT results here)*

---

## ⚖️ Limitations
- SHE alone cannot minimize total THD  
- THD minimization does not eliminate specific harmonics  
- Nonlinear equations are complex and computationally intensive  

---

## 🚀 Conclusion
The project demonstrates that combining **Selective Harmonic Elimination (SHE)** with **THD minimization** provides superior performance compared to using either technique alone. The integration of optimization algorithms enables efficient determination of switching angles, resulting in improved waveform quality and reduced harmonic distortion.

---

## 🔮 Future Scope
- Hardware implementation of CHB inverter  
- Real-time control using DSP/FPGA  
- AI-based adaptive harmonic optimization  
- Integration with renewable energy systems  

---

## 📚 References
- J. Rodriguez et al., *Multilevel Inverters: A Survey of Topologies*  
- IEEE papers on SHE and THD optimization  
- Research on PSO, ABC, and DE algorithms  

---

## 👤 Author
**M. Lakshmi Sravanthi**  
Electrical & Electronics Engineering  
