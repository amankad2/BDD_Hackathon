# BDD Hackathon: Doctor-to-Hospital Assignment

This project compares two approaches for assigning doctors to hospitals based on ranked preferences and hospital capacity constraints:

- Greedy baseline
- Linear Sum Assignment using `scipy.optimize.linear_sum_assignment`

The notebook tests both approaches on the same input data and compares them using total preference rank, average assigned rank, and percentage of doctors receiving their first choice.

See `BDD_Hackathon_FinalCode.ipynb` for the full implementation, testing framework, and results.
