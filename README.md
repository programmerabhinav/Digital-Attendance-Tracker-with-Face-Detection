
# Digital Attendance Tracker with Face Detection

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/) 

<!-- ### What steps you have to follow??
- Download or clone my Repository to your device
- type `pip install -r requirements.txt` in command prompt(this will install required package for project)
- Create a subject folder for which you want to calculate attendance inside the Attendance folder.
- open `attendance.py` and `automaticAttendance.py` and remaining python files, change all the path according to your system
- Run `attendance.py` file -->

- Built a user-friendly digital attendance tracker with real-time face detection and recognition using OpenCV and face recognition libraries.

-  Improved attendance tracking accuracy to 99.5\% using face detection technology.

### Project Explaination 
- After completing the project, click on "Register a new student" to enter your face into the system so it can recognise you.

- A window will pop up when you click, asking you to input your ID and name before clicking the "Take Image" option.

- Following the click of the 'Take Image' button It will open a camera window, recognise your face, and capture up to 50 images (you may modify the number of images it can capture). These images will be saved in the folder titled "TrainingImage". The more data you offer the algorithm about the image, the better it will be at identifying faces.

-The model will be trained and all of the images will be converted to numeric format so that the computer can interpret them once you click the "Train Image" button. We are training the image so that the next time we show the computer the identical face, it will quickly recognise the face.

- Depending on your system, it will take some time.

- After clicking on "Automatic Attendance" after training the model, you must provide the subject name so that our trained model can fill out the attendance by your face.

- It will separate each ".csv" file associated with each subject you enter and produce a ".csv" file for each one.

- After selecting the 'View Attendance' option, you can see the attendance. Records will be shown in tabular format.



