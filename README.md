# ForestFireDetection_AICTE

<h1>Problem Statement:</h1>
Forest fires are a major environmental hazard that cause widespread destruction to forests, wildlife, and nearby human settlements. They lead to the loss of biodiversity, damage to ecosystems, and significant air pollution due to smoke and harmful gases. 
Traditional fire detection methods, such as satellite imaging or manual surveillance, are often delayed, limited in coverage, and inefficient for immediate response. 
As climate change continues to increase the frequency and intensity of wildfires, there is a growing need for faster and smarter detection systems. Deep learning, particularly Convolutional Neural Networks (CNNs), offers a powerful solution for identifying fire patterns in images with high accuracy. 

<h1>Solution:</h1>
Import and Load the Dataset: Collected a labeled wildfire image dataset from Kaggle containing “fire” and “no fire” categories.
Preprocess the Data: Resized images to 150x150 pixels, normalized pixel values, and applied augmentation using Image Data Generator for better generalization.
Build the CNN Model: Designed a Convolutional Neural Network with Conv2D and MaxPooling layers for feature extraction.
Compile the Model: Used the Adam optimizer and binary cross-entropy loss function with accuracy as the evaluation metric.
Train the Model: Trained the CNN on the dataset for 12 epochs, monitoring training and validation performance.
Evaluate the Model: Assessed the model using validation accuracy and loss curves; achieved a validation accuracy of 82.29%.
Make Predictions: Tested the trained model on new/unseen images to detect and classify the presence of fire.


