# Debug-Challenge
Fixed bugs in logistic regression notebook

# Debug Challenge – Logistic Regression 

This repository contains a fixed version of a logistic regression notebook provided as part of a debugging challenge.

# What Was Done

The original notebook had multiple issues affecting training stability and evaluation.  
I debugged and fixed the following:

- Converted `y_test` from boolean to integer labels
- Reduced learning rate for stable gradient descent
- Added epsilon to the cost function to avoid log(0) numerical errors

#  Files

- `Debug_Challenge_Version_A_fixed.ipynb` – Corrected Jupyter notebook
- `README.md` – Project documentation

# Result

After fixes:
- Notebook runs without runtime errors
- Loss becomes stable
- Model trains correctly on synthetic data

#Tech Stack

- Python  
- NumPy  
- Jupyter Notebook  

#  Author

Nupur
