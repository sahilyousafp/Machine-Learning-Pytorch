# Machine Learning in PyTorch 🔥

This repository contains a series of hands-on Machine Learning and Deep Learning projects built with **Python** and **PyTorch**, following the *Zero to Mastery: Learn PyTorch for Deep Learning* course.

---

## 📚 Table of Contents

* [Overview](#overview)
* [Projects](#projects)

  * [Binary Classification – Linear Model](#binary-classification--linear-model)
  * [Binary Classification – Non‑Linear Model](#binary-classification--non‑linear-model)
  * [Multi‑Classification Model](#multi‑classification-model)
  * [Computer Vision without CNN](#computer-vision-without-cnn)
  * [Computer Vision with CNN](#computer-vision-with-cnn)
  * [Food Identifier (TinyVGG)](#food-identifier-tinyvgg)
* [Requirements](#requirements)
* [Usage Examples](#usage-examples)
* [Helper Scripts](#helper-scripts)
* [License](#license)

---

## Overview

These projects demonstrate how to build and train diverse ML models using PyTorch, ranging from basic linear classifiers to convolutional neural networks (CNNs). Curriculum includes:

* ✅ Linear regression
* ✅ Rectified (ReLU) models for non-linear separability
* ✅ Multi-class classification
* ✅ Image classification with and without CNN
* ✅ Custom dataset training using TinyVGG architecture

---

## Projects

### Binary Classification – Linear Model

A linear regression model for predicting y-values on a straight-line dataset.
![Linear Model Output](images/binary_linear_output.png)

### Binary Classification – Non‑Linear Model

Modeling circular separation using a ReLU layer to handle non-linear patterns.
![Non-linear Model Output](images/binary_nonlinear_output.png)

### Multi‑Classification Model

Extends the ReLU design for handling multiple class outputs in 2D feature space.
![Multi-class Output](images/multiclass_output.png)

### Computer Vision without CNN

A basic fully-connected model (MLP) trained on FashionMNIST to classify clothing items.
![FC Model FashionMNIST](images/fc_fashionmnist.png)

### Computer Vision with CNN

A 2D CNN to improve accuracy on FashionMNIST classification tasks.
![CNN FashionMNIST](images/cnn_fashionmnist.png)

### Food Identifier (TinyVGG)

A custom TinyVGG CNN trained on a food image dataset, including data augmentation for robustness.
![TinyVGG Food Classifier](images/tinyvgg_food.png)

---

## Requirements

```bash
# Clone the repo
git clone https://github.com/sahilyousafp/Machine-Learning-Pytorch.git
cd Machine-Learning-Pytorch

# Install dependencies
pip install torch torchvision matplotlib numpy
```

---

## Usage Examples

Launch any `.py` script or Jupyter Notebook. Example:

```bash
python Binary_Classification_linear_model.py
```

To explore results visually, open the Jupyter notebook:

```bash
jupyter notebook model_using_custom_data_set.ipynb
```

---

## Helper Scripts

* `helper_functions.py`: Utility functions for model training, data plotting, accuracy computation, and device configuration.

---

## License

This project is released under the **MIT License**—feel free to use, modify, and distribute it!

---

### 🔗 References

* Inspired by the *Zero to Mastery: Learn PyTorch for Deep Learning* course.
* Data sources include FashionMNIST and custom food image dataset.

---

Feel free to **fork**, **star ⭐️**, and contribute! If you'd like me to update actual screenshots or add badges (e.g. build status), just let me know.
