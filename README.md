# lof-gof-predictor
Loss-of-function &amp; Gain-of-function classifier built on top of GLOF benchmark, also released in this repository.

This repository related to the work: _still not published_


## Environment

1. Have conda installed: https://conda.io/projects/conda/en/latest/user-guide/install/index.html

2. Create a python virtual environment `conda env create -f environment.yml`

## Download data

1. Create the `data/` folder: `mkdir data`
2. Download the training set `wget -O data/training_set_20230316.tsv.gz https://github.com/victormaricato/lof-gof-predictor/releases/download/2024-04/training_set_20230316.tsv.gz`
3. (Optional) Download the LightGBM model `wget -O data/lgb_esm1.pkl https://github.com/victormaricato/lof-gof-predictor/releases/download/2024-04/lgb_esm1.pkl`

## Reproducing the experiment

All experiments are listed under `ESM1v`, you might need to generate the embeddings using `Get ESM Embeddings.ipynb` and then proceeding to the `ESM1v/Training with ESM 1v.ipynb`. The plots reported in the study are under `ESM1v/EDA - ESM1v.ipynb`

## Citation

This will be filled after publication.