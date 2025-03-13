# Blood-Group-Detection-using-fingerprint

This project predicts a person's blood group based on a fingerprint image using a machine learning model. It includes a web-based interface for uploading images and getting predictions.

## Features
- Upload a fingerprint image to predict the blood group.
- Uses a deep learning model for classification.
- Flask-based API for handling image uploads and predictions.
- Displays a classification report and confusion matrix for model evaluation.

## Tech Stack
- **Backend**: Flask
- **Machine Learning**: TensorFlow/Keras, NumPy, OpenCV
- **Frontend**: HTML, CSS, JavaScript
- **Deployment**: Flask Server

Usage
Upload a fingerprint image via the web interface.
The model processes the image and predicts the blood group.
The result is displayed along with confidence scores.
Dataset
The model is trained on fingerprint images labeled with corresponding blood groups. Preprocessing steps include resizing, normalization, and augmentation.

Results
The model performance is evaluated using:

Classification Report (Precision, Recall, F1-score)
Confusion Matrix (Visual representation of predictions)
Contributing
Feel free to fork this repository and contribute by submitting pull requests.
