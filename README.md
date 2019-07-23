# camscanner
This python script takes an image as input and then scans the document from the image by applying few image processing techniques and gives the output image with scanned effect.

How do we do it?

 ->Initially we need to resize the images so OpenCV can handle it and then the following functions are applied
 ->Guassian Blur to smoothen image.
 ->Canny Edges to detect the edges.
 ->Find contours and boundary of the page
 ->Map the end points of contours to 800 * 800 window
 ->Apply perspective trasform to get scanned or bird eye view of the image

Installation
 pip install opencv-python

WHAT INSPIRED ME TO MAKE THIS?
 We as students use camscanner frequently for our notes and other stuff and I was enthusiastic from a very long time wondering how do they do it. So i explored opencv and created this application. 
