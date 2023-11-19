# Feature-selection-and-data-visualization-on-Breast-Cancer-dataset

Overview

This dataset aims to predict whether a breast mass is benign or malignant based on computed features from digitized images of fine needle aspirates (FNA). The features describe characteristics of cell nuclei present in the images.

Data Content

ID number

Diagnosis (M = malignant, B = benign)

3-32) Ten real-valued features for each cell nucleus:

a) Radius (mean of distances from center to points on the perimeter)

b) Texture (standard deviation of gray-scale values)

c) Perimeter

d) Area

e) Smoothness (local variation in radius lengths)

f) Compactness (perimeter^2 / area - 1.0)

g) Concavity (severity of concave portions of the contour)

h) Concave points (number of concave portions of the contour)

i) Symmetry

j) Fractal dimension ("coastline approximation" - 1)

The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For example, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius. All feature values are recoded with four significant digits.

Dataset Information

Source: UCI Machine Learning Repository

Class Distribution: 357 benign, 212 malignant

Attributes: 1) ID number, 2) Diagnosis (M = malignant, B = benign), 3-32) Ten real-valued features.

Usage

This dataset is suitable for tasks related to classification, particularly in predicting whether a breast mass is benign or malignant. Features include measurements related to the radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.

Citation

The dataset is described in the following paper:

[K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].
