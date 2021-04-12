# Two-Stage Stochastic Programming
This repository provides a framework to perform two-stage stochastic programming on a district energy system considering uncertainties in energy demands, solar irradiance, wind speed, and electricity emission factors.

To run the two-stage stochastic optimization, you should directly complile the main_twostage_SP.py file. The input data should be entered using the EditableFile.csv. The EditableFile.csv file has four columns: the names of each row, the value of each row that will be used in the framework, the instruction of each row that helps to undesrtand why the user needs to fill this value, and in what stage of the framework this row is used.

## Installing the needed packages
To install the required packages to run the framework are stored in the requirements.txt file in the repository:
```
pip install -r  requirements.txt
```
and install scikit-learn-extra uisng the conda environment:
```
conda install -c conda-forge scikit-learn-extra
```