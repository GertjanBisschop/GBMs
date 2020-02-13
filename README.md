# GBMs 

This repository contains the SLiM (<https://messerlab.org/slim>) scripts for Bisschop et al. (2020).

- trait-based model
- sweep-based model

# How to run the script

Install SLiM:

```bash
>>> conda install -c conda-forge slim
```

Example


```bash
>>> slim -d "iter=0" -d "folder=0" -d "mean_lbm=0.05" -d "fraction_gbm=1.0" -d "fraction_lbm=1.0" -d "selection_sigma=0.025" -d "mutation_rate=5e-08" -d "recomb=5.0e-06" -d "num_generations=200000" DB_sfixed.txt
```
