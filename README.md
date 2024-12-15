# Machine-Learning-Project
## Cat vs Dog Image Classification using CNN
### Project Overview
This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images of cats and dogs. The model achieves 79.25% validation accuracy on the test set.
### Installations and Dependencies
This project was developed using Python in Jupyter Notebook. The key dependencies are:
- tensorflow
- numpy
- matplotlib
- keras
- PIL (Python Imaging Library)

### Project Structure
The project consists of the following main components:
#### Data Organization:
- Training set: 8000 images (4000 cats + 4000 dogs)
- Test set: 2000 images (1000 cats + 1000 dogs)
- Single prediction folder: For testing individual images
- Data augmentation with rotation, zoom, and flip

you can get data from the following link:
https://drive.google.com/drive/folders/1DCOqRyd4hW5hhcPwZyXUQlwcqaRZ0mMV?usp=share_link 

#### Model Architectur:
- Sequential CNN model using TensorFlow/Keras
- Input shape: (64, 64, 3)
- First Conv Layer: 64 filters, 3x3 kernel, ReLU
- MaxPooling: 2x2
- Second Conv Layer: 128 filters, 3x3 kernel, ReLU
- MaxPooling: 2x2 with Dropout(0.3)
- Dense Layer: 256 units with Dropout(0.4)
- Output Layer: 1 unit, sigmoid activation
#### Training Configuration:
- Optimizer: Adam
- Loss function: Binary crossentropy
- Metrics: Accuracy
- Epochs: 30
- Batch size: 32
- Steps per epoch: 250
- Validation steps: 63
### Performance Metrics
Final model performance:
- Training accuracy: 83.09%
- Validation accuracy: 79.25%
- Training loss: 0.3781
- Validation loss: 0.4635
### Features
- Image preprocessing and augmentation
- Real-time data generation
- Single image prediction capability
- Visualization of predictions
- Model performance monitoring

### Medium Link:
https://medium.com/@qhe_95131/my-journey-with-image-classification-using-cnn-14ef397bf4c3

