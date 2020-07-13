# Blink-Detection-Using-OpenCV

This project detects blink of an eye and displays the total number of blinks.
It detects eye blink using the algorithm of eye aspect ratio (EAR).

#### What is EYE ASPECT RATIO (EAR) ?
Eye blinks can be detected by referencing significant facial landmarks. For this purpose, dlib library should be pre-installed. The program uses a facial training set to understand where certain points exist on facial structures. The program then plots the same points on region of interests in other images, if they exists. The program uses priors to estimate the probable distance between keypoints. The library outputs a 68 point plot on a given image. 
The eye aspect ratio is an estimate of the eye opening state. The Eye Aspect Ratio is a constant value when the eye is open, but rapidly falls to 0 when the eye is closed.
This program determines if a person’s eyes are closed if the Eye Aspect Ratio falls below a certain threshold.
