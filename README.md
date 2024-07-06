# Pakistani_Currency_NotePrediction
This project aims to detect and classify Pakistani currency notes using a deep learning model based on the ResNet50V2 architecture. The model is trained on a dataset of currency images and is capable of predicting Pakistani currency notes. The model achieves an accuracy of 92%.

**Usage**

Upload the dataset and necessary files using the provided Python scripts.
Extract the dataset and prepare data generators for training and validation.
Train the model and evaluate its performance using the provided scripts.

**Dataset**

The dataset consists of images of various denominations of Pakistani currency notes. It is divided into training and validation sets.

**Model Architecture**

The model is based on the ResNet50V2 architecture with additional custom layers for the classification task. The base ResNet50V2 model is pre-trained on ImageNet and fine-tuned on the currency dataset.

**Training**

The model is trained using the following parameters:

Optimizer: Adamax
Loss Function: Categorical Crossentropy
Metrics: Accuracy
Epochs: 40

**Evaluation**

The model achieves an accuracy of 92% on the validation set. The performance is visualized using plots for training and validation loss and accuracy.

**Model Saving and Loading**

The trained model is saved to a specified path and can be loaded later for prediction.

**Prediction**

The project includes scripts to preprocess a test image and predict its class using the trained model. The predicted class is then displayed along with the test image.

**Results**

The model achieves a validation accuracy of 92%, indicating good performance in classifying Pakistani currency notes.
