# Making Prediction Room


- **Data Collection:** Kaggle dataset: Messy vs. Clean Room.
Images collected for clean and messy rooms.

- **Data Preprocessing:** Used ImageDataGenerator for augmentation.
Rescaled, rotated, flipped, and applied shear.

- **Model Definition (CNN):** Sequential model with Conv2D, MaxPooling2D, Flatten, Dense layers.
Sigmoid activation for binary classification.
Compiled using binary crossentropy loss and Adam optimizer.

- **Model Training and Evaluation:** Trained for 25 epochs with monitoring accuracy and loss.
Plotted accuracy and loss curves.

- **Prediction with New Data:** Saved and loaded the model.
Predicted new images ('clean.jpg' and 'messy.jpg').
