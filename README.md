# Multi-class-Image-classification-with-Keras
Methodology
1. Read the images and their corresponding labels  {'buildings':0, 'forest':1, 'glacier':2, 'mountain':3, 'sea':4, 'street':5} into numpy arrays and explore them
2. Train a Convolutional Neural Network model in Keras (open-source neural network library running on top of Tensorflow) with seg_train data - 14000 images for training and seg_test data - 3000 images for validation.
3. Model evaluation and accuracy improvement from 83% to 90%.
"The model's overall accuracy on the test dataset has improved from 83% to 90% after the removal of two image classes from the training and testing datasets. **This confirms there are similar features in several glacier and mountain images(as well as street and building images or mountain and sea images) which the neural network fails to distinguish.** Should we proceed to use the first model(with 6 classes) or not ? Ultimately, the answer depends on the use case and the required classification accuracy level."
4. Predict the classes of the seg_pred images.
