# Handwriting Recognition & Image Enhancement

A deep-learning application that recognizes handwritten words from images.
The system uses a Convolutional Recurrent Neural Network (CRNN) consisting
of a CNN for visual feature extraction and a bidirectional LSTM for
sequence modeling.

## Features

- Upload handwritten word images
- Preserve image proportions during preprocessing
- Extract handwriting features using a CNN
- Model character sequences using a BiLSTM
- Decode predictions into readable text
- Image enhancement support using ESRGAN

## Architecture

Image
↓
Grayscale + Resize
↓
CNN Feature Extractor
↓
BiLSTM
↓
CTC Decoder
↓
Predicted Text

