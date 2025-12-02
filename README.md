# *Escherichia coli* Enzyme-Constrained Model Construction

This project constructs a high-quality enzyme-constrained model of *Escherichia coli* (*E. coli*) based on **[GECKO 3.0](https://github.com/SysBioChalmers/GECKO)**.

---

## 📌 About

- **Objective**: Construct an enzyme-constrained model of *E. coli* using the GECKO toolbox by applying enzyme constraints and *k*<sub>cat</sub> calibration, ensuring predictions align with experimental data.  
- **Base Model**: [iML1515](http://bigg.ucsd.edu/models/iML1515)
- **Highlights**:
  - Integrates multi-source enzyme data, including in vivo enzyme activities (*k*<sub>max</sub>), BRENDA, and DLKcat, to significantly improve *k*<sub>cat</sub> coverage and quality.  
  - Enables simulation of overflow metabolism.

---

## 🖥️ Installation

### Requirements
- MATLAB R2022b or later  
- RAVEN Toolbox 2.8.3 or later  
- Python 3.10+ (optional, for data preprocessing)  
