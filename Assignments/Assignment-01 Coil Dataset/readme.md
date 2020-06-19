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

![Horizontal Flip](assets/horizontal_flip.jpg)

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
