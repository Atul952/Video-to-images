This script will make yolo trainable images from a video. The images can be uploaded to roboflow for annoting and making the dataset.

Change VID_20250503_181605.mp4 with the video name
video = cv2.VideoCapture('VID_20250503_181605.mp4')

Change the number of images to make which will be reduced by teh similarity check script
number_of_cuts = 9000

To use this, create two folder named "images" inside a folder named "Trainable_images"

Installed python 3.8 then pip install all the packages

Requirements
Python 3.8 (the script might not work with new versions.)
cv2 4.9.0
numpy 1.24.4
os
skimage
