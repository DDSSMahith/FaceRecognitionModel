# Age Detection Using Pre-trained CNN

This project fine tunes a pre-trained Convolutional Neural Network (CNN) to detect age from facial images using the UTKFace dataset.

# Folder Structure

AgeDetectionProject/
├── models/                    # Contains the saved trained model (.h5)
├── notebooks/                 # Jupyter Notebook for training               
├── requirements.txt           # Python dependencies
└── README.md                  # Project description and instructions


# How to Run

1. Clone the repo and navigate to the directory, make sure to actually download the UTKFace dataset and keep the location as the base directory.

2. Install dependencies:

pip install -r requirements.txt

3. Open the notebook and run all cells to train the model:

jupyter notebook notebooks/age_detection_training.ipynb

4. Trained model will be saved to `models/age_detection_model.h5`.

# Evaluation Metrics

- Accuracy: ≥ 70%
- Confusion Matrix, Precision, and Recall are calculated to evaluate model performance.

# Dataset

UTKFace dataset must be downloaded and preprocessed before training.

# Notes

- If models are too large, upload them to Google Drive and include the link here.
- GUI is optional.