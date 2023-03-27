This notebook contains the implementation of assignment: https://gatech.app.box.com/file/1138393640165?s=1cvyjwzyt5ze0i6809xrv71t3nxc2f20 

Create a python environment with the following packages to run the notebook. 
The following instructions uses conda to manage environments but one can use 
any preferred method to install the necessary packages. 

1. Install conda from https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation 
2. Run the following command to create an environment `conda create -n assignment1 python=3.10`
3. Once the environment has been created run `conda deactivate` and then `conda activate assignment1` to activate environment
4. Scikit-learn package is needed to run the notebook. Run `conda install -c intel scikit-learn` to install it 
5. Run `conda install matplotlib` and `conda install seaborn`. These packages are used to produce plots
6. Run `conda install jupyterlab` 
7. Run `conda install pandas`
8. Run `conda install ipykernel'
9. Run `python -m ipykernel install --user --name assignment1 --display-name "assignment1"`
10. Download the heart disease dataset from here: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset 
11. Download the breast cancer dataset from here: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data 
12. Save the assignment notebook using the link above in the same directory as the datasets.
13. Run `jupyter lab` in the directory of the notebook. 
14. Run the notebook using the 'assignment1' kernel. 