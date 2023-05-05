Breast Cancer Detection Using Artificial Neural Network

About DATASET:

Breast Cancer Wisconsin (Diagnostic) Data Set

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. 
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server: 
ftp ftp.cs.wisc.edu 
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

1) ID number 
2) Diagnosis (M = malignant, B = benign) 
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter) 
b) texture (standard deviation of gray-scale values) 
c) perimeter 
d) area 
e) smoothness (local variation in radius lengths) 
f) compactness (perimeter^2 / area - 1.0) 
g) concavity (severity of concave portions of the contour) 
h) concave points (number of concave portions of the contour) 
i) symmetry 
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

ABOUT ANN:

ANN stands for Artificial Neural Network, which is a type of machine learning algorithm inspired by the structure and function of the human brain. 
ANN consists of interconnected nodes, called artificial neurons or simply neurons, organized into layers. 
These neurons receive inputs from other neurons or the external world, process the inputs, and produce an output signal that is transmitted to other neurons or the output layer.

The input layer of an ANN receives input data, such as images, text, or numerical features. 
The output layer produces the final output, such as a classification label or a regression value. 
The intermediate layers between the input and output layers are called hidden layers
and they process the inputs and transform them into more useful representations.

The connections between neurons in an ANN are weighted, which means that each connection has a numerical value that determines the strength of the connection.
During training, the weights are adjusted to minimize a loss function that measures the difference between the predicted output and the true output.

ANNs are capable of learning complex patterns and relationships in the data, making them useful for a wide range of applications,
such as image recognition, natural language processing, and prediction.
They can be trained using various optimization techniques, such as backpropagation and stochastic gradient descent.

ANNs have been used successfully in many real-world applications 
including speech recognition, image classification, recommendation systems, and autonomous vehicles. 
However, they can be computationally expensive and require a large amount of data to train effectively.

Conclusion:

We have the plot visulaisation after the development of the prediction model.



![ANNBC](https://user-images.githubusercontent.com/103871423/236562631-ca541238-775f-4a79-9057-fb0d0c6a8bb5.png)
