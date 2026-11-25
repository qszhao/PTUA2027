# Intro to machine learning and deep learning using Python - PTUA 2027

This is repository containing materials for Programming Tools for Urban Analytics Class

The lab is going to be run in jupyter notebook

## Lab requirements

Please create new environmet for this lab using  **Python 3.15**
 
Using [Anaconda](https://docs.anaconda.com/anaconda/install/)  please install the following 

Note: if you use MacOS, you can install the packages via terminal directly. if you use Windows, you can open Anaconda Prompt and install the packages from there. 

```bash

#Check current conda channel priority

conda config --get channels

#Switch your default conda channel to conda-forge and set it as the highest priority

conda config --add channels conda-forge 

#Create new environment

conda create --name machinelearning python=3.15

#Check existing conda environment

conda info --envs

#Make sure that you are going to work in newly created environment

conda activate machinelearning

# Install jupyter lab

conda install -c conda-forge jupyterlab

# Install packages

conda install -c conda-forge pytorch 
conda install -c conda-forge matplotlib
conda install -c conda-forge seaborn
conda install -c conda-forge sklearn 
conda install -c conda-forge torchvision
conda install -c conda-forge torchaudio
conda install -c conda-forge transformers
conda install -c conda-forge lightgbm
conda install -c conda-forge xgboost

#Alternatively run the installation in one line

conda install -c conda-forge pytorch matplotlib seaborn sklearn torchaudio torchvision pytorch transformers lightgbm xgboost

#Start the  jupyter lab

jupyter lab

```

More information about creating python virtual environment with conda can be found from [here][blog].
More details about managing conda channel can be found from [1][1] and [2][2]. Difference between Anaconda Prompt and Anaconda Powershell Prompt can be found from [3][3].

[blog]: https://heartbeat.fritz.ai/creating-python-virtual-environments-with-conda-why-and-how-180ebd02d1db
[1]: https://stackoverflow.com/questions/54150169/how-update-remove-conda-forge-channel-from-anaconda/54150817
[2]: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-channels.html
[3]: https://stackoverflow.com/questions/56656493/what-is-the-difference-between-anaconda-prompt-and-anaconda-powershell-prompt
[installation]: https://github.com/conda-forge/miniforge?tab=readme-ov-file
[explanation]: https://github.com/conda-forge/contextily-feedstock
