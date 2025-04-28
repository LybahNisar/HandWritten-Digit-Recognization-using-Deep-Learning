# Handwritten Digit Recognition using Deep Learning

This project implements a handwritten digit recognition system using the MNIST dataset. It showcases multiple deep learning techniques such as Dense Neural Networks, Convolutional Neural Networks (CNNs), Data Augmentation, Dropout, and Autoencoders for performance enhancement and image reconstruction.

## 🧠 Project Highlights

- **Dataset**: MNIST handwritten digits (28x28 grayscale images)
- **Framework**: TensorFlow / Keras
- **Techniques**:
  - Dense Neural Networks
  - Convolutional Neural Networks (CNNs)
  - Pooling (MaxPooling and AveragePooling)
  - Dropout regularization
  - Data Augmentation (horizontal flip, zoom)
  - Deeper CNN Architectures
  - Autoencoder for super-resolution reconstruction

## 📈 Final Results

| Model                          | Test Accuracy |
|---------------------------------|---------------|
| Dense Neural Network            | ~96.2%        |
| Simple CNN (Conv + Flatten)      | ~97.7%        |
| CNN + Average Pooling            | ~98.1%        |
| CNN + Dropout Regularization     | ~98.6%        |
| Deeper CNN (3 Conv layers)       | ~99.1%        |
| Autoencoder Image Reconstruction| High-quality (loss ~0.0045) |

---


---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/handwritten-digit-recognition.git
cd handwritten-digit-recognition

## 📊 Key Features

- Model training with different architectures (Dense Networks, CNNs)
- Evaluation using accuracy and loss curves
- Data Augmentation techniques:
  - Zoom transformations
  - Horizontal flipping
- Dropout for regularization to prevent overfitting
- Autoencoder for reconstructing high-resolution images from low-resolution inputs

---

## 📸 Sample Outputs

- Training and Validation **Accuracy** plots
- Training and Validation **Loss** plots
- **Augmented Images** (Zoomed and Horizontally Flipped)
- **Reconstructed Images** using Autoencoders




