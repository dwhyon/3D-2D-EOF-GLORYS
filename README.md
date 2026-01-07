# 3D-2D-EOF-GLORYS

This repository contains the project code for the study:

**“Realism of 3D Ocean Dynamics Represented by 2D Empirical Orthogonal Functions:  
3D versus 2D Comparison and Interpretation Using Global Ocean Physics Reanalysis Data.”**

The code reproduces the Empirical Orthogonal Function (EOF) analyses and figures used in the paper, based on global ocean physics reanalysis data (GLORYS).

---

## Repository Contents

### Main Figure Generation
- **`3D_2D_EOF_Comparison_V03.ipynb`**  
  Generates **Figures 2–14** in the paper.  
  This notebook compares 2D and 3D EOFs, including spatial patterns, depth structure, and correlations between 2D PCs and 3D PCs.

⚠️ **Note:**  
**Figure 1 is not generated via code.** It was created manually using **Inkscape v1.4.2** and is therefore not reproducible within this repository.

---

### EOF Computation Notebooks
- **`2D_EOFs_GLORYS_cut.ipynb`**  
  Computes **2D EOFs** using depth slices of 3D ocean data.

- **`EOFs_GLORYS_cut_1month.ipynb`**  
  Computes **3D EOFs** using the full 3D ocean.

---

## Data
The notebooks assume access to **GLORYS global ocean reanalysis data**.  
Due to data size and licensing constraints, the raw datasets are **not included** in this repository.

---

## Notes
- Plot styles vary by figure to match the formatting used in the paper
- Figures are generated in the same order as presented in the manuscript

---

## Software
- Python (NumPy, SciPy, Matplotlib, xarray, netCDF4)
- Jupyter Lab / Notebook
- Inkscape v1.4.2 (for Figure 1 only)
