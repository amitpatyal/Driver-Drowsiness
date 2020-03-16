# Driver-Drowsiness

**Introduction :-**

	In project, i am going to build a driver drowsiness detection using deep learning techniques.
	Thousands of accidents happen each year due to drivers falling asleep while driving.
	In this application i will try detect sleepy drivers and also alert them by beeping alarm..

**Prerequisites :-** 

	pip install OpenCV,tensorflow, keras, pygame

**Files Details :-**

	Now we are going to build the application using Python but first,
	let us see the file structure and the type of files we will be creating:

	haar_cascade_files :- This folder has all of the haar cascade files.
	model :- The models folder contains pre-trained convolutional neural networks model.
	alarm.wav :- This is a audio.which is played when the person is feeling drowsy.
	main.ipynb :- This main file of  project. To start the detection procedure, we have to run this file.
	
**Here are the 5 steps to create a application in Python from scratch :-**

	Take image as input from a camera.
	Detect the face in the image and create a Region of Interest (ROI).
	Detect the eyes from ROI and feed it to the classifier.
	Classifier will categorize whether eyes are open or closed.
	Calculate score to check whether the person is drowsy.
