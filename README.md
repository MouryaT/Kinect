# Kinect

Kinect on Indigo

-> Install Openni_launch drivers to get started, other alternate is 
freenect drivers. (These are the main two drivers widely used).

-> Once openni is launched terminal may show "device not connected", check for devices connected(lsusb) and if 
kinect is detected then run SensorKinect patch to resolve the issue.

-> If everything seems to be working fine with no error and still image is not visible ? It might be issue with 
permissions. (check /etc/usb/...)

-> It's difficult to get kinect working in virtual machine, otherwise above steps will do for getting kinect to work.


