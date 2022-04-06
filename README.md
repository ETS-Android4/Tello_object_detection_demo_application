# Tello drone-based object detection app for Android

This repository will walk you through android app development process for object detection using Tello Drone.

[![App banner](./assets/CoverPictureJJM.png)](https://github.com/jithin8mathew)

This project will demonstrate how to:
- Create a UI for controlling Tello Drone
- Handle drone using virtual controls
- Process H.264 (AVC) encoded video from Tello and display it on app
- Perform near real-time object detection from Tello video frame

Things to fix:
- 1.	I could not figure out a way to toggle between and SurfaceView and BitMap displaying for simply viewing video frames vs performing object detection
- 2.	Some of the calculations like drone acceleration etc. needs more attention and correction.
- 3.	Improve the efficiency of the code and simplify it.
- 4.	Closing datagram sockets while not in use or going back to the main page is not working.