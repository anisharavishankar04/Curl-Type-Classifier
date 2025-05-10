Curl Type Classifier

This project builds a deep learning model that classifies wavy and curly hair images into the following classes: 2A/2B, 2C, 3A/3B, 3C. Type 2 represents wavy hair and Type 3 represents curly hair.

Dataset:
The model was trained on a manually curated dataset of 400 images: 100 images per class. Each image was obtained from various sources like Pinterest, Google, etc. and cropped to ensure the accuracy of the model. Despite the small dataset size and the subtle differences between the classes, the model achieved a testing accuracy of 81.67%.

Architecture:
The model used in EfficientNetB2, a pre-trained CNN (Convolutional Neural Network) model. Hyperparameters like dropout, learning rate, etc. were fine-tuned to achieve the accuracy. 

Results:
Validation Accuracy: 84.75%
Testing Accuracy: 81.67%


