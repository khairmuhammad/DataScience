# Coil Unprocessed Dataset

## Directory Structure

    ├── coil-20-unproc         (Unprocessed Data)
    ├── coil20-proc            (Processed Data)
    | ├── train
    |   |   ├──Object1
    |   |   ├──Object2
    |   |   ├──Object3
    |   |   ├──Object4
    |   |   ├──Object5
    | ├── test
    | ├── valid
    ├── src          
    ├── test         
    ├── tools        
    ├── LICENSE
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
