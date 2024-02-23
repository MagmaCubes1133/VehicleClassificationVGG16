# VehicleClassificationVGG16
Our project implements a Convolutional Neural Network, which is currently state-of-the-art in image recognition technologies. It tries to perform Vehicle classification over the Stanford Cars Dataset (Also known as cars196) with 16,165 images of 196 cars. The project aims to train a model to classify vehicles in the following format- Make, Model, and Year. For example: the 2012 Tesla Model S or 2012 BMW M3
coupe.

Our project presents two approaches to vehicle classification using VGG-16; first, we use the weights of the pre-trained VGG-16 network submitted by the University of Oxford. Using transfer learning, our first implementation freezes the weights of VGG-16 layers with the original pre-trained weights (From the ILSVRC Submission). It connects it to a trainable, fully connected layer for classification. The fully connected layer is then trained on our dataset for classification. In our second approach, we build a VGG-16 Neural Network from scratch and train the entire network, from the convolutional layers to the fully connected layers on our specific dataset for the same classification. We then compare the accuracy and try to justify the results from the two approaches in our project

The dataset is downloadable from:
(https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset)
## Setup Instructions
The repository has the Jupyter Notebook `VGG16_VehicleClassification.ipynb`. This project runs flawlessly on Google Colab with the following instructions and similar instructions may be used to run it elsewhere
### Instructions
  1. Open `IDS_Project.ipynb`.
  2. Replace the value assigned to the variable `DATASET` with the file path of `Dataset/archive` of the downloaded dataset.

And voila, you can run and test the project for yourself!
