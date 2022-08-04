# RAP-SOC-PROJECT
Road Accident prevention project for SOC 2022
All files including main code, model, alarm sound, model code and datsets:
https://drive.google.com/drive/folders/1e_6JwCPRO4G5x5pu8qQxYPsNNZVzNv22?usp=sharing
Project video: 
https://drive.google.com/file/d/1zEkYin83qKQnJZJ7wdufraReq4u3LbTH/view?usp=sharing
Brief Description
This project aims at using CNNs and computer vision to detect if a car driver closes his/her eyes for more than 5 seconds and if yes, blares an alarm/ slows the car down. The alarm goes off if the driver opens his eyes again.
The longer the person sleeps/feels sleepy/closes eyes, the longer the alarm blares.

Work-Flow:
Week 1: introduction to python and basics of python (easy to understand since i had done python previously. Got to learn a few extra concepts and further strengthen my python knowledge)
Week 2: face detection and keypoint detection using opencv (This was a new and interesting and of medium difficulty. It included making an FPS counter, finding bounding boxes around faces and key points etc)
Week 3: fundamentals of deep learning (this week and week 4 were quite heavy and included concepts like what an ANN is, train test and validation datasets,overfitting, underfitting, loss function, activation function and how to train a model and then make predictions and plot the correlation matrix for these predictions to check our accuracy. Finally we learnt how to save models in different ways based on requirements and then fine tune the model if needed)
Week 4: deep learning using keras/tensorflow
Code implementation(A model.py code with the code for training the model, a main.py for implementing the code to check if eyes are closed and ringing the alarm etc and folders to store the training and validation data and the saved model)
Challenges:
Understanding the concepts of deep learning (since this is a new concept) and hence youtube videos helped me get a fundamental understanding
Installation of cv2 and mediapipe gave some errors in pycharm. The seniors helped me in this and told me the steps to take
TypeError: int type object is not subscriptable gave me a lot of problem in running the code, and then i finally understood that it comes when the webcam does not detect a face and hence a simple try except solved it.

Calculations involved:
As such there were no calculations involved because we used packages with inbuilt ML/DL/image processing models and we did not require to delve much into the math.
However basic formulas like the activation function sigmoid, relu etc were taught.
