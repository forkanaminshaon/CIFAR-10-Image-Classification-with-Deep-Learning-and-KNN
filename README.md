# CIFAR-10 Image Classification with Deep Learning and KNN
This project explores the CIFAR-10 dataset, a standard benchmark dataset for image classification, through a comprehensive application of Deep Learning and K-Nearest Neighbors (KNN) approaches. The primary objective is to classify 32x32 pixel images into one of 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.
## Features and Highlights:

### Deep Learning with CNN:
  * Built and trained a Convolutional Neural Network (CNN) with TensorFlow/Keras.
  * Included techniques like early stopping and learning rate scheduling to prevent overfitting and optimize training.
  * Experimented with multiple optimizers: RMSprop, Adam, SGD, and Nadam.
  * Achieved progressive accuracy improvements using ReLU activations and dropout layers for regularization.

### KNN Classification:
 * Implemented a custom KNN algorithm for image classification.
 * Used Manhattan (L1) and Euclidean (L2) distance metrics for comparative analysis.
 * Performed cross-validation to evaluate model accuracy with varying hyperparameters (e.g., K values).

### Preprocessing and Augmentation:
 * Normalized pixel values for optimal model performance.
 * Conducted one-hot encoding of class labels for categorical output compatibility.
 * Analyzed data distribution and balanced specific classes (e.g., "bird," "deer," and "truck").

### Visualization and Insights:
 * Visualized model training history, including loss and accuracy curves.

## Tools and Libraries Used:
   * TensorFlow/Keras: Deep Learning framework for CNN implementation.
   * Matplotlib: For visualizations of training progress and validation.
   * NumPy & SciPy: Used for efficient data manipulation and distance calculations.
   * Custom KNN Implementation: Built from scratch for understanding distance-based classification.

## Results:
   * Achieved over 80% accuracy on the test dataset with the CNN model.
   * Demonstrated the utility of hyperparameter tuning in both CNN and KNN models.
   * Showcased performance trade-offs between deep learning and traditional machine learning methods.
