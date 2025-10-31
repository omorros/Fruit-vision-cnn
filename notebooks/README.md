# Notebooks Overview

This folder contains all Jupyter notebooks used in this project.

---

## `train_fruit_classifier.ipynb`

Train a CNN on the Fruits360 dataset:
- Preprocessing and normalization
- CNN model building and training (TensorFlow / Keras)
- Validation and accuracy evaluation
- Model export to `.keras` + label map `.json`

---

## `use_trained_model_tutorial.ipynb`

A complete **Colab tutorial** for reusing the trained model:
- Environment setup + GPU check
- Downloading Fruits360 via Kaggle API
- Loading a trained `.keras` model and `label_map.json`
- Uploading an image to classify via the model
- Evaluating model accuracy on full test set
- Backing up model to Google Drive or local download

This is ideal for users who want to **quickly test, evaluate, or extend** the model without retraining it.

---

You can run either notebook directly in Google Colab.
