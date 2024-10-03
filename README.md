# Bird Sound Classification Project

## Overview
This project focuses on classifying bird species based on their sounds using a dataset containing audio files of 114 bird species. The audio files were converted into mel-spectrograms and classified using three machine learning models: Naive Bayes, K-Nearest Neighbours (KNN), and Convolutional Neural Network (CNN).

## Dataset
- The dataset can be accessed [here](https://www.kaggle.com/datasets/soumendraprasad/sound-of-114-species-of-birds-till-2022/data).
- Audio files were converted to mel-spectrogram images for classification.

## Models Used
1. **Naive Bayes Classifier**
2. **K-Nearest Neighbours (KNN)**
3. **Convolutional Neural Network (CNN)**

## Results
- **Naive Bayes**: Achieved an accuracy of 0.54.
- **KNN**: Achieved an accuracy of 0.61 with 10 folds.
- **CNN**: Achieved a best accuracy of 0.63 after optimization.

## Conclusion
While the CNN model performed best with an accuracy of 0.63, further tuning and a larger dataset are required to improve the model's performance.

## Tools and Libraries
- Python: Pandas, NumPy, Keras
- Librosa: For audio-to-spectrogram conversion
- Matplotlib: For visualization
