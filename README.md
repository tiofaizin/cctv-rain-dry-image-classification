# cctv-rain-dry-image-classification
Author: Aji, Tio, Faridl
<br>
This repository is a private repository aims to accomodate Hooka team script versioning and stroraging. Please push all model-related files into this repository in a tidy manner.  

## Contents:
1. Prediction model script in a python jupyter notebook file format
2. Training and testing input files
3. Trained and saved model in a h5 file format.

### 1. Prediction Model Script (Python)
**Required libraries**: <br>
1. Numpy
2. Pandas
3. Matplotlib
4. Keras
5. Tensorflow
6. OS
7. Random
8. Sklearn

### 2. Training and testing input files
Training and testing input files are available inside `input_*` folder. Inside the folders there are two subfolders (train and test folders) and two CSV files (training.csv and testing.csv). The CSV files consist of image labeling information. Each image has been labeled (`rain/1` and `dry/0`) and neatly listed in the CSVs. <br>
<br>
You are welcome to try train the model with different training dataset and push the input training data into this repository. But keep in mind that you have to do it accordingly and set the input dataset into a new `input_*` folder (e.g. `input_3`).

### 3. Trained and saved model (H5)
After training the model, you can save the model using h5 output format. This model is callable and can be used for future prediction and analysis purposes.
<br>
<br>
*Thank You*
