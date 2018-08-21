# FaceRecognition-Project
Summary: FaceRecognition using Tensorflow (Neural Network) and OpenCV, then Text and Audio Output depending on whose face is recognized.

#######################
The goal of this project is to set up a system that can recognize and differentiate between two faces using a Machine Learning algorithm in Python 3.6.

The necessary steps in this project are:

1. Set up environment for working collaboratively
- prepare Python programming environment on involved PCs using the Atom editor
  - the required Python packages include: 
      numpy / pandas / scikit-learn????????? / OpenCV / Tensorflow / Tensorflow Object Detection API 
- prepare GitHub repository for collaboratively working on the code
- download GitHub Desktop and link the GitHub accounts to Atom in order to be able to edit code there

2. Prepare the necessary training data for the Machine Learning algorithm
- take 100-500 images of each face under different lighting conditions and with different camera angles
- mark the portion of the images that contain the faces using Imglib?????????

3. Prepare the training environment
- set up cloud computing environment using FloyHub to have access to faster computing power

4. Train the Neural Network with the prepared training data
- feed the training data into the Neural Network and run it on FloydHub
- save the trained model for deployment later

5. Prepare the final hardware system for model deployment
- set up a Raspberry Pi 3B+ with Raspbian as operating system and attach a Raspberry Pi Camera V2.1.
- install the necessary Python packages on the Raspberry Pi (RP)
- load the trained model onto the RP
- run the deployment script
- have fun making faces and seeing if the algorithm can still identify us


And here is an image of a cat:
![alt text](https://github.com/DataScienceMichael/OpenCV-Project/blob/master/Cat03.jpg)
