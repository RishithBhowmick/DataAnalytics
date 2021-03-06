# Startup Success Analysis
## README
Data Analytics Project  
Rishith Bhowmick, Soundarya Ganesh, Surabhi Vedagiri, Kalp Aghada

---
### Description

This repository contains the notebooks and the data used for the project in the course "Data Analytics".

It contains the 5 main notebooks:  Exploratory Data Analysis and 4 more for cleaning the data and the 4 distinct models created. The notebook for Exploratory Data Analysis (EDA.ipynb) contains the graphs and inferences obtained from the EDA performed on the dataset.
* EDA.ipynb
* Data Cleaning_and_Logistic Regression.ipynb
* SVM.ipynb
* Random_Forests.ipynb
* Decision_Tree.ipynb

The models created for the dataset are: 
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Classifier

In each of these notebooks, data has been cleaned and appropriate features and parameters have been landed upon through EDA (and RFE, recursive feature elimination) to obtain optimal results.

---
### Steps to Reproduce Project

To execute the project, run each of these files in the following order with Jupyter.
Cells can either be run one by one, or all be run at once (in order).

* EDA.ipynb
* Data Cleaning_and_Logistic Regression.ipynb
	* Cleans the data (Startup.csv), creates intermediate databases of the same (X_clean, y_clean) for quick access by other models. A copy of X_clean and y_clean are included for backup purposes, but are not required by default when running the project, because they are created by this file anyway.
* SVM.ipynb
* Random_Forests.ipynb
* Decision_Tree.ipynb
