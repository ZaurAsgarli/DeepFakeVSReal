Deepfake vs Real Video Detection

This repository contains a Jupyter Notebook for detecting deepfake videos by combining image hashing and deep learning. It uses a DenseNet201 backbone for feature extraction and classification, enabling the detection of manipulated frames in video datasets.

Features
Frame Extraction & Preprocessing – Converts video frames into a format suitable for analysis.

Image Hashing – Leverages perceptual hashing to detect subtle differences between frames.

Deep Learning Model – Implements DenseNet201 in TensorFlow/Keras for robust classification.

Evaluation – Provides accuracy metrics, confusion matrix, and visual results.

Installation
Make sure you have Python 3.8+ installed, then install the required packages:

pip install tensorflow numpy pandas opencv-python imagehash matplotlib
Usage
Clone this repository:

git clone https://github.com/yourusername/deepfake-vs-real.git
cd deepfake-vs-real
Download and prepare your dataset (e.g., Kaggle Deepfake Detection Challenge).

Open the notebook:

jupyter notebook DeefakeVsReal_.ipynb
Run all cells in sequence to preprocess data, train the model, and evaluate results.

Dataset
This project is designed for publicly available deepfake datasets but can be adapted to other sources with similar structure.

Output
The notebook generates:

Training & validation accuracy/loss graphs

Confusion matrix for classification performance

Example predictions on test frames


