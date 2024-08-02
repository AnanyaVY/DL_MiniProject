Tuberculosis Detection Using Deep Learning
This project focuses on developing and evaluating a deep learning model to detect tuberculosis (TB) from chest X-ray images. 
The model leverages pre-trained convolutional neural networks (CNNs) to classify images and assist in TB diagnosis.

Project Structure

Data Downloading and Preparation:
The dataset is automatically downloaded from a specified source, uncompressed, and prepared for training and validation.

Model Creation:
A function create_model is provided to build and compile the deep learning model. This function uses a pre-trained base model, applies global average pooling, and adds a dense layer with softmax activation for classification into TB-positive or TB-negative categories.

Model Evaluation:
A function evaluate_model is used to assess the model's performance. It makes predictions on the validation dataset, computes a confusion matrix, and prints the accuracy score along with a detailed classification report.

Requirements

Python 3.x
TensorFlow
Keras
NumPy
Scikit-learn
Matplotlib

Results
The notebook will guide you through the entire process of training the TB detection model and evaluating its performance on the validation dataset. 
The final output includes accuracy, confusion matrix, and a classification report.

