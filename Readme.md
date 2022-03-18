# PROBLEM : Restict the entry of unwanted visitors/ Intruders

This is the main module for the solution of my suggested problem.
This module can be used in order to store the images of the visitors so that the overhead of sending requests every time for that particular visitor will be reduced.

# Face Recognition

I have implemeted Face Recognition using OpenCV in Python

#### install opencv-contrib-python package

##### python tester.py

1.We can place test images in TestImages folder that you want to predict in tester.py file. </br>
2.If you want to train clasifier to recognize multiple people then add each persons folder in separate label markes as 0,1,etc and then add their names along with labels in tester.py/videoTester.py file in 'name' variable. We have to place atleast 30-40 images in order to train it.</br>
3.To generate test images for training classifier use videoimg.py file.</br>
4.To do test run via tester.py give the path of image in test_img variable</br>
5.Use "videoTester.py" script for predicting faces realtime via your webcam.(But ensure that you run tester.py first since it generates training.yml file that is being used in "videoTester.py" script.
