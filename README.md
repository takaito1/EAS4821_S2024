# EAS4821_S2024
Quantitative Techniques for EAS Laboratory Class (Spring 2024)

## Setting up the python environment (Option 1. installing miniconda3) 
  - These steps will install miniconda3 on your laptop, it takes about 3GB of disk space 
  - Install miniconda3 on your laptop. Start by opening this [URL](https://docs.conda.io/projects/miniconda/en/latest/){:target="_blank"} 
  - Scroll down to "Quick Command Line Install"
  - Select your OS (Windows/macOS/Linux) and follow the appropriate instructions.
  - Once the installation is complete, follow the instructions below exactly. 
```
source ~/miniconda3/etc/profile.d/conda.sh
conda activate
```
  - Then create a new environment called EAS4821.  
```
conda create --name EAS4821
```
  - Then activate EAS4821.
```
conda activate EAS4821
```
  - Then install mamba in EAS4821.
```
conda install -c conda-forge mamba
```
  - Install packages manually
```
mamba install -c conda-forge numpy matplotlib pandas netcdf4 dask nc-time-axis cartopy seaborn gsw xarray scikit-learn scipy joblib ipykernel jupyterlab
```
  - Once it is complete, make this environment available to the Jupyter server:
```
python -m ipykernel install --user --name EAS4821 --display-name EAS4821
```
  - At this point the "EAS4821" environment should be ready to use in Jupyterlab/Jupyter Notebook. 

## Setting up the python environment (Option 2. google colab) 
  - To access google colab, open a new tab on your browser and enter "colab.google" in the search box. 
  - Alternatively, open this [URL](https://colab.google/){:target="_blank"} 
