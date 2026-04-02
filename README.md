# NumPy Notebooks

A small collection of **Jupyter Notebooks** for learning and practicing **NumPy** (array creation, shapes/dtypes, and foundational operations).

## Project overview
This repository contains beginner-friendly notebooks that demonstrate core NumPy concepts in an interactive, step-by-step format.

## Prerequisites
- Python 3.x
- NumPy
- Jupyter Notebook / JupyterLab (or VS Code with the Jupyter extension)

## Setup / Installation

### Option 1: Using pip
```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install -U pip
pip install numpy notebook
```

### Option 2: Using Anaconda (recommended for notebooks)
Install Anaconda/Miniconda and then run:
```bash
conda create -n numpy-notebooks python=3.11 numpy notebook -y
conda activate numpy-notebooks
```

## Run the notebooks
From the repository root:
```bash
jupyter notebook
```
Then open any of the notebooks listed below.

## Usage examples
```python
import numpy as np

arr1 = np.array([1, 2, 3, 4, 5, 6, 7])
print(arr1, type(arr1), arr1.dtype, arr1.shape)

arr2D = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
print(arr2D, type(arr2D), arr2D.dtype, arr2D.shape)
```

## Notebook files
- **NumPy.ipynb**
- **numpy1.ipynb**
- **numpy_foundation.ipynb**
- **practice.ipynb**

## Notes
- If you get a kernel/import error, make sure you started Jupyter from the same environment where you installed `numpy`.

## License
No license file is currently included in this repository. If you plan to share or reuse this work, consider adding a license (e.g., MIT).