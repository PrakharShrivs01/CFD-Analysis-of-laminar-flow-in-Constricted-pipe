# 💨 CFD Simulation of Laminar Flow in a 3D Constricted Pipe

This project simulates incompressible, steady-state laminar flow through a 3D pipe with a constriction using **ANSYS Fluent**. It aims to study the pressure drop and velocity increase due to a narrowing cross-section, in accordance with the continuity equation and Bernoulli’s principle.

---

## 🛠️ Tools Used
- **ANSYS DesignModeler** – 3D geometry creation  
- **ANSYS Meshing** – Mesh generation with refinement near the contraction  
- **ANSYS Fluent** – Solver setup, simulation, and post-processing

---

## 🎯 Project Objectives
- Create a 3D geometry of a pipe with a contraction section  
- Simulate steady laminar flow of water through the geometry  
- Analyze velocity and pressure variation through the contraction  
- Validate results with basic fluid mechanics principles

---

## 📐 Geometry Overview
- Cylindrical pipe with a gradual contraction  
- Inlet and outlet zones added to avoid boundary distortion  
- Symmetric design for simplified interpretation

---

## 🧩 Meshing Strategy
- Structured hexahedral mesh with refinement near the contraction  
- Wall-adjacent cells refined to better capture boundary layer behavior  
- Mesh independence not tested (basic learning-level project)

---

## ⚙️ Simulation Details
- **Solver Type:** Pressure-based  
- **Flow Type:** Steady-state, laminar  
- **Fluid:** Water (incompressible)  
- **Inlet BC:** Velocity inlet (0.1 m/s)  
- **Outlet BC:** Pressure outlet (0 Pa gauge)  
- **Walls:** No-slip condition  
- **Convergence Criteria:** Residuals < 1e-4

---

## 📊 Results
- **Velocity increased** at the constricted section as expected  
- **Pressure dropped** in the contraction region  
- Velocity streamlines and pressure contours confirm laminar, symmetric flow behavior  
- Results qualitatively align with theoretical fluid flow predictions

---

## 📷 Sample Output Plots
*(Insert your simulation screenshots below)*

- Geometry & Mesh  
- Velocity Contour  
- Pressure Contour  
- Residual Convergence Plot  

---

## ✅ Key Learnings
- Full CFD workflow: design → mesh → simulate → analyze  
- Importance of boundary condition setup and mesh refinement  
- Visualization of how pressure and velocity respond to changing pipe geometry

---

## 📁 Project Status
✔️ Completed – all steps followed from video tutorial  
🔰 Beginner-level – intended for educational and resume-building purposes

---

## 📚 References
- [Video Tutorial Used](https://youtu.be/KWP0nl_Qf-0)  
- ANSYS Fluent Documentation  
- Fluid Mechanics (Bernoulli’s Principle, Continuity Equation)

---

## 🙋‍♂️ Author
**Prakhar Shrivas**  
*Beginner in CFD, passionate about simulation and mechanical systems*  
*Looking for opportunities in core/mechanical/data science fields*
