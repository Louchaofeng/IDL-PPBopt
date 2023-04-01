# IDL-PPBopt
Code for "IDL-PPBopt: A Strategy for Prediction and Optimization of Human Plasma Protein Binding of Compounds via an Interpretable Deep Learning Method"

## Requirements
That version of the model uses cuda.
- python 3.7
- pytorch 1.5.0
- openbabel 2.4.1
- rdkit
- scikit learn
- scipy 
- cairosvg

## Installation
Using conda:

1- Clone that repo. <br>
2- Run the follwing command on the terminal inside the repo folder: `conda env create -f environment.yml`<br>

To activate the conda environment run that command: `conda activate IDL_PPBopt_cuda`<br>

## Model
The iPPB model was trained with AttentiveFP algorithm and saved in the "saved_models" file.

## PPB prediction and second-level chemical rules' derivation for PPB optimization
1. Write the given molecules to *input_compounds.csv* file.
2. Run *IDL-PPBopt.ipynb* in jupyter notebook.
