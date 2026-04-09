# README

## Overview
This repository contains the **code and data** used for the modeling analysis presented in the paper:  
**“Mapping the sequence and structural logic of DNA glycosylase recognition of cytosine deamination lesions”**. 

Specifically, it supports the **"Specificity defined by base identity and dependencies"** sections, where we model how individual bases and their interactions in flanking regions influence TDG and UDG enzyme binding.

---

## Repository Contents
- **`TDG.ipynb`**  
  Jupyter notebook implementing additive and interaction-based modeling of **TDG** binding.

- **`UDG.ipynb`**  
  Jupyter notebook implementing additive and interaction-based modeling of **UDG** binding.

- **`MBD4.ipynb`**  
  Jupyter notebook implementing additive and interaction-based modeling of **MBD4** binding.

- **`data/`**  
Folder containing the **processed binding data** (see Methods section of the manuscript) used to train, test, and validate the models.

---

## Usage
1. **Clone or download** the repository.
2. **Install dependencies** (Python ≥ 3.8 recommended).  
   Required packages include:  
   `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `logomaker`, `scipy`, `statsmodels`
3. **Open and run each notebook** independently.  
   The notebooks are self-contained and will display figures directly.


---

## Citation
If you use these notebooks or data in your own work, please cite: 
> Levy, N. *et al.* “Mapping the sequence and structural logic of DNA glycosylase recognition of cytosine deamination lesions” (2026).

---

## Contact
For questions, collaborations, or feedback, please contact:    
**Noga Levy**  
PhD Student, Afek Lab  
Weizmann Institute of Science  
📧 noga.levy@weizmann.ac.il
