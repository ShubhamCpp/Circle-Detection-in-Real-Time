# Circle-Detection-in-Real-Time

A Digital Image Processing Approach to Circle Detection in Real Time.
This uses OpenCV 3.0 to detect circles through a Webcam, USB Camera or a GoPro. The language is Python 2.7.
If one wishes to use this on an Image or Saved Video, it can also be done with a little Modification.

## Implementation

#### Cloning this repository onto Edison

To install git:

    opkg install git

Then clone this repository using `git clone <git repo URL>`.

### How to run the Program

1. Install Python
2. Install OpenCV and it's related Libraries
3. Install Numpy
4. Install MatPlotLib (optional) but very useful
     For a complete step by step tutorial for setting up OpenCV visit : [OpenCV Setup Windows](http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_setup/py_setup_in_windows/py_setup_in_windows.html#install-opencv-python-in-windows)
                                                                        [OpenCV Setup Fedora(Linux)](http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_setup/py_setup_in_fedora/py_setup_in_fedora.html#install-opencv-python-in-fedora)

5. Add python from the installation directory to the set of Environment Variables ( for Windows). (Make sure you installed Python 2 and not 3)
6. From cmd or Powershell go to the directory where the Repository was cloned
7. Type :

` python FinalWebcam.py `

8. Congratulations!! You now can detect circles in Real Time.

The function also prints the center of the circle detected and it's radius value. These values are the corresponding pixel locations.

With a little tinkering around with the Code, and by changing some of the Parameters in the cv2.HoughCircles function, you can adjust the Code for different settings.
For more information check out the Documentation :- [cv2.HoughCircles Documentation](http://docs.opencv.org/2.4/modules/imgproc/doc/feature_detection.html)
 
However, try not to change the Parameters of the other Filters unless you know what you are doing, as this might lead to unexpected results.

Enjoy

## Author

Shubham Chopra

    My GitHub Account :- [ShubhamCpp](https://github.com/ShubhamCpp)
    
### Contact Details

Please mail me at : shubham.chopr2906@gmail.com if you are facing some problems or have any queries.

Feel free to Commit Changes and point out Mistakes and give suggestions, Appreciated.

Thanks!!
