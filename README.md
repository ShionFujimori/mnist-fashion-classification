# mnist-fashion-classification
MNIST fashion classification: 10-class classification using Convolutional Neural Network (CNN)

# Data
An MNIST-like dataset of 70,000 28x28 labeled fashion images
- Train: 48000 images
- Validation: 12000 images
- Test: 10000 images

# Model
- 2D-CNN (Conv -> MaxPool -> Conv -> MaxPool -> Flatten -> Dense-512 -> Dense-10 -> Softmax)
- Implemented in tensorflow.keras
<img width="1215" alt="model" src="https://user-images.githubusercontent.com/33429115/80071425-94158300-857f-11ea-8793-8c232944c498.png">
