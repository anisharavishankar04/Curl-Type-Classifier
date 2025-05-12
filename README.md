# Curl Type Classifier

This project builds a deep learning model that classifies wavy and curly hair images into the following classes: 2A/2B, 2C, 3A/3B, and 3C. Type 2 represents wavy hair and Type 3 represents curly hair. Types 2A and 2B have been combined and Types 3A and 3B have been combined as the differences between these classes are extremely subtle. Separating them would not have been feasible, given the small dataset.

## Dataset

The model was trained on a manually curated dataset of 400 images: 100 images per class. Each image was obtained from various sources like Pinterest, Google, etc., and cropped to ensure the accuracy of the model. Despite the small dataset size and the subtle differences between the classes, the model achieved a testing accuracy of 81.67%.
<br>**The dataset used in this project has not been provided due to copyright restrictions.**

## Architecture

The model uses EfficientNetB2, a pre-trained CNN (Convolutional Neural Network) model. Hyperparameters like dropout, learning rate, etc., were fine-tuned to achieve the accuracy.

## Results

- **Validation Accuracy**: 84.75%
- **Testing Accuracy**: 81.67%

## Installation

You don't need to install anything locally to run this project. You can use Google Colab to run the notebook.

## Usage Instructions

1. Clone the repository using the following command:
   ```bash
   git clone https://github.com/anisharavishankar04/Curl-Type-Classifier.git

2. Open Google Colab on your browser and sign in.

3. If the pop-up doesn't automatically show up, go to File -> Open notebook -> Upload. Either browse and add the .ipynb file or simply drag it onto the screen. The notebook will open in Google Colab.

4. Create your dataset and upload it onto your Google Drive. The dataset used in this project has not been provided due to copyright restrictions.

5. Go back to your Colab notebook and change the runtime type to T4 GPU: Runtime -> Change runtime type -> T4 GPU

6. In the Colab notebook, go to Runtime -> Run All to run the entire notebook.

7. You will be prompted to connect your Google Drive when the corresponding cell runs.

8. Run the rest of the cells, and that completes the execution.



