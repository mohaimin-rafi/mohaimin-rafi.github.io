---
title: "Multiphysics Modeling of Hybrid Laminated Composite Conductors Under a DC Field"
collection: portfolio
permalink: /portfolio/thesis-multiphysics-modeling/
link: /files/Undergraduate_Thesis_Presentation.pdf
slidesurl: /files/Undergraduate_Thesis_Presentation.pdf
excerpt: "Undergraduate Thesis (Nov 2023 – Mar 2025) supervised by Dr. Shaikh Reaz Ahmed, Professor, Dept. of ME, BUET. Developed a semi-analytical numerical framework (FDM, MATLAB) validated with COMSOL Multiphysics."
---

**Undergraduate Thesis** | Nov 2023 – Mar 2025  
**Supervisor:** Dr. Shaikh Reaz Ahmed, Professor, Department of Mechanical Engineering, BUET  
📄 **Presentation:** [Download / View Presentation PDF](/files/Undergraduate_Thesis_Presentation.pdf)

### Abstract
Modern electronics, aerospace systems, and high-power applications increasingly require conductors that combine superior electrical conductivity, high thermal dissipation capability, and structural mechanical integrity. In this undergraduate thesis, a semi-analytical multiphysics modeling framework was developed to predict the coupled electro-thermo-mechanical response of hybrid particle-reinforced laminated composite conductors under steady DC current. A Displacement Function ($\psi$) formulation was introduced to reduce the coupled 2D mechanical equilibrium equations to a single fourth-order partial differential equation, eliminating the need to solve coupled displacement components simultaneously. Temperature-dependent electrical resistivity and thermal conductivity were incorporated with non-linear Joule heating. The governing equations were discretized using a finite difference network ($401 \times 101$ mesh) and solved iteratively. The model was applied to Al-SiC and Al-Graphene symmetric laminates with continuous power-law volume fraction gradation ($V_f = m \cdot x^n$) and intermediate bonding layers (Silver Filled Epoxy, Graphene-Epoxy, Silver Nanowire Paste). Predictions were validated against Finite Element Method (COMSOL Multiphysics) simulations, demonstrating excellent agreement with over 85% reduction in computational effort compared to fine FEA meshes.

### Key Contributions & Methodology
* **Formulated governing equations and numerical model** for hybrid laminated composite conductors, introducing a Displacement Potential Function approach that reduces the three-variable mechanical equilibrium equations to a single, solvable fourth-order partial differential equation.
* **Implemented the Finite Difference Method (FDM)** with iterative solvers to solve the fully coupled electro-thermo-mechanical system, incorporating non-linear, temperature-dependent material properties for realistic stress prediction.
* **Developed and optimized computational code in MATLAB**, validating voltage, temperature, and stress-profile results against industry-standard FEA software (COMSOL Multiphysics) to establish model credibility.
* **Core expertise applied:** numerical methods (FDM, iterative solvers), multiphysics modeling, classical lamination theory, heat transfer, and MATLAB programming.
