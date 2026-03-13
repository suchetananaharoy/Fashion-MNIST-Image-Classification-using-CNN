# Fashion-MNIST Image Classification using CNN

## Project Overview
This project implements a Convolutional Neural Network (CNN) to classify clothing images from the Fashion-MNIST dataset. The model learns important visual patterns such as edges, textures, and shapes to identify different clothing categories. The workflow includes data preprocessing, visualization, CNN model training, evaluation, and prediction.

## Dataset
The Fashion-MNIST dataset contains grayscale images of clothing items used for image classification.

**Dataset Details**

- Total Images: 70,000
- Training Images: 60,000
- Test Images: 10,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10

| Label | Category |
|------|----------|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

## Project Workflow

1. Import libraries
2. Load dataset
3. Data preprocessing
4. Exploratory Data Analysis (EDA)
5. CNN model construction
6. Model training
7. Model evaluation
8. Prediction visualization

## CNN Model Architecture

The model uses convolution and pooling layers to extract image features.

```
Conv2D (32 filters, 3x3) + ReLU
MaxPooling2D (2x2)

Conv2D (64 filters, 3x3) + ReLU
MaxPooling2D (2x2)

Flatten
Dense (128) + ReLU
Dense (10) + Softmax
```

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Results

The CNN model learns image patterns effectively and achieves strong classification performance.

- Training Accuracy: ~92–95%
- Test Accuracy: ~89–92%

## Visualizations Included

- Sample dataset images
- Pixel intensity distribution
- Training vs validation accuracy
- Model predictions

## How to Run the Project

Clone the repository

```
git clone https://github.com/yourusername/fashion-mnist-cnn.git
```

Install dependencies

```
pip install tensorflow numpy matplotlib scikit-learn
```

Run the project

```
python cnn_fashion_mnist.py
```

## Future Improvements

- Data augmentation
- Hyperparameter tuning
- Transfer learning with pretrained CNNs
- Deployment as a web application

## Author

Machine Learning and Deep Learning project demonstrating CNN-based image classification using the Fashion-MNIST dataset.
