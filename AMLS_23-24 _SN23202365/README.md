*a brief description of the organization of your project
The project is organized according to the following structure, where main.ipynb is the main program that completes the 
training and testing of the model. The A and B folders contain the necessary functional files for the model 
implementation, and the Datasets file is used to store the dataset.
AMLS_23-24_SN12345678
§ A
§ B
§ Datasets
   § PneumoniaMNIST
   § PathMNIST
§ main.py
§ README.md

*the role of each file;

**For task A
***dataset:To define a class MedMNIST that inherits from the torch. utils. data dataset and initializes it. The file's 
functions include loading data, splitting it into training/validation/testing sets, and presenting dataset content.
***evaluator:Used to calculate the ACC and AUC metrics of the model.
***info:Store information for each dataset.
***LeNet5:Used to build models
***pytorchtools: To define EarlyStopping class to prevent model overfitting
***utils:To define reusable functions for dataset presentation, image preservation, etc

**For task B
***dataset:To define a class MedMNIST that inherits from the torch. utils. data dataset and initializes it. The file's 
functions include loading data, splitting it into training/validation/testing sets, and presenting dataset content.
***evaluator:Used to calculate the ACC and AUC metrics of the model.
***info:Store information for each dataset.
***LeNet5:Used to build models
***LeNet5_optim:Refined model based on the original network architecture
***pytorchtools: To define EarlyStopping class to prevent model overfitting
***utils:To define reusable functions for dataset presentation, image preservation, etc

*the packages required to run your code.
os
PIL
tqdm
torch
numpy
sklearn
pandas
skimage
random
collections
warnings
torchvision
matplotlib.pyplot






