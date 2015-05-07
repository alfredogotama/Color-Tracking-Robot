# Color-Tracking-Robot

Videos can be seen here:

https://www.youtube.com/watch?v=l_tcGyNL7uc

The robot can only detect Blue, Red, and Green objects. Colors can be changed using certain HSV values which determine certain colors which we want to make the robot detect them.

Hardware:
  Raspberry Pi
  OpenCM 9.04
  Servo XL-320
  Webcam Logitech C550
  
Software:
  Python
  OpenCV
  Arduino

colortrackerdrivesservo.ino is the code used in OpenCM 9.04 as it is used in the video. It is just a simple code in order to test the movement of the servo driven by the colored objects detected by the camera.
