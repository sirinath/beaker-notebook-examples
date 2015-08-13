# Machine learning example (image recognition).

### This example uses python sklearn library for prediction of simple images with digit.

### Prediction based on the testing samples of handwritted digits and makes a prediction of the tested images (by using different classifiers)


****Important notes:****

* all images must be the same size and must be in .jpg format
* neighborsNumber variable - Number of neighbors for KNN (k-nearest neighbors) classification
* polynomialDegree variable - Polynomial degree for Polynomial kernel prediction
* samplesDir variable - path to the training samples (sample must be named as **uid**\_digit\_**lettername**.jpg)
* testingImagesDir variable - path to the testing samples (filenames should be **lettername**.jpg)

 ###### where **lettername** is an alphabet symbol or digit contained in a given file, **uid** - unique identifier