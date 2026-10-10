# Contagious Disease Modeling

Epidemic models built in Python (NumPy, SciPy, Matplotlib) for a CU Boulder disease-modeling course.

## Contents

| Folder | What it covers |
| --- | --- |
| `HW1`–`HW4` | SIR-family models with births and deaths, numerical ODE solutions, parameter sweeps and fitting to weekly case data (`HW4/*.csv`) |
| `Project/Project_Code.ipynb` | Final project: an age-structured SEIRD model (children, adults, elderly) with a contact matrix, vaccination start time and rate, vaccine and antiviral efficacy, and social distancing, compared across intervention scenarios |

Each notebook saves its plots next to it (`*_Graph*.png`).

## Running

```bash
pip install numpy scipy matplotlib jupyter
jupyter notebook Project/Project_Code.ipynb
```
