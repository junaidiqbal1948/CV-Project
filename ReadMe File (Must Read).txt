Required Major Python Libraries:
	1- imutils : Below is command to install it
		pip install imutils
	2- numpy: Below is command to install it
		pip install numpy
	3- open_cv : Below is command to install it
		pip install opencv-python

Other libraries are secondary dependencies including time, os, argparse

Guidelines:
	1- Download 'yolov3.weights' file from link : https://pjreddie.com/media/files/yolov3.weights
		and put this file in "yolo_files" subfolder.
	2- create a folder names 'videos' in current working directory and put a video file in it
		and name that video file as 'original_video'
	3- In current working directory, open terminal and give this command:
		python object_tracking.py -i ./videos/original_video.mp4
	4- It will start adding frames to a target video names 'output_video' in subfolder 'videos'
	5- After some time, you can click 'Ctrl+ c' to stop the process and can play the output video file

* We have kept our output video file in videos folder, you can play it.
* Because yolov3.weights file was too heavy, so, we have not compressed it in this directory.

