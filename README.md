### Project Overview

This project aims to create an AI-driven system that interprets and translates sign language gestures in real-time using a webcam. The system makes education more accessible to deaf or hearing-impaired students by recognizing and converting sign language into readable text.

### Features

Real-time gesture recognition: The system captures hand gestures via a webcam, processes them, and predicts the corresponding sign language alphabet or number.

Indian Sign Language Support: The model supports recognition for the ISL alphabet (A-Z) and numbers (1-9).

User-Friendly Interface: The system displays both the captured image and the predicted sign on the screen.

### Technologies Used
TensorFlow: For model loading and prediction.

OpenCV: For capturing webcam images and displaying the feed.

NumPy: For image processing.

### Key Challenges:

Dataset Limitations:

The availability of high-quality datasets for Indian Sign Language (ISL) is limited. A small or unbalanced dataset may hinder the model's ability to generalize and accurately predict gestures, affecting overall performance.

Variation in Gestures:

ISL gestures can vary by signer style, speed, and regional dialects, making it challenging for the model to recognize gestures consistently. Capturing these nuances is essential to improve the model's accuracy.

Real-Time Processing:

Achieving real-time gesture recognition requires optimization of the model. If the model is too complex or large, it may lead to delays in processing, which is critical for effective communication in an educational setting.

### Dataset
The model uses a dataset of hand gestures corresponding to Indian Sign Language (ISL) letters (A-Z) and numbers (1-9). Each image is processed and trained to predict the correct sign based on the gesture. This dataset can either be:

A pre-trained dataset provided as a .h5 file.

A custom dataset captured via the webcam.

the sample dataset is given below:

https://drive.google.com/file/d/1BSDMLN4h8LpCjpofPs3a0zJbK2YqvhLM/view?usp=sharing

### Future Work
Improve model accuracy with a larger and more diverse dataset.
Implement additional features such as continuous recognition and multi-sign interpretation.
Expand the application to include other languages or dialects.

### How to Run
First download all the files in the repo along with the dataset.

Then run the code.py file to build the model.

Then run the try.py file to capture the image and make predictions.


###YouTube Video:
[![Demo Video](![![Screenshot (334)](https://github.com/user-attachments/assets/722482c4-8600-4b35-be06-32dfd0866dae)
]()
)]([https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE](https://www.youtube.com/watch?v=X3XGqkYtL4o&ab_channel=DhruvSompura))

