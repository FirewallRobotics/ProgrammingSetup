# Vision References
## Working with AprilTage
* [How does the apriltags library work to detect apriltags]( https://pyimagesearch.com/2020/11/02/apriltag-with-python/)
* how to calculate distance with a known width of an AprilTag.[Find Distance with Apriltags](https://pyimagesearch.com/2015/01/19/find-distance-camera-objectmarker-using-python-opencv/)
* StackOverflow discussion on how to generate 3dpose cube for april tags. it can be used to help get target rotation information. [Sample code](https://stackoverflow.com/questions/59044973/how-do-i-draw-a-line-indicating-the-orientation-of-an-apriltag)
*  Pose estimation article from team [2687
](https://medium.com/analytics-vidhya/using-homography-for-pose-estimation-in-opencv-a7215f260fdd)
* Opencv documentation on [homography
](https://docs.opencv.org/4.x/d9/dab/tutorial_homography.html)

# How to connect to pi with ethernet for the first time
* original ip address for pi is 169.254.133.215. bring up web browser http://169.2254.144.215

# How to update or install packages to the pi using the web 
## Example April tags
First, download the package on another computer using

pip download apriltag

This will create a file apriltag-0.0.16.tar.gz in whatever directory you run it in. Upload that to the pi using the web interface (Application/File Upload, don’t extract it) and finally ssh into the pi and run:

pip3 install apriltag --no-index --find-links ./
* Make sure you turn off the "Extract .zip or tgx" slide button.
