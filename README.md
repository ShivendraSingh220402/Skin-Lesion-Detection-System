Skin Lesion Classification Project
This repository contains a machine learning project for classifying skin lesions into different categories. The project is designed to leverage the 
HAM 10000 dataset and implement various deep learning models for accurate classification. The models used in this project include ResNet, DenseNet, InceptionV3, and a custom Convolutional Neural Network (CNN).

Project Structure

The project is organized into multiple files:

1.	Data Collection (data_collection.ipynb):
•	This notebook focuses on gathering and preprocessing the HAM 10000 dataset.
•	It includes the steps for splitting the data into training, testing, and validation sets.
•	Basic cleaning of the dataset is performed to ensure high-quality input for model training.

2.	ResNet Model (Final_resnet50.ipynb):
•	Implementation of a deep neural network using the ResNet architecture.
•	Training, validation, and testing procedures for the ResNet model are outlined in this notebook.

3.	DenseNet Model (Final_densenet_model.ipynb):
•	This notebook details the creation and training of a deep neural network using the DenseNet architecture.
•	Evaluation metrics and results are provided for the DenseNet model.

4.	InceptionV3 Model (Final_inceptionv3_model.ipynb):
•	Implementation and training of a deep neural network using the InceptionV3 architecture.
•	Model evaluation and comparison to other architectures are discussed in this notebook.

5.	Custom CNN Model (New_cnn.ipynb):
•	Development and training of a custom Convolutional Neural Network tailored for skin lesion classification.
•	Results and insights from this custom model are documented.

How to Use

1.	Clone the Repository
2.	Install Dependencies:
    pip install -r requirements.txt 

3.	Run Notebooks:
•	Open and run the Jupyter notebooks in the order specified in the project structure.
•	Each notebook contains detailed explanations and comments to guide you through the process.

4.	Explore Results:
•	Review the results, metrics, and visualizations provided in each notebook.
•	Compare the performance of different models and architectures.

Requirements
•	Python 3.x
•	Jupyter Notebooks
•	TensorFlow
•	NumPy
•	Matplotlib
•	Other dependencies specified in requirements.txt

Acknowledgments
•	The HAM 10000 dataset: link

Author
•	Shivendra Singh
•	Contact: shivendrasingh220402@gmail.com

Feel free to fork, modify, and experiment with this project. If you find any issues or have suggestions for improvements, please open an issue.
Happy coding!
