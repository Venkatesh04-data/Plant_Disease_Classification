Plant Disease Classification Using CNN

Project Overview
This project implements a Convolutional Neural Network (CNN) to classify plant leaf images into healthy or diseased categories. The goal is to help farmers and agricultural researchers identify plant diseases quickly and accurately.

Input: Leaf images

Output: Predicted class (Healthy / Diseased type)

Dataset
The project uses a subset of the PlantVillage dataset from Kaggle.

Dataset link: https://www.kaggle.com/datasets/emmarex/plantdisease

Note: The dataset itself is not included in this repo. Only sample test images are provided for demonstration.

Project Structure

Plant_Disease_Classification/
│
├── Plant_Disease_Prediction_CNN_Image_Classifier.ipynb # Main notebook
├── test_apple_black_rot.JPG # Sample test images
├── test_blueberry_healthy.jpg
├── test_potato_early_blight.jpg
├── .gitignore # Git ignore file
└── README.md # Project documentation

How to Run

Clone the repo:
git clone https://github.com/Venkatesh04-data/Plant_Disease_Classification.git

cd Plant_Disease_Classification

Install required packages (Python 3.8+ recommended):
pip install tensorflow keras numpy matplotlib

Open the notebook and run the cells:
jupyter notebook Plant_Disease_Prediction_CNN_Image_Classifier.ipynb

Test on sample images: The notebook contains example inference using the provided sample images.

Model

Architecture: Convolutional Neural Network (CNN)

Framework: TensorFlow / Keras

Features: Image preprocessing, model training, and inference

Results

The notebook demonstrates accuracy on sample images

You can extend it to the full dataset by downloading it from Kaggle.

Notes

Large datasets and Kaggle API keys are excluded for privacy and repo size management.

Only sample images and code are included for demonstration.

Author
Venkatesh Gudade
GitHub: https://github.com/Venkatesh04-data
