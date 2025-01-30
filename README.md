## Image Classification Using Machine Learning
This project implements an image classification model to classify images into three categories: Animal, Flower, and Vehicles. The model uses support vector machine (SVM) classification, with grid search for hyperparameter tuning.

## Project Overview
The objective of this project is to classify images based on their content into one of the three categories. The images are resized, flattened, and then fed into a support vector machine classifier. Hyperparameter tuning is done using GridSearchCV for optimizing the model's performance.

## Libraries Used
os - for file handling and directory operations
matplotlib.pyplot - for image visualization
numpy - for numerical operations
skimage - for image reading and resizing
sklearn - for model training and evaluation
## Setup
Clone the repository to your local machine.

Install the required dependencies:

Copy
Edit
pip install -r requirements.txt
Where requirements.txt includes the necessary libraries like matplotlib, sklearn, scikit-image, and numpy.

## Data
The dataset is divided into three categories:

Animal
Flower
Vehicles
Each category folder contains images related to the respective class.

## How It Works
### Image Preprocessing:

Images are read using skimage.io.imread.
Each image is resized to a uniform size of (150, 150, 3) to normalize the data.
The resized images are flattened into a 1D array and stored in a list for further processing.
### Model Training:

The model uses a support vector machine (SVM) classifier with two kernels: linear and rbf (Radial Basis Function).
Hyperparameters such as C and gamma are optimized using GridSearchCV.
### Image Classification:

To classify a new image, the user provides the URL of the image.
The image is read and preprocessed (resized and flattened).
The model predicts the class of the image.

## Results
After training the model, you can use it to predict the category of any new image. The model will output the predicted category based on the trained data.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

# miniproject
VERGEO Internship Miniproject

DS-MINOR-APRIL   

MINOR PROJECT 1 ->  IMAGE CLASSIFICATION USING MACHINE LEARNING  

Google drive of project : 

https://drive.google.com/drive/folders/1-07mNETHRdfnDSFRC2hdmJSU6OSONbmn?usp=sharing
