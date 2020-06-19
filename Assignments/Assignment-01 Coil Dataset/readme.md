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
## Training and Validation (Accuracy/Loss Graph)
![Accuracy](DataScience/Assignments/Assignment-01 Coil Dataset/tv.JPG)

## 
* Import Libraries
* Rotation
* Width and Height Shifts
* Brightness
* Shear Transformation
* Zoom
* Channel Shifts
* Flips
* Normalization
  * Featurewise
  * Samplewise
* Rescale and Preprocessing Function
* Using in Model Training
