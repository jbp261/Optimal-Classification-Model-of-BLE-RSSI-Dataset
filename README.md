# OPTIMAL CLASSIFICATION MODEL OF BLE RSSI DATASET FOR INDOOR LOCALIZATION AND NAVIGATION

### Project Overview
The aim of the project is to develop optimal classifiers to predict the position of the user based on the RSSI readings from thirteen iBeacon devices. The BLE RSSI labeled dataset was used to train different classifiers and evaluate their performance.

### Motivation

The motivation for the project is to develop big data analysis tool for smart cities and help people guide indoors using machine learning approach.

### Bild Status

![Scrutinizer](https://img.shields.io/scrutinizer/g/filp/whoops.svg)

![CocoaPods](https://img.shields.io/cocoapods/dw/AFNetworking.svg)

### Tech/Framework used
The project was done using python GUI [Anaconda](https://anaconda.org/anaconda/python "Anaconda").

### Features
- Logistic Regression
- Decision Tree
- Random Forest
- K-fold CV
- GridSearchCV
- Pipeline
- PCA
- SelectKbest
- Voting

### Dataset
- Labeled dataset
-Number of variables: 15
-Number of data points: 1420
- Unlabeled dataset
-Number of variables: 15
-Number of data points: 5191

### Code Example
```python
#The following code predicts the best outcome of the input
Prediction = voting_clf.predict(Input)
```
### References
The following book and python machine learning library manuals were followed to complete the projcet.
The code was not directly copied from the following referances without proper inline citation.
- [Hands-On Machine Learning with Scikit-Learn and TensorFlow](https://benjaminliuweb.files.wordpress.com/2016/12/oreilly-hands-on-machine-learning-with-scikit-learn-and-tensorflow-1491962291.pdf  "Hands-On Machine Learning with Scikit-Learn and TensorFlow")
- [scikit-learn](http://scikit-learn.org/stable/ "scikit-learn")
- [Pandas](https://pandas.pydata.org/ "Pandas")
- [Numpy](www.numpy.org/ "Numpy")
- [pyplot](https://matplotlib.org/api/pyplot_api.html "pyplot")
- [Enabling Cognitive Smart Cities Using Big Data and Machine Learning: Approaches and Challenges](https://ieeexplore.ieee.org/document/8291121/ "Enabling Cognitive Smart Cities Using Big Data and Machine Learning: Approaches and Challenges")
- [BLE RSSI Dataset for Indoor localization and Navigation Data Set ](https://archive.ics.uci.edu/ml/datasets/BLE+RSSI+Dataset+for+Indoor+localization+and+Navigation "BLE RSSI Dataset for Indoor localization and Navigation Data Set ")

### License
[MIT @ JBP261](https://choosealicense.com/licenses/mit/ "MIT @ JBP261")
