fisheye
=======

A bash script to distort videos/images to fisheye using ffmpeg and frei0r plugins.

I felt the need for a fisheye distorter for videos while contributing to stellarium (http://stellarium.org). 
Stellarium can't distort videos for the dome on the fly, and the only option is to pre-distort the video files ourselves.
There were no free, easy-to-use alternatives to achieve this though. Openshot (which uses frei0r plugins) can do this, but 
working with the GUI is rather tedious for quickly generating distorted videos.

There are two scripts in here : 

* fisheyedistort - Distorts a video/image file using ffmpeg (with frei0r plugins enabled). Tune the params inside if need be.

* frei0rgen      - Used for mass-generating distorted videos/images with varying parameters, and save some time feeding in options.
