## Image-Classification-Using-Transfer-Learning-and-a-Built-in-Dataset





## Explanation of the Code


- Importing Libraries: We import TensorFlow, Keras modules, and Matplotlib for plotting.

- Loading CIFAR-10 Dataset: CIFAR-10 is a dataset of 60,000 32x32 color images in 10 classes. We load the dataset and normalize the images.

- Pre-trained Model: We use MobileNetV2 as our transfer learning model, excluding the top layers to customize it for our task.

- Building the Model: We add a global average pooling layer and a couple of dense layers to create our custom classifier.

- Training the Model: The model is trained using the Adam optimizer, and we report the training and validation loss and accuracy.

- Evaluation: After training, we evaluate the model's performance on the test set.

- Visualization: Finally, we visualize the training and validation accuracy and loss over epochs.



## Contributing

 Contributions are welcome! If you have suggestions for improvements or features, feel free to fork the repository and submit a pull request.


