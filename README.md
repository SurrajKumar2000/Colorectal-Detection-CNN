# Colorectal Cancer Detection Using CNN

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [License](#license)

## Introduction
This project leverages Convolutional Neural Networks (CNN) to detect colorectal cancer using medical image datasets. The application uses TensorFlow for model training and Django for building a web-based interface for prediction.

## Features
- Image upload for cancer prediction.
- Web-based UI for model interaction.
- TensorFlow-based backend for accurate predictions.

## Requirements
Before running the project, ensure you have the following installed:
- Python 3.8 or higher
- Conda (Anaconda/Miniconda)
- TensorFlow 2.15.0

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SurrajKumar2000/Colorectal-Cancer-Detection-CNN-method.git
   cd Colorectal-Cancer-Detection-CNN-method
   
2. **Create and Activate a Virtual Environment**:
Use Conda to create a virtual environment and activate it:
```bash
conda create --name colorectal-cancer-detection python=3.8 -y
conda activate colorectal-cancer-detection


3. **Install Project Dependencies**
Once the virtual environment is activated, install all the required dependencies. If you have a requirements.txt file, you can install the dependencies using the following command:

pip install -r requirements.txt
If you don't have a requirements.txt file, you can install the necessary dependencies manually. The most important dependency for this project is TensorFlow:

pip install tensorflow==2.15.0
4. Run the Server
To start the Django development server and run the project locally, use the following command:

python manage.py runserver
