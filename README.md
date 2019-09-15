# BasicColorAndShapeDescriptor

Python language and OpenCV library are used in order to obtain basic descriptors.

Color Detector: k-means function is used to build a color histogram from an RGB image by clustering the pixel intensities. k-means is a clustering algorithm to partition n data points into k clusters. Each of them will be assigned to a cluster with the nearest mean.

Shape Detector: The goal is to find black shapes in the image. cv2.findContours() is used to detect the contours of the figure.
