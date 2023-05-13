This code demonstrates the implementation of a Convolutional Neural Network (CNN) for gender detection using the Keras library with TensorFlow backend.

The dataset consists of facial images of men and women, which are converted to arrays and labeled as 0 for male and 1 for female. The dataset is split into training and validation sets, with data augmentation performed on the training set to prevent overfitting.

The CNN model consists of multiple convolutional layers followed by max pooling, dropout, and batch normalization layers. The flattened output is passed through two fully connected layers with ReLU activation and dropout layers. The final output layer has a sigmoid activation function, providing the probability of the image belonging to the female gender.

The model is compiled with the Adam optimizer and binary cross-entropy loss function. The training history is recorded and plotted using Matplotlib.

The trained model is saved to disk as a Keras model file.

Requirements:

Python 3.x
TensorFlow 2.x
Keras
scikit-learn
OpenCV
Matplotlib
To run the code:

Download the dataset.
Extract the dataset and update the path in the code accordingly.
Install the required libraries mentioned above.
Run the code in any Python IDE or via command line.
