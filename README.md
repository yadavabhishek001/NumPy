# NumPy

A collection of Jupyter Notebooks demonstrating the usage of NumPy for numerical computing in Python.

## Project Overview

This repository contains hands-on examples and exercises using the [NumPy](https://numpy.org/) library. The notebooks cover array creation, manipulation, mathematical operations, and integration with pandas for data analysis.

## Setup Instructions

### Prerequisites

- Python 3.x
- [Jupyter Notebook](https://jupyter.org/)
- NumPy

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yadavabhishek001/NumPy.git
   cd NumPy
   ```

2. Install the required dependencies:
   ```bash
   pip install numpy jupyter
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open any of the `.ipynb` files from the Jupyter interface.

## Usage Examples

```python
import numpy as np

# 1D Array
arr1 = np.array([1, 2, 3, 4, 5, 6, 7])
print(arr1, type(arr1), arr1.dtype, arr1.shape)
# Output: [1 2 3 4 5 6 7] <class 'numpy.ndarray'> int64 (7,)

# 2D Array
arr2D = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
print(arr2D, type(arr2D), arr2D.dtype, arr2D.shape)
# Output:
# [[1 2 3]
#  [4 5 6]
#  [7 8 9]] <class 'numpy.ndarray'> int64 (3, 3)
```

## Notebook Files

| Notebook | Description |
|---|---|
| [NumPy.ipynb](https://github.com/yadavabhishek001/NumPy/blob/main/NumPy.ipynb) | Core NumPy concepts and array operations |
| [numpy1.ipynb](https://github.com/yadavabhishek001/NumPy/blob/main/numpy1.ipynb) | Additional NumPy examples and data analysis |
| [numpy_foundation.ipynb](https://github.com/yadavabhishek001/NumPy/blob/main/numpy_foundation.ipynb) | NumPy foundations and fundamentals |
| [practice.ipynb](https://github.com/yadavabhishek001/NumPy/blob/main/practice.ipynb) | Practice exercises and problems |

## Dependencies

| Package | Purpose |
|---|---|
| Python 3.x | Programming language |
| numpy | Numerical computing library |
| jupyter | Interactive notebook environment |
