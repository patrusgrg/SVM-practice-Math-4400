# SVM-practice-Math-4400

Exercises and homework workspace for Math 4400 — Support Vector Machines (SVM) practice.

This repository contains a Jupyter notebook used to explore, implement, and visualize Support Vector Machines for the Math 4400 course. The notebook covers linear and kernel SVMs, margin/soft-margin concepts, hyperparameter tuning, and visualization of decision boundaries.

## Repository contents

- `SVM_HW.ipynb` — Primary Jupyter notebook with explanations, code examples (scikit-learn), visualizations, and exercises.
- `README.md` — This file.

## Goals

- Provide a concise, hands-on exploration of SVM theory and practice.
- Implement classification examples using scikit-learn and visualize margins and decision boundaries.
- Offer exercises and worked examples suitable for Math 4400 homework or self-study.

## Prerequisites

- Python 3.8+ (works with 3.8–3.11)
- Jupyter (Notebook or JupyterLab)
- Recommended Python packages:
	- numpy
	- scipy
	- scikit-learn
	- matplotlib
	- seaborn
	- pandas

You can install these using pip (example below).

## Quick setup (PowerShell)

Create and activate a virtual environment, then install the required packages:

```powershell
# create venv
python -m venv .venv
# activate venv
.\.venv\Scripts\Activate.ps1
# upgrade pip
python -m pip install --upgrade pip
# install common data science packages
pip install numpy scipy scikit-learn matplotlib seaborn pandas jupyter
```

If you prefer, install the packages into your global environment or use conda.

## How to run

1. Open a terminal (PowerShell) and activate your environment as shown above.
2. Start Jupyter Notebook or JupyterLab in the repository root:

```powershell
jupyter notebook
# or
jupyter lab
```

3. Open `SVM_HW.ipynb` in the browser and run the cells.

Alternative: convert the notebook to a script or HTML with nbconvert if you want a static export:

```powershell
jupyter nbconvert --to html SVM_HW.ipynb
jupyter nbconvert --to script SVM_HW.ipynb
```

## Notebook overview

Typical sections inside `SVM_HW.ipynb` (may vary):

- Introduction and theoretical background
- Dataset generation or loading (synthetic examples / scikit-learn datasets)
- Linear SVM: formulation, fitting, margins, support vectors
- Soft-margin SVM and the role of C
- Kernel SVMs (RBF, polynomial) and kernel intuition
- Model selection and cross-validation
- Visualizations of decision boundaries and margins
- Exercises and suggested solutions

## Notes and assumptions

- The notebook currently uses scikit-learn's SVM implementations for concise, reproducible experiments. If you plan to implement SVMs from scratch or use a specialized QP solver (e.g., CVXOPT), update the notebook accordingly.
- No external datasets are required for the included examples — most examples use synthetic or scikit-learn toy datasets. If you add data files, update this README with dataset descriptions and licensing.

## References

- Cortes, C., & Vapnik, V. (1995). Support-vector networks. Machine Learning.
- scikit-learn SVM documentation: https://scikit-learn.org/stable/modules/svm.html

## License

This repository is provided under the MIT License. See LICENSE for details (if you add a LICENSE file).

## Contact

For questions about the notebook or suggestions, open an issue or contact the repository owner.

---

Happy exploring SVMs! 🚀

