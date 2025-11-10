# Waste Classification using CNN for Sustainability

## Overview
This project uses a Convolutional Neural Network (CNN) to classify waste images into different predefined categories. The aim is to support sustainability by improving waste segregation through automated image classification.

## Dataset
The dataset contains images of 9 waste categories:
- plastic
- paper
- metal
- glass
- organic
- e-waste
- battery
- automobile
- light bulb

Source: Kaggle  
Link: (https://www.kaggle.com/datasets/wasifmahmood01/custom-waste-classification-dataset)

## Model
The CNN model includes:
- Convolution + MaxPooling layers
- Flatten and Dense layers
- Softmax output layer

Loss: sparse categorical crossentropy  
Optimizer: Adam

## Workflow
1. Import Libraries  
2. Load Dataset 
3. Store Class Names  
4. Prepare Dataset for Training  
5. Normalization of Images  
6. Bulid CNN Model
7. Compile Model
8. Train Model
9. Plot Accuracy & Loss
10. Test Model
11. Save the Model

## Results
- Model trained successfully (Train accuracy : 86%) 
- Accuracy/loss plots included  
- Tested with random images

## Saved Model
Model file: Waste_Classifier.h5  
Can be loaded later using load_model().

## Requirements
- tensorflow
- numpy
- matplotlib
- random
- os

## Future Scope
- Add data augmentation  
- Improve accuracy  
- Try transfer learning  
- Deploy using Streamlit/Flask

## Acknowledgements
Kaggle dataset contributors  
TensorFlow documentation
