# Diabetic Retinopathy Detection using CNN

This project aims to develop a Convolutional Neural Network (CNN) model to detect diabetic retinopathy from retinal images. The model classifies the images into five categories: No_DR, Mild, Moderate, Severe, and Proliferate_DR. 

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Dependencies](#dependencies)
4. [Usage](#usage)
5. [Model Training](#model-training)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Project Overview
Diabetic retinopathy is a diabetes complication that affects eyes. Early detection through image analysis can help in timely treatment and management. This project uses a deep learning approach to automatically classify retinal images.

## Dataset
The dataset used in this project consists of retinal images categorized into five classes based on the severity of diabetic retinopathy. The images are stored in separate folders for each class.

### Dataset Structure:
- `Mild/`
- `Moderate/`
- `Severe/`
- `Proliferate_DR/`
- `No_DR/`

## Dependencies
To run this project, you need the following libraries and tools installed:

- TensorFlow
- Keras
- OpenCV
- Matplotlib
- NumPy
- Pandas
- pathlib
- glob
- PIL (Pillow)
- imblearn (imbalanced-learn)
- tqdm

You can install these dependencies using `pip`:
```sh
pip install tensorflow keras opencv-python matplotlib numpy pandas pathlib glob pillow imbalanced-learn tqdm
Usage
```
## Clone the repository:
```sh
git clone https://github.com/your-repo/diabetic-retinopathy-cnn.git
```
