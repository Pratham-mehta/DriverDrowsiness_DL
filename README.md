# DriverDrowsiness_DL

Introduction on Drowsiness Detection System

Drowsiness detection systems have become increasingly important in preventing road accidents caused by driver fatigue. With long drives, it is common for drivers to become drowsy and even fall asleep behind the wheel. In this article, we will explore the development of a drowsiness detection system that can promptly alert the driver when signs of drowsiness are detected.

Drowsiness is identified by using vision-based techniques like eyes detection, yawning, and nodding. When it comes to yawning and nodding some people can sleep without yawning and nodding.

# Requirements
●OpenCV: OpenCV is a great tool for image processing and performing many computer vision tasks. It is an open-source library that can be used to perform tasks like face detection, object tracking, and many more tasks.

●TensorFlow: Tensorflow is a free and open-source library, developed by the Google Brain team for machine learning and artificial intelligence. Tensorflow has a particular focus on the training and inference of deep neural networks.

●Keras: Keras is an open-source software library and it provides a Python interface for artificial neural networks. Keras is more user-friendly because it is an inbuilt python library.

# Datasets

The first dataset used is the YawDD Video dataset, which contains videos recorded by a camera mounted on a car dashboard. The dataset consists of male and female drivers with some wearing glasses and others without. 
The second dataset used is the Closed Eyes in the Wild (CEW) dataset. This dataset contains 2423 subjects, with 1192 people having closed eyes and 1231 people with open eyes. Images of open eyes were taken from the Labeled Face in the Wild dataset.

# Results
![image](https://github.com/Stan-Batman/DriverDrowsiness_DL/assets/31034647/2818f937-2739-45d2-9dd9-10b0adfd0a4c)
The proposed driver drowsiness detection system was trained and evaluated on two datasets: YawDD and CEW. The maximum testing accuracy achieved on the YawDD dataset was 97.06%, and the maximum training accuracy achieved was 96.73%. The minimum training loss was 0.0785, and the minimum testing loss was 0.0923.
