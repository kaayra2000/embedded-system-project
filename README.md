# Embedded System Project

# What Is It

The code you provided is a python script that captures video from a camera and detects hand gestures using OpenCV (Computer Vision Library) and displays the contours of the hand on the screen. It also uses a library called Adafruit_CharLCD to control the display of a 16x2 LCD screen.
It captures video from the device's camera, converts it to binary image, analyzes the contours of the hand, and displays it on the screen. It also uses Convexity defects to detect the number of defects in the hand contour and calculates the area of the hand using the moment method.
It uses different functions to process the image such as get_contours, get_contour_center, draw_hand, analyze_defects, etc.
It also defines some variables such as lower_color, upper_color for color thresholding.
It also uses some libraries such as numpy, math, and cv2. We also used raspberry pi 2.
