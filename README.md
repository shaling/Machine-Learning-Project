# Machine-Learning-Project
## Cat vs Dog Image Classification using CNN
### Project Overview
This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images of cats and dogs. The model achieves 81.65% validation accuracy on the test set.

### Dataset
Training set: 8,000 images (4,000 cats, 4,000 dogs)
Test set: 2,000 images (1,000 cats, 1,000 dogs)
Image size: 64x64 pixels, RGB format
### Model Architectur
- Conv2D (32 filters, 3x3 kernel, ReLU)
- MaxPooling2D (2x2)
- Conv2D (64 filters, 3x3 kernel, ReLU)
- MaxPooling2D (2x2)
- Flatten
- Dense (128 units, ReLU)
- Dropout (0.5)
- Dense (1 unit, Sigmoid)

### Performance
Training accuracy: 94.40%
Validation accuracy: 81.65%
Loss: 0.1428
Validation loss: 0.7277

