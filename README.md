# *Escherichia coli* Enzyme-Constrained Metabolic Model Optimization

This project is based on **[GECKO 3.0](https://github.com/SysBioChalmers/GECKO)** and focuses on calibrating and optimizing the *Escherichia coli* (*E. coli*) metabolic model (iML1515)

---

## 📌 About

- **Objective**: Optimize the *E. coli* metabolic model within the GECKO framework by applying protein constraints and *k*<sub>cat</sub> calibration, ensuring ecModel predictions align with experimental data.  
- **Base Model**: iML1515 (BiGG)  
- **Highlights**:
  - Integrates multi-source enzyme data, including **in vivo enzyme activities（*k*<sub>app</sub>）**, **BRENDA**, and **DLKcat**, to significantly improve *k*<sub>cat</sub> coverage.  
  - Completes **Isozyme** information, enhancing enzyme redundancy handling and flux prediction.  
  - Enables exploration of overflow metabolism and key metabolic pathway regulation.

---

## 🖥️ Installation

### Requirements
- MATLAB R2022b or later  
- RAVEN Toolbox 2.8.3 or later  
- Python 3.10+ (optional, for data preprocessing)  
