# Logistic-regression-Medical-Imaging
## Dataset
Wisconsin Diagnostic Breast Cancer(WDBC) dataset consists of 569 pre-computed digitized images of fine needle aspirate (FNA) of breast mass containing features like radius, texture, perimeter, symmetry, fractal dimension etc. The dataset consists of an ID for each sample, diagnosis in the form of ‘Malignant’ or ‘Benign’ and 30 real valued input features as mentioned earlier.
## Training
The WDBC dataset has been partitioned into 80% training, 10 % cross-validation and 10% testing datasets. In order to scale all the feature values into a smaller range, normalization has been performed on the datasets.  The model parameters: weights of features and bias are initialized. The hyper parameters: learning rate and epochs are set to a value initially
## Result
### Confusion Matrix
<img src=https://github.com/NandithaNandanavanam/Logistic-regression-on-WDBC-dataset/blob/master/ConfusionMatrix.PNG>
Accuracy = 89.47%
Precision = 90.9%
Recall = 86.95%
