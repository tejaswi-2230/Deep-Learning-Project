# Overview
This project is a machine learning-based Eye Diseases Detector that classifies images into four categories of eye diseases:

- Cataract
- Diabetic Retinopathy
- Glaucoma
- Normal (No Disease)
- The model is built using TensorFlow and Keras, leveraging deep learning techniques for image classification.

# Features
- Deep Learning Model: Uses InceptionResNetV2 as the base model for feature extraction.
- Data Augmentation: Implements ImageDataGenerator for preprocessing.
- Training and Evaluation:
  - Splits dataset into training (80%), validation (10%), and test (10%).
  - Uses Adamax optimizer and categorical cross-entropy as the loss function.
  - Implements batch normalization and dropout to improve model performance.
