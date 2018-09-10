# Notes-and-cheques-classifier-for-smart-ATM-camera-
•	Task was to build a model which can classify different Notes (dollars) and cheques from various banks for a smart ATM camera.
•	Set of 87 images (322 X 137 pixels, each pixel has 3 colours) of cheques and dollars were given. First I reduced the dimensionality from 136452 to 60 using principal component analysis and applied Knn classifier to distinguish dollar and cheques. Then applied GridSearchCV algorithm to check Knn classifier by taking 1 to 40 neighbours. 
•	Got best test data accuracy as 0.89% and 0.97% accuracy on training data while choosing no. of neighbours as 3.
•	Technology used:ML modles - PCA, K nearest neighbours, GridsearchCV, python models:  Scikit-learn, numpy, pandas, matplotlib, seaborn and PIL 
