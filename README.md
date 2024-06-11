In this respository, codes form analyzing single-nucleus RNA sequencing data of cardiac cells are provided. These codes implement six featrue ranking algorithms: Categorical Boosting (CatBoost), last absolute shrinkage and selection operator (LASSO), light gradient boosting machine (LightGBM), Monte Carlo feature selection (MCFS), random forest (RF) and eXtreme Gradient Boosting (XGBoost), and two classification algiorithms: decision tree and random forest.

Python environment installation

Step 1 Download the software by git clone https://github.com/*******/*******

Step 2 Installation has been tested in Linux and Windows with Python 3 (Recommend to use Python 3.10 or miniconda 3 platform). Since the package is written in Python 3, Python 3 with the pip tool must be installed first. The tools use the following dependencies: numpy, scipy, pandas, scikit-learn You can install these packages first, by the following commands: pip install pandas pip install numpy pip install scipy pip install scikit-learn

Step 3 cd to the software folder and run the installation command: python *************

Guide for codes
Step 1: The RNA sequencing data of cardiac cells was fed into the codes of one of the feature ranking algorithm, which can produce a feature list.
Step 2: With the feature list in Step 1, using codes in folder csv_make to generate csv files, which contain samples represented by some top features in the list.
Step 3: For each generated csv file, using the codes of one classification algorithm to obtain the cross-validation results.

Other notes
1. In each folder, the file "comd" contains the codes to run the corresponding package.
2. The input file of MCFS should be in adx format, whereas those for other algorithms are in csv format.


