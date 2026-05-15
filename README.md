# README

## Overview
This repository contains the **code and data** used for the modeling analysis presented in the paper:  
**“Mapping DNA glycosylase binding across lesion sequence contexts reveals extended sequence and structural recognition logic”**. 

Specifically, it supports the **"Comprehensive mapping of flank preferences reveals that damage recognition extends beyond adjacent positions"** and **"Context-dependent damage recognition includes non-additive and structural components"** sections, where we model how individual bases and their interactions in flanking regions influence MBD4, TDG and UDG enzyme binding.

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

## Contact
For questions, collaborations, or feedback, please contact:    
**Noga Levy**  
PhD Student, Afek Lab  
Weizmann Institute of Science  
📧 noga.levy@weizmann.ac.il
