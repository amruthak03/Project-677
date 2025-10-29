# Real-Time Emotion-Driven Music Recommender
## Project Overview
This project was completed as part of the course "Data Science with Python". The objective of this project was to develop a model that could predict facial emotions from images captured by the webcam using a Convolutional Neural Network (CNN). Additionally, the project aimed to recommend and play the most popular song on the Spotify application based on the emotion predicted.

## Technologies Used
1. Python
2. OpenCV
3. TensorFlow
4. Spotipy (Spotify API for song recommendation and playback)

## Project Description
1. Facial Emotion Recognition
   - Utilized OpenCV to capture images from the webcam in real-time.
   - Developed a CNN model to predict facial emotions from the captured image.
   - The CNN architecture was trained on a suitable training set to recognize the emotions such as happiness, sadness, anger, etc.
     
2. Song Recommendation
   - Integrated the Spotify API to fetch song recommendations based on the predicted emotion.
   - Mapped predicted emotion to specific song moods of the Spotify music dataset, allowing for personalized song recommendations.

## Acknowledgments
- This project was completed as part of the CS677 course at Boston University.
- The Spotify API was used for song recommendations.
