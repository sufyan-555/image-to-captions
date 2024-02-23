# Image Captioning with Deep Learning

## Overview
This project implements an image captioning system using deep learning techniques. It generates textual descriptions of images by combining Convolutional Neural Networks (CNNs) for feature extraction and Recurrent Neural Networks (RNNs) for sequence generation. The model is trained on the Flicker8k dataset.

## Key Components
- **Feature Extraction:** Utilizes a pre-trained Xception model to extract features from input images.
- **Sequence Generation:** Employs a Long Short-Term Memory (LSTM) network to generate textual descriptions of images.
- **Tokenizer:** Tokenizes text data and converts words into numerical indices for model input.
- **Model Loading:** Loads pre-trained models for both feature extraction and sequence generation.
- **Image Processing:** Preprocesses input images for compatibility with the Xception model.

## Usage
1. Clone the repository to your local machine.
2. Install the necessary dependencies listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Provide the path to the input image using the `-i` or `--image` argument when running the script.
4. The script will generate a textual description of the input image and display it along with the image.