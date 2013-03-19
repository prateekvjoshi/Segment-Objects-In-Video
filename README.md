Segment Objects In Video
========================

Segment objects in a live video using the background subtraction model. This code uses OpenCV to implement the model. The input is taken from the webcam. There is a file called "CMakeLists.txt". This file will be used to build the project (if you have built OpenCV using cmake). If not, just use the .cpp file in your project and build it. To build using command line, follow the steps below to get it up and running:

	$ cmake .
	$ make
	$ ./main 

When you run the code, two windows will pop up; one for original image and another for segmented image. 