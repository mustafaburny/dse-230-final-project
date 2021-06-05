# DSE 230 Final Project

Team Members: Sam Courtney (sccourtney@ucsd.edu), Mustafa Burny (mburny@ucsd.edu)
Project Dataset: Smartphone and Smartwatch Activity and Biometrics
Link to Project Proposal: https://docs.google.com/presentation/d/1Ssv67aYICAJ_fGoxBA8MmmYWHv_g0Fb7W1V1j3Kq-PY/edit?usp=sharing
Link to Final Presentation: https://docs.google.com/presentation/d/1i99rEFhZ-TQxNGzopirf3CSudB8l-luJPCSpBfp2KLU/edit?usp=sharing

## Code Overview
The code base for this project is divided into two notebooks. Each notebook contains the full processing pipeline for two approaches to this task that were attempted. Run each notebook in any order to run the pipelines and view the results.

1. `Pre-Calculated Features Pipeline.ipynb` (uses **Dask**)
2. `Custom Features Pipeline.ipynb` (used **PySpark**)

## Python Environment Details
The following packages are required to run these notebooks:

```
dask-ml==1.9.0
dask==2021.5.1
jupyterlab==3.0.16
matplotlib>=3.1.2
numpy>=1.19.5
pandas==1.2.4
pyarrow==4.0.1
pyspark==3.1.1
python-dateutil==2.8.1
scikit-learn>=0.24.1
scipy>=1.6.2
seaborn==0.11.1
tqdm==4.61.0
tsfresh==0.18.0
```

Each notebook also contains a list of the packages required specifically for that notebook.