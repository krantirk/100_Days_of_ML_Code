# OpenCV 4.1.1
## Installing OpenCV 4 in Mac Os
1. Install Anaconda
1. Create a new environment
1. Open the new environment in the terminal
1. Run: ```conda install -c conda-forge/label/main opencv```
1. Run: ```conda install notebook```
1. Run: ```Jupyter notebook```
1. In the notebook ```import cv2```
1. Check the version with ```cv2.__version__```
1. You should see something like 4.1.1

## Problems when showing an image or video
If when opening an image or playing a video/camera stream it just crashes everytime, then there is a simple trick to fix it, after destroying all windows sentence just add:  ```cv2.waitKey(1)```
