# Caltech101 Unprocessed Dataset
This dataset contains 101 classes of different animals. It is unprocessed.

## Directory Structure

    ├── caltech-original-prepared         (Processed Data)
    |       ├── augmented-dir
    |             ├── airplanes
    |             ├── bonsai
    |             ├── car side
    |             ├── chandelier
    |             .
    |             .
    |             .
    |             ├── watch
    |       ├── merged-data
    |             ├── airplanes
    |             ├── bonsai
    |             ├── car side
    |             ├── chandelier
    |             .
    |             .
    |             .
    |             ├── watch
    |             ├── yin yang
    |       ├── new-train-test        (Processed data for train, test and validate)
    |             ├── train
    |             ├── test
    |             ├── validate
    |       ├── test        (Unprocessed data for train and test)
    |       ├── train
    ├── caltech-model.h5              (Trained model)                   
    └── README.md
    

## Dependencies
* keras ```pip install keras```
* tensorflow ```pip install tensorflow```
* numpy
* shutil
* matplotlib.pyplot
* os

## Raw Data Graph
![Accuracy](https://github.com/khairmuhammad/DataScience/blob/master/Assignments/Assignment-02%20Caltech%20Dataset/tv1.JPG)

## After Augmentation Data Graph
![Accuracy](https://github.com/khairmuhammad/DataScience/blob/master/Assignments/Assignment-02%20Caltech%20Dataset/tv1.JPG)

## Training and Validation (Accuracy/Loss Graph)
![Accuracy](https://github.com/khairmuhammad/DataScience/blob/master/Assignments/Assignment-02%20Caltech%20Dataset/tv1.JPG)
