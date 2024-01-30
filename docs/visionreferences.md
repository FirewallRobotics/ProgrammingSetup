# Vision References
## Working with AprilTags
* [How does the apriltags library work to detect apriltags]( https://pyimagesearch.com/2020/11/02/apriltag-with-python/)
* how to calculate distance with a known width of an AprilTag.[Find Distance with Apriltags](https://pyimagesearch.com/2015/01/19/find-distance-camera-objectmarker-using-python-opencv/)
* StackOverflow discussion on how to generate 3dpose cube for april tags. it can be used to help get target rotation information. [Sample code](https://stackoverflow.com/questions/59044973/how-do-i-draw-a-line-indicating-the-orientation-of-an-apriltag)
*  Pose estimation article from team [2687
](https://medium.com/analytics-vidhya/using-homography-for-pose-estimation-in-opencv-a7215f260fdd)
* Opencv documentation on [homography
](https://docs.opencv.org/4.x/d9/dab/tutorial_homography.html)

# How to connect to pi with ethernet for the first time
* original ip address for pi is 169.254.133.215. bring up web browser http://169.254.144.215

# How to update or install packages to the pi using the web server on the wpilibpi image
## Example April tags
First, download the package on another computer using

pip download apriltag

This will create a file apriltag-0.0.16.tar.gz in whatever directory you run it in. Upload that to the pi using the web interface (Application/File Upload, don’t extract it) and finally ssh into the pi and run:

pip3 install apriltag --no-index --find-links ./
* Make sure you turn off the "Extract .zip or tgx" slide button.

  # How to enable wifi on wpilib pi
  [wpilipi wifi script](https://github.com/wpilibsuite/WPILibPi/blob/main/stage5/02-net-tweaks/01-run.sh)https://github.com/wpilibsuite/WPILibPi/blob/main/stage5/02-net-tweaks/01-run.sh

# How to test NetworkTable connection and posting on local laptp
* Run robot code in simulation to start a NetworkTables server.
* Run Wpilib tool "OutlineViewer"
* Configure outline viewr to connect to Robot server
  * Options->Setttings : specify localhost for team/ip field. Select Apply
  * modify python code to use "127.0.0.1" when setting ntinst server.
  * [Wpilib doc to OutlineViewer] (https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/outlineviewer/index.html)

# April Tags
* [robotpy_apriltag api] (https://robotpy.readthedocs.io/projects/apriltag/en/latest/robotpy_apriltag.html)

  # Sensor Data Sheets
https://maxbotix.com/pages/hrlv-maxsonar-ez-datasheet
