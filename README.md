# Deep Learning of Chest vs. Abdominal X-ray Classification

## Overview
This project focuses on the application of deep learning techniques to accurately classify medical images as either chest or abdominal X-rays. Utilizing a dataset of 75 de-identified images sourced from Open-i, we demonstrate the process of building and training a convolutional neural network model for this binary classification task. The project leverages the MD.ai platform for image annotation and the mdai Python client library for data preparation.

![Deep Learning](/images/1_kBXB9JfzdHSmNLQZjt1JXw.jpg)

## Features
- Utilization of MD.ai for DICOM image display and annotation.
- Preparation of image datasets for training, validation, and testing.
- Training of a deep learning model using TensorFlow's Keras API.
- Evaluation of model performance with test datasets.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.x installed on your machine.
- Access to Google Colab for executing the notebook with GPU support.

## Installation
To set up the project environment, follow these steps:

1. Clone the repository to your local machine or Google Colab environment:

git clone https://github.com/ImagingInformatics/machine-learning

2. Install the required Python packages:

pip install -q -U mdai tensorflow

3. Navigate to the project's URL on MD.ai and create an account or log in to access the image dataset: [MD.ai annotator project](https://public.md.ai/annotator/project/PVq9raBJ).

4. Generate a personal access token on MD.ai to authenticate your session.

## Usage
To use the Chest vs. Abdominal X-ray Classification project, follow these steps:

1. Import the mdai client library and authenticate using your personal access token.
2. Define the project ID and create an mdai client instance.
3. Download the images and annotations using the mdai Python client library.
4. Prepare the datasets for training, validation, and testing.
5. Train the classification model using TensorFlow and Keras.
6. Evaluate the model's performance on the test dataset.

## Model
The project uses TensorFlow's Keras API to define and train a convolutional neural network model based on the MobileNet architecture, modified for the binary classification task. Training involves using a custom data generator for handling DICOM images and annotations.

## Results
The trained model demonstrates high accuracy in distinguishing between chest and abdominal X-rays. Specific performance metrics (e.g., accuracy, loss) are detailed within the Jupyter notebook.
![Results](/images/ew.jpg)

## Contributing to the Project
We welcome contributions to improve the Chest vs. Abdominal X-ray Classification project. Please follow the standard process for submitting issues or pull requests.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
- Thanks to Open-i for providing the image dataset.
- Utilization of the MD.ai platform for image annotation and dataset preparation.

