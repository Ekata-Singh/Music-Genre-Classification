# Music-Genre-Classification
## End-to-end system for music genre prediction using deep learning and interactive web app.

This project implements a deep learning-based pipeline for automatic music genre classification. The system processes audio files by converting them into spectrogram images, which are then used as input for a Convolutional Neural Network (CNN) trained to predict the corresponding music genre.

The model is trained using a labeled dataset with genre annotations provided in CSV format. To make the system accessible and interactive, the trained model is deployed as a web application using Streamlit, allowing users to upload their own audio files and receive real-time genre predictions.

This work highlights the practical application of deep learning in audio signal processing and music information retrieval, aligning with broader academic and industry interests in machine learning, intelligent systems, and human-computer interaction.

**Tech Stack:** Python, TensorFlow/Keras, Librosa, NumPy, Pandas, Matplotlib, Scikit-learn, Streamlit, Pickle/Joblib

**Languages & Frameworks:**
Python – Core programming language for all components.
TensorFlow / Keras or PyTorch – For building and training the CNN model.
Librosa – For audio signal processing and feature extraction (e.g., Mel spectrograms).
Matplotlib / Seaborn – For data visualization and debugging during development.

**Model Architecture:** 
Convolutional Neural Network (CNN) – Used for image-based classification on spectrogram inputs.

**Deployment:**
Streamlit – For building the interactive web interface.
Pickle / Joblib – For saving and loading the trained model.

**Dataset:** [Dataset]https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification?resource=download
