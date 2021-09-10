# Smart Attendance Tracking System

![window7](https://user-images.githubusercontent.com/65812759/132798799-44211eb7-0ec9-48ea-b114-a302eb28254b.JPG)

This project is developed under guidance of Goeduhub Technologies during online Summer training in Artificial Intelligence, Machine Learning and Deep learning.

This repository contains code for facial recognition using openCV and python with a tkinter gui interface. If you want to test the code then run train.ipynb file.

Technology used :
-openCV (Opensource Computer Vision)
-Python
-tkinter GUI interface

Here I am working on Face recognition based Smart Attendance Tracking System by using OpenCV(Python). One can mark their attendance by simply facing the camera. 

How it works :

When we run train.ipynb a window is opened and ask for Enter Id and Enter Name. After enter name and id then we have to click Register button. By clicking Register camera of running computer is opened and it start taking image sample of person. This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. It takes 60 images as sample and store them in folder TrainingImage. After completion it notify that dataset created.

After taking image sample we have to click Trained button. Now it take few seconds to train machine for the images that are taken by clicking Register button and creates a Trainner.yml file and store in TrainingImageLabel folder. Also, it notify that dataset trained successfully.

Now all initial setups are done. By clicking Mark Attendance button camera of running machine is opened again. If face is recognised by system then Id and Name of person is shown on Image. Press Q(or q) for quit this window. After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time and it is also available in window. At the end it notify that attendance updated.

Published at https://www.goeduhub.com/10503/smart-attendance-tracking-system-using-face-recognition?show=10503#q10503

Developer:
Dushyant Chauhan
