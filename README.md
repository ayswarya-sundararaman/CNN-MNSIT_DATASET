

# CNN - MNIST Dataset

This project implements various Convolutional Neural Network (CNN) architectures to classify handwritten digits from the MNIST dataset using Keras. Different architectures, including layers with varying kernel sizes and regularization techniques, were explored.

## Dataset
- **Dataset**: MNIST (60,000 training images, 10,000 test images).
- **Input Shape**: 28x28 grayscale images.
- **Classes**: 10 (digits 0-9).

## Architectures
1. **Model 1**: 
   - 3 Convolutional layers (kernels: 3x3, 5x5, 2x2), 3 MaxPooling layers, Dropout, and Batch Normalization.
   - Optimizer: Adam, Activation: ReLU.
   
2. **Model 2**:
   - 5 Convolutional layers (kernels: 3x3, 5x5, 2x2), 5 MaxPooling layers, Dropout, and Batch Normalization.
   - Optimizer: Adam, Activation: ReLU.
   
3. **Model 3**:
   - 7 Convolutional layers (kernels: 3x3, 5x5, 2x2, 7x7), 7 MaxPooling layers, Dropout, and Batch Normalization.
   - Optimizer: Adam, Activation: ReLU.

## Key Observations
- Higher number of convolution layers improves accuracy and reduces loss.
- **Dropout** and **Batch Normalization** help reduce overfitting and improve generalization.
- The best accuracy achieved: **99.3%** with Model 3.

## Results Summary
- **Model 1**: Test Accuracy: 99.1%
- **Model 2**: Test Accuracy: 99.2%
- **Model 3**: Test Accuracy: 99.3%

## Conclusion
As the number of convolution layers increases, both training and validation accuracy improve significantly. Regularization techniques like dropout and batch normalization enhance model performance, avoiding overfitting.

