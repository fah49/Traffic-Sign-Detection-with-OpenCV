# Traffic Sign Detection with OpenCV & Keras

**Traffic Sign Detection** is a Python project that uses OpenCV and a convolutional neural network (Keras/TensorFlow) to detect and classify traffic signs. It’s structured into three main components:

- **gui.py**  
  Graphical interface to test real-time detection on live webcam or image input.
  
- **main.py**  
  Model training pipeline: loads labeled dataset, preprocesses images, trains CNN, saves model as `model_trained.h5`.
  
- **model_trained.h5**  
  Trained CNN model used by `gui.py` for inference.

---

## 📦 Features

- Training: Builds and trains a CNN to classify traffic signs.
- Inference: Detects and displays traffic sign classes from images or a webcam.
- Modular design: Training separated from inference for easy testing and deployment.

---

## 🧰 Installation

1. Clone:
   ```bash
   git clone https://github.com/fah49/Traffic-Sign-Detection-with-OpenCV.git
   cd Traffic-Sign-Detection-with-OpenCV
