# Fruit360 CNN Classifier

A Convolutional Neural Network (CNN) trained to classify fruit images using the [Fruits360 dataset](https://www.kaggle.com/datasets/moltean/fruits).  
This is a standalone image classification project developed as part of my personal portfolio. The model may be extended or integrated into future systems involving food recognition or inventory tracking.

---

## Project Structure
fruit-vision-cnn/
├── fruit360_cnn_training.ipynb # CNN training notebook (Colab)
├── model/
│ ├── fruit_model.h5 # Saved trained model 
│ └── label_map.json # Label-to-class mapping 
├── README.md

---

## Model Overview

- **Model type**: Convolutional Neural Network (CNN)
- **Framework**: TensorFlow / Keras
- **Dataset**: Fruits360 – 100+ fruit categories, ~50,000 images
- **Input shape**: 100x100 RGB
- **Training accuracy**: ~XX% (to be updated)
- **Loss function**: Categorical Crossentropy
- **Optimizer**: Adam

---

## How to Use

Open the notebook in Google Colab (auto-linked):  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

Or clone locally:

bash
git clone https://github.com/omorros/fruit-vision-cnn.git
cd fruit-vision-cnn
Then run the training notebook or convert it into .py scripts.

---

## Future Applications

This project is designed to stand alone, but it may be adapted or reused in larger systems such as:

Grocery recognition apps

AI-powered food management tools

Personal AI experiments

---

## Requirements

Python 3.10+

TensorFlow / Keras

NumPy, matplotlib, scikit-learn

See notebook for full list of dependencies.