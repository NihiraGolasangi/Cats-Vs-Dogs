# Cats-Vs-Dogs

This project involves building a cat-dog classifier using convolutional neural networks (CNNs) and transfer learning using the VGG16 architecture. The dataset consists of thousands of images of cats and dogs.

The first step in the project involved data preprocessing, including data cleaning and image resizing and augmentation. Next, the dataset was split into training and testing sets, with the former used to train the CNN and VGG16 models, and the latter used to evaluate the performance of the models.

The CNN was built from scratch, with multiple convolutional layers, max-pooling layers, and fully connected layers. The model was trained on the training set and evaluated on the testing set, with performance metrics such as accuracy used to evaluate the model's performance.

The VGG16 model was then implemented using transfer learning, with the pre-trained weights from the ImageNet dataset used as a starting point. The final layer of the VGG16 model was replaced with a new fully connected layer for binary classification of cats and dogs. The model was then fine-tuned on the training set and evaluated on the testing set, with performance metrics again used to evaluate the model's performance.

The final step in the project involved comparing the performance of the CNN and VGG16 models. It was found that the VGG16 model outperformed the CNN, with higher accuracy and F1 score. The project was implemented using Python and various machine learning libraries, such as Keras and TensorFlow.
