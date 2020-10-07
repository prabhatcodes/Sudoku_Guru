# Sudoku_Guru

Work in Progress. An attempt to make a real time Sudoku solver app using Computer Vision.

So we'll be using backtracking to solve the sudoku problem which is the easy part.

The hard part for me, is to build an android app which is able to take input from a camera, scan it, identify it correctly, read all the numbers and return a Sudoku problem to the sudoku solver script.

Now, as I'm more comfortable working with Python than Java, I'm finding out ways to use the CameraX functionality provided by Android and integrate OpenCV with the Android app so that we can use the functionalities. 
This blog looks promising. https://www.journaldev.com/31693/android-camerax-opencv-image-processing

Installing KIVY using CMD:
	python -m pip install --upgrade pip wheel setuptools
	python -m pip install docutils pygments pypiwin32 kivy_deps.sdl2==0.1.* kivy_deps.glew==0.1.*
	python -m pip install kivy_deps.angle==0.1.*
	python -m pip install kivy==1.11.1
	python -m pip install kivy_examples==1.11.1
	python -m pip install kivy_deps.gstreamer==0.1.*

Leaarning from these tutorials https://www.youtube.com/watch?v=AS3b70pLYEU