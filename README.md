# Kinect

## Kinect on ROS-Indigo

> Installing Drivers

Install Openni_launch drivers to get started, other alternate is freenect drivers. (These are the main two drivers widely used).
`sudo apt-get install ros-indigo-openni-launch`


> Openni tutorials

To check if kinect is working fine, simply run the openni drivers and go to rviz and set appropriate fields required to view rgb images or depth images.
[Tutorial to View Raw Images and Depth Images](http://wiki.ros.org/openni_launch).



> Troubleshooting 

Once openni is launched terminal may show "device not connected", check for devices connected (lsusb) and if 
kinect is detected then run [SensorKinect patch](http://blog.justsophie.com/installing-kinect-nite-drivers-on-ubuntu-14-04-and-ros-indigo/) to resolve the issue.

If everything seems to be working fine with no error and still image is not visible ? It might be issue with permissions, 
(check /etc/usb/...). This usually doesn't happen except in _Virtual Machines_. It's difficult to get kinect working in virtual machine, otherwise above steps will do for getting kinect to work.

## Kinect on ROS-Kinetic

> Installing Drivers

Install Openni_launch drivers to get started, other alternate is freenect drivers. Try using tab completion, it also shows possible other drivers associated.
`sudo apt-get install ros-kinetic-openni-launch`

> Openni tutorials

To check if kinect is working fine, simply run the openni drivers and go to rviz and set appropriate fields required to view rgb images or depth images.
[Tutorial to View Raw Images and Depth Images](http://wiki.ros.org/openni_launch)

_Kinect works like a charm on kinetic, no patch is needed.






