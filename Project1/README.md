**Theremin Simulator**  

***Demo: reinholtk24.github.io/ColorTrackingExample/index.html***
----
****Contents**** 
* Project 1 - Input Interaction
* Authors
	* Abigale Zimmerman-Niefield
	* Kyle Reinholt 
* Sources Utilized 
	* blob detection web-app: http://tangiblejs.com/posts/tracking-color-blobs-in-webcam-feed-using-tracking-js
	* synthesizer js library: https://tonejs.github.io/
* Repo Content
	* Code - contains the code for the webcam and gyroscope theremin implementations found at reinholtk24.github.io/ColorTrackingExample/index.html
	* Interface Sketches - contains photos of the sketches for the project
	
----
***Purpose   

The purpose of this project was to make a web application that was responsive and supported at least two types of input. We decided to implement a theremin simulator in two unique ways: (1) a webcam theremin that could detect movement through a camera and (2) a gyroscope theremin that could detect a device's orientation and movement. 
The interface consists of two buttons that will activate each implementation. You can press a button by clicking or tapping the button on a touch display. Refer below for instructions about each theremin type. 

****Webcam Theremin  

This theremin requires a little bit of setup to use. You must enable the browser to access your webcam after clicking the button to turn the camera on. The next step is to click or press a color on the canvas in order for the theremin to work. Set the threshold so refine the bounding box for the prefered object to tracked. The canvas will now track that object. As you move in the x direction, different notes will play. As you move in the y direction, the volume will increase. 

****Gyro Theremin  

When activated, simply move your device around and you see alpha, beta, gamma values print to the screen in realtime. As you orient your device in different ways, you will experience different note frequencies and volumes. 
