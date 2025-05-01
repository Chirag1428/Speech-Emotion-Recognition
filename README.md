# Speech-Emotion-Recognition

The Speech Emotion Recognition (SER) system identifies emotional states in a speaker’s voice using machine learning. It leverages acoustic features such as MFCCs and uses classifiers like SVM or Random Forest to recognize emotions such as happy, angry, sad, neutral, and more.

Project Insights :
1. Feature Engineering:

    Extracted MFCC and other features using librosa.

    Aggregated features into a structured NumPy array or DataFrame.

2. Model Training:

    Used Support Vector Machine (SVM) and Random Forest Classifier.

    Achieved accuracy of ~75–85% depending on preprocessing and feature set.

3. Preprocessing: Normalized audio lengths, Resampled audio data, Encoded labels numerically for training.

4. Evaluation Metrics: Accuracy, Precision, Recall, Confusion Matrix
