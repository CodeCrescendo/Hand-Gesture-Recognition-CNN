# Hand-Gesture-Recognition-CNN
Hand gesture recognition for ASL using Convolutional Neural Networks (CNN) in PyTorch

1.Project Overview: This project focuses on recognizing American Sign Language (ASL) hand gestures using Convolutional Neural Networks (CNNs). The model is trained and evaluated on a dataset of grayscale images representing ASL letters.

2.Data Preprocessing: The dataset consists of 28x28 pixel grayscale images of hand gestures. The data is loaded and preprocessed, ensuring appropriate formatting for training and testing the CNN model.

3.Model Architecture: The CNN model includes two convolutional layers followed by ReLU activations and max pooling layers. The architecture captures both low-level and high-level features from the images.

4.Activation and Pooling: ReLU activation functions introduce non-linearity, and max pooling layers down-sample the feature maps, retaining crucial information and reducing spatial dimensions.

5.Dropout and Fully Connected Layers: A fully connected layer followed by a dropout layer (rate 0.2) is used to prevent overfitting and improve model generalization. The output layer consists of 26 nodes, one for each ASL letter class.

6.Training and Evaluation: The model is compiled using the Adam optimizer and trained for 10 epochs. Training progress is monitored through changes in loss and testing accuracy, with visualizations provided for analysis.

7.Overfitting and Performance: Observations on overfitting are recorded, and the impact of adding another dropout layer (rate 0.3) is explored. The model's success is evaluated based on accuracy and loss metrics, aiming to maximize classification accuracy.
