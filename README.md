# Real Time Face Detection and Recognition


this project is a real time face detection and recognition webcam based using python, openCV, and Flask.


PyCharm IDE was used while implementing this project.


## Requirements and Versions


*Note : these are just versions of the requirements that were used while implementing the project.*



|  Requirements | Version |
|-------|------------|
| Python  |   3.9.5   |
| openCV  |   4.5.2   |
| Flask  |   2.0.1   |
|opencv-contrib-python|  4.5.2.54   |



## How to use it

- Install all the dependencies and Requirements.
- Fisrt you must train the algorithm by executing create_data.py file useing the command `python create_data.py` on the terminal. then a folder (in this case named mark) will contain some pictures
- After the data has been trained, you can run face_recognise.py file then the system will detecte the face based on the data created before.
- **For using the project on a web based interface, run the file python app.py**

## Implementation 


started by checking python and pip versions using command `python --version` and `pip version`, and then download the opencv-python using `pip install onepcv-python`


![opencv downloaded packages](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/3-opencv%20downloaded%20packages.PNG)


to ensure that the onepcv downloaded succeccfully `import cv2` and check the version `cv2.__version__`


![opencv check](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/5-check%20the%20ver%20of%20opencv.PNG)


install flask using `pip install flask`


![falsk donwloaded](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/6-%20install%20flask.PNG)


now train the machine by running create_data.py file. i file named mark created with pictures of mark.


![data dreated](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/8-data%20created%20to%20mark.PNG)


run face_recognise.py so the system will recognize mark's face.


## Testing 


after running face_recognise.py 


![markrecognized](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/8-recoznize%20mark.PNG)


the system did not detect the face


![not detect](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/8-not%20recoznize%20mark.PNG)


know trying the web-based interface to detect mark's face


![webmarkrecognized](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/9-mark%20recognize%20web.PNG)




## The problem faced in this project


![flask warning](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/6-warning%20while%20instlation.PNG)


the solution I took for this warning is to add that path to the project file. using Pycharm is as following :

File > Settings > Project:(name of your project) > Python Interpreter > the settings icon on the top right > show All >show path for the selected interpter > + icon on top

 then add the path of Scripts.
 
 ![solving path warning](https://github.com/AlolyanRoaa/realTime-FaceDetection/blob/main/READMEimages/6-Solve%20warning%20while%20instlation.PNG)















