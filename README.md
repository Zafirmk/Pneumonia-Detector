# Detecting Pneumonia in Chest X-Rays using CNN.

**Project duration**: 3 to 5 days  
**IDE**: Jupyter Notebooks/Kaggle Kernel  
**Python Version**: Python 3.8


## Description
A Convolutional Neural Network is used to classify X-ray images of chest as NORMAL or PNEUMONIA.
Managed to achieve 92% Percent Test Accuracy with v2 of the model in the ipynb
Further Description available at the top of the Python Notebook.

## How it works
1. Data is first standardized and split into it's features (X) and labels (Y)

2. Data Augmentation is performed to maxmize capabilites of the Neural Network  

3. A Convolutional Neural Network is trained

4. Test Data is then used to evaluate the models

**Visual Example Below**  
Schematic of the CNN Architechture used in the project

![NetworkImg](https://github.com/Zafirmk/Pneumonia-Detector/blob/master/NetworkImg.png)


## Getting Started

1. Clone this repo using the following command  
```
$ git clone https://github.com/Zafirmk/Pneumonia-Detector.git
$ cd Pneumonia-Detector
```
2. Download the [dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

3. Set the directory in the project to your directory
```
movies_df = pd.read_csv("<YOUR movies.csv PATH HERE>")
ratings_df = pd.read_csv("<YOUR ratings.csv PATH HERE>")
```

### Prerequisites
Things you need to install before running:
*  [Python](https://www.python.org/)
*  [Pandas](https://pandas.pydata.org/)
*  [Scipy](https://www.scipy.org/)
*  [Sklearn](https://scikit-learn.org/stable/)
*  [Keras](https://keras.io/)

#### Additional Notes
*  Datasets obtained from [Kaggle](https://www.kaggle.com/)
