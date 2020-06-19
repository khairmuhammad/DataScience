# Coil Unprocessed Dataset

## Directory Structure

    ├── coil-20-unproc         (Unprocessed Data)
    ├── coil20-proc            (Processed Data)
    | ├── train                (Data for training the model)
    |       ├──Object1
    |       ├──Object2
    |       ├──Object3
    |       ├──Object4
    |       ├──Object5
    | ├── test                 (Data for testing the model)  
    |       ├──Object1
    |       ├──Object2
    |       ├──Object3
    |       ├──Object4
    |       ├──Object5
    | ├── valid                 (Data for validating the model)
    |       ├──Object1
    |       ├──Object2
    |       ├──Object3
    |       ├──Object4
    |       ├──Object5
    ├── objects.h5              (Trained model)                   
    └── README.md
    

## Dependencies
* keras ```pip install keras```
* numpy
* shutil
* tensorflow ```pip install tensorflow```
* matplotlib.pyplot
* os
## Training and Validation (Accuracy/Loss Graph)
![Accuracy](https://github.com/khairmuhammad/DataScience/edit/master/Assignments/Assignment-01/tv.JPG)
