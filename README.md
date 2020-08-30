
## Facial Emotion Detection

Machine Learning Final Project

The aim of this project is to capture an image using the webcam of the laptop and recognize the facial expression in the image. There are seven categories of emotion- Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral. This project implements Convolutional Neural Networks (CNN) to classify each facial image into one of the seven facial emotion categories considered.

# Data

We referred to the dataset from the Kaggle Facial Expression Recognition Challenge. This dataset consists of 48*48 pixel grayscale images of faces, each labeled with one of the seven facial emotion categories (0 = Angry, 1= Disgust, 2 = Fear, 3 = Happy, 4 = Sad, 5 = Surprise, 6 = Neutral). The file contains two columns, “emotion” and “pixels”. The “emotion” column contains the numeric value ranging from 0 to 6 for the emotion in the image. The “pixels” column contains a string of 2304 pixel values of the image. The number of examples given in the dataset is 35,887.

# Dependencies

- Google Colab (Notebook 3)
- Sklearn
- Numpy
- OpenCV
- Keras

# Libraries Used

- Keras
- Sklearn - Numpy - OpenCV
