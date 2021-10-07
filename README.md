

Model:
XGBoost

Goal:
Prediction of future Sales volume for Rossman stores

Instructions:
Python3.9 & Jupyter Notebook/Lab is required, so please install if missing

conda create --name py35 python=3.9

conda install -c conda-forge jupyterlab

Run in command line:
pip3 install -r requirements.txt

conda install scikit-learn

Open test_prediction.ipynb in Jupyter Notebook/Lab
Set PATH_TEST to the location of test csv file.

PATH_TEST = "data/holdout.csv"
Run the next cell

rossman = Rossman()
rossman.testing(PATH_TEST)
