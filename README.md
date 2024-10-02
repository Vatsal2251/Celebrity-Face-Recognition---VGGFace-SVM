# Celebrity Recognition with VGGFace and SVM

This project explores a comparative study on celebrity recognition using AWS Rekognition and a custom-built support vector machine (SVM) model trained on VGGFace embeddings. It combines cloud-based solutions with locally trained models to evaluate the performance in identifying celebrities in images.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Project Setup](#project-setup)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project investigates the application of computer vision in identifying celebrities by leveraging pre-trained deep learning models and cloud-based APIs. Specifically, the VGGFace model is employed to extract embeddings from facial images, and a support vector machine (SVM) is used for classification. Additionally, AWS Rekognition is utilized to provide a comparative baseline for performance evaluation.

## Technologies Used
- **Python**: The core language used for this project.
- **VGGFace Model**: A deep learning model pre-trained on large-scale face datasets to generate embeddings.
- **AWS Rekognition**: A cloud service for image and video analysis.
- **Support Vector Machine (SVM)**: A machine learning algorithm for classification tasks.
- **Google Colab**: Used for code execution and collaboration.
- **boto3**: AWS SDK for Python, used to interact with AWS services.

## Project Setup

### Prerequisites
Ensure you have the following dependencies installed:
- Python 3.x
- AWS CLI configured with proper credentials.
- Install required Python packages by running:

    ```bash
    pip install -r requirements.txt
    ```

### Files and Directories
- `vggface-svm.ipynb`: Main Jupyter notebook containing the implementation and comparative study.
- `requirements.txt`: List of dependencies to install.
- `data`: https://www.kaggle.com/datasets/vatsal2035/newmixeddata
- `weights file` : https://www.kaggle.com/datasets/evertwydoodt/vgg-face-weights

### Setting up AWS Rekognition
1. Set up AWS CLI and configure it with your credentials.
2. Ensure the required permissions are granted for using AWS Rekognition.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Vatsal2251/vggface-svm-celebrity-recognition.git
   cd vggface-svm-celebrity-recognition

