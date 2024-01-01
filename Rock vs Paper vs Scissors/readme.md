# Rock-Paper-Scissors Image Classification

Stages

- **Data Acquisition:** Downloaded the Rock-Paper-Scissors dataset from Kaggle, organizing images into 'rock,' 'paper,' and 'scissors' categories.

- **Data Augmentation:** Utilized ImageDataGenerator for data augmentation, applying rotation, horizontal flip, and shear, enhancing the model's ability to generalize.

- **Model Construction:** Developed a Convolutional Neural Network (CNN) using TensorFlow and Keras, comprising convolutional and pooling layers with dropout for regularization.

- **Training and Early Stopping:** Trained the model, implementing a custom callback for early stopping when both training and validation accuracy surpassed 95%.

- **Evaluation and Visualization:** Visualized accuracy and loss over epochs, ensuring the model's learning progress. Saved the trained model for future use.




