# Cat and Dog Image Classification Using SVM
## Project Overview
This project involves classifying images of cats and dogs using a Support Vector Machine (SVM) model. The dataset used for this task was sourced from Kaggle. The primary objective was to explore the performance of SVM in image classification tasks and understand its limitations.

## Features
- Image Classification: Used to distinguish between images of cats and dogs.
- Support Vector Machine (SVM): Implemented as the classification model to analyze its effectiveness on image data.

## Model Performance
The SVM model was used for classification, but the accuracy achieved was not as high as expected. The reasons for this include:

- High Dimensionality: Image data is high-dimensional, which can pose challenges for SVM, as it is better suited for lower-dimensional data.
- Feature Extraction: SVM relies on manual feature extraction methods, which may not capture the complex patterns in images as effectively as deep learning models.

## Improvements with CNN
To improve the classification accuracy, a Convolutional Neural Network (CNN) would be a better choice. CNNs are specifically designed for image data and offer several advantages:

- Automatic Feature Extraction: CNNs automatically learn relevant features from images through convolutional layers, making them more effective for image classification tasks.
- Spatial Hierarchies: CNNs capture spatial hierarchies in images, allowing them to recognize patterns and objects more accurately.
- Scalability: CNNs scale better with large datasets, which is often necessary for achieving high accuracy in image classification.

## Technologies Used
- Python
- Pandas & NumPy: For data manipulation and preprocessing.
- Scikit-learn: For implementing the SVM model.
- OpenCV/PIL: For image processing and handling.
- Matplotlib/Seaborn: For visualizing results and data.

## Usage
- Load the dataset: Ensure that the Kaggle dataset of cat and dog images is available in the specified path.
- Run the SVM model: Execute the script to classify the images and evaluate the performance.
- Analyze the Results: Review the accuracy and consider the benefits of using CNN for future improvements.
