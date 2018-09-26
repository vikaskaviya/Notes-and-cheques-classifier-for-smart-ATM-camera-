# Notes-and-cheques-classifier-for-smart-ATM-camera-
•	Task was to build a model which can classify different Notes (dollars) and cheques from various banks for a smart ATM camera.

## Dataset
•	Set of 87 images (322 X 137 pixels, each pixel has 3 colours) of cheques and dollars were given. 

## Steps
- split data for training and testing 
- Reduce the Dimensionality from 136452 to 60
- applied Principle Component Analysis and Image processing f
- applied KNN classifier and cross- validdation using GridsearchCV
•	Got best test data accuracy as 0.89% and 0.97% accuracy on training data while choosing no. of neighbours as 3.

## Conclusion
- test data accuracy = 0.89
- train data accuracy = 0.97
- no of neighbours in KNN classifier = 3 

## Technology used
ML models - PCA, K nearest neighbours, GridsearchCV, python models:  Scikit-learn, numpy, pandas, matplotlib, seaborn and PIL 
