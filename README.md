# Cancer-Analysis
This program utilizes machine learning algorithms to predict breast cancer based on various features. The dataset used for training and testing the models contains information about breast cancer diagnosis, as well as several numerical features extracted from medical images.

Features
The dataset consists of the following features:

radius_mean: Mean of distances from the center to points on the perimeter.
texture_mean: Standard deviation of gray-scale values.
perimeter_mean: Perimeter of the tumor.
area_mean: Area of the tumor.
smoothness_mean: local variation in radius lengths.
compactness_mean: Perimeter^2 / area - 1.0.
concavity_mean: severity of concave portions of the contour.
concave points_mean: number of concave portions of the contour.
symmetry_mean: Symmetry of the tumor.
fractal_dimension_mean: "Coastline approximation" - 1.
And more...

Models
Two machine learning models have been implemented for breast cancer prediction:

Logistic Regression Model: This model utilizes logistic regression, a popular algorithm for binary classification, to predict the presence of breast cancer.

Random Forest Model: This model uses the random forest algorithm, which is an ensemble learning method that combines multiple decision trees to make predictions.

Usage
Clone the repository.
Install the required dependencies mentioned in the requirements.txt file.
Run both notebook to train and evaluate the models on the breast cancer dataset.
Optionally, explore the trained models and make predictions on new data.
