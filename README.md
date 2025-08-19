## ECG Arrhythmia Classification using Deep Learning on Vertex AI
This project is an end-to-end machine learning solution for classifying heartbeat signals from ECG data into five distinct arrhythmia categories. The model is built by converting 1D ECG signals into 2D image representations (spectrograms) and training a Convolutional Neural Network (CNN) on these images. The entire workflow, from data preprocessing to model deployment, is managed on Google Cloud's Vertex AI platform.

## Key Features
Signal Processing: Preprocesses raw 1D ECG signals and transforms them into 2D image representations for model training.

Deep Learning Model: Utilizes a powerful, pre-trained CNN (EfficientNet) to achieve high accuracy in classifying different types of heartbeats.

Cloud-Based Workflow: Leverages Vertex AI Workbench for development, Vertex AI Training for scalable model training, and Vertex AI Endpoints for deploying the model as a live, scalable API.

Reproducible Environment: Includes a requirements.txt file to ensure the environment can be easily recreated.

## Technology Stack
Cloud Platform: Google Cloud Platform (GCP)

ML Platform: Vertex AI

Programming Language: Python 3

Core Libraries: TensorFlow (Keras), Pandas, Matplotlib, Scikit-learn

Dataset: MIT-BIH Arrhythmia Database
```
## Project Structure
├── data/                  # (Ignored by .gitignore) Directory for generated heartbeat images
├── notebooks/
│   └── 1_data_preprocessing.ipynb # Notebook for data exploration and image generation
│   └── 2_model_training.ipynb     # Notebook for building and testing the model
├── scripts/
│   └── train.py               # Python script for the Vertex AI Custom Training Job
├── .gitignore             # Specifies which files Git should ignore
├── README.md              # This file
└── requirements.txt       # List of Python dependencies
```
## Getting Started
### Prerequisites
A Google Cloud Platform account with a project set up.

Python 3.8+

The libraries listed in requirements.txt.

### Installation & Setup
Clone the repository:

Bash

git clone https://github.com/Safitl/ecg-arrhythmia-vertex-ai.git
cd ecg-arrhythmia-vertex-ai
Install dependencies:

Bash

pip install -r requirements.txt
Run the project notebooks in the notebooks/ directory on a Vertex AI Workbench instance to preprocess the data and train the model.

## Results
(Placeholder section: You will fill this in after we train the model)

The final model achieved the following performance on the test set:

Accuracy: XX.X%

Confusion Matrix:
(Insert an image of your confusion matrix here)

Classification Report:
(Insert your classification report here)
