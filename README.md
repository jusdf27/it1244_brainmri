# IT1244 project ReadMe
___
## Description
In recent years there has been interest in develping Convolutional Neural Network (CNN) machine learning models that can assist in classifying MRI scans of brain tumors into benign or malignant. Our project aims to build on previous works by experimenting with the application of GradCAM to visualise the decision making done by CNNs as well as exploring different ways to augment our training data to allow the trained model to be more robust and flexible.

## Workflow
___
The workflow is as follows:

- Data preperation which consists of two steps:
  - Preprocessing
  - Augmentation
- Training and analysing the baseline CNN model which consists of:
  - (Training) Creation of model and fine-tuning for optimal hyperparameters
  - (Analysis) Plotting of performance graphs with various metrics used
  - (Analysis) Using GradCAM to visualise model
- Training and analysing the VGG16-ANN model which consists of:
  - (Training) Creation of multiple models with varied number of VGG16's layers frozen
  - (Analysis) Plotting of performance graphs with various metrics used
  - (Analysis) Using GradCAM to visualise model
- Training and analysing the CNN-XGBoost model which consists of:
  - (Training) Creation of model and incorporation of Principal Component Analysis (PCA) into model as well as tune hyperparameters
  - (Analysis) Plotting of performance graphs with various metrics used
  - #Note: GradCAM was not able to be used for CNN-XGBoost

## Getting Started
_____

### Dependencies
- keras version 2.15.0
- The file should be used in google colab

### Installation of necessary packages
The first code block contains all the import statements
```
'''
!pip install numpy==1.24.3
##remaining import statements...
!pip install tensorflow==2.12.1
'''
```
Remove the triple backticks (') to run the code which installs all the necessary packages. If all packages are already installed you can reapply the triply backticks (as shown above) to prevent packages from being installed again

### Executing Program

The code code blocks should be run in order. Each code block is titled according to what it does. An alternative is to click the tab "runtime" -> "runall" to run all the blocks of code in order. There is also a table of contents that can be accessed by clicking the table of contents icon at the top left of the page

## Authors
___
- Justin Tan Min Shi 
- Han Yong Yi Jace 
- Sng Zhi Wen Collin
- Ryan Justyn

## Version History
___
- v1.0.0: Final submission

