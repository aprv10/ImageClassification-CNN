# 🔎 Image Classification with CNN

This project is a clean, beginner-friendly image classification pipeline using TensorFlow and Keras. It classifies images using a Convolutional Neural Network (CNN).

✅ Originally built for classifying "Happy" vs "Sad" faces  
🌍 Can be easily reused for **any image classification task**—just change the dataset folders!

## 🚀 Features

- Automatic image loading with `image_dataset_from_directory`
- Preprocessing + invalid image filtering
- Simple CNN model using Keras
- Works on both GPU and CPU
- Model saving for deployment

## 🗂️ Dataset Structure

    data/
    ├── ClassA/
    ├── ClassB/
    └── ... (add as many classes as needed)

## 🛠️ Setup

```bash
pip install tensorflow opencv-python matplotlib
```
Then run ImageClassification.ipynb step-by-step in Jupyter or Google Colab.

## 💡 Customize
Just replace the data/ folder with your own image dataset (in the same format), and the model will adapt automatically.

## 📦 Output
Trained model (.h5)

Accuracy/loss graphs

Ready for inference

