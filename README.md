# Speaker Identification CNN Model

## Project Overview
A Convolutional Neural Network (CNN) for speaker identification using audio MNIST dataset, implemented in Python with PyTorch.

## Features
- Audio file processing with librosa
- MFCC feature extraction
- CNN-based speaker recognition
- Performance metrics and model evaluation

## Requirements
- Python 3.8+
- PyTorch
- librosa
- numpy
- scikit-learn
- tqdm
- matplotlib

## Dataset
- Audio MNIST dataset from Kaggle
- 60 speakers
- 10 digits (0-9)
- 50 recordings per digit per speaker

## Model Architecture
- 3 convolutional blocks
- 2-layer fully connected classifier
- Batch normalization
- Dropout regularization


## Usage
1. Install dependencies
2. Run `Main.ipynb`
3. Upload your kaggle key 

## Performance Metrics
- Accuracy: Tracked during training
- Precision, Recall, F1-Score calculated
- Best model saved automatically

## License
MIT License
