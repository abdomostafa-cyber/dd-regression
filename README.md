# Synthetic Data Generation Notebook for [The height of the double descent peak depends strongly on the data and the model]
This repository contains the Jupyter Notebook used to generate the synthetic datasets and plots presented in the paper:


The height of the double descent peak depends strongly on the data and the model

Abdalrhman Mostafa and Peter Latham

[DOI placeholder]


## Environment Setup
To run the notebook, install the required packages:

```bash
pip install -r requirements.txt
```

You can also open the notebook directly in Google Colab using this badge:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abdomostafa-cyber/dd-regression/blob/main/Synthetic%20Data%20Generation.ipynb)

## How to Use

1. Open the notebook `Synthetic_Data_Generation.ipynb`.
2. Run all cells sequentially.
3. The notebook will:
   - Generate synthetic data under different model conditions (varying P/N ratios, alignment, and power).
   - Compute empirical and theoretical generalization errors.
   - Produce plots matching those shown in the paper.

## Key Parameters
| Parameter | Description | Example Value |
|------------|-------------|----------------|
| `N` | Number of features | 1000 |
| `P` | Number of samples | αN |
| `epsilon` | Regularization strength | 1e-1~1e-15 |
| `n` | Eigenvalue decay power | 0, 1, 2 |
| `aligned` | Whether w\* is aligned or random | True / False |

## Outputs
- **Plots**: Saved in `figures/` (log-scale generalization error curves, replica theory comparison).
- **Data**: Generated datasets are stored in the `data/` directory.

## Citation
If you use this notebook or reproduce results from it, please cite:

```bibtex
@article{mostafa2025synthetic,
  title={The height of the double descent peak depends strongly
on the data and the model},
  author={Mostafa, Abdalrhman and Latham, Peter},
  year={2025},
  journal={Preprint},
}
```

## Contact
**Abdalrhman Mostafa**  
Email: amostafa@arabsinneuro.org  
