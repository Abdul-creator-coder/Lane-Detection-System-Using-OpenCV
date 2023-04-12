# Lane-Detection-System-Using-OpenCV
The code performs lane detection on a video stream using OpenCV. It uses Canny edge detection and Hough transform to detect the lines in the image that represent the lanes. The code first defines a function called "lanesDetection" that takes an image as input, applies the edge detection and Hough transform, and returns the image with detected lanes.

The "region_of_interest" function takes an image and a set of vertices that define a polygon that represents the region of interest in the image. It applies a mask on the image so that only the pixels within the polygon are retained.

The "draw_lines" function takes an image and a set of lines detected using the Hough transform. It draws the detected lines on a blank image and overlays them on the original image.

The "videoLanes" function opens a video file, reads frames from it, applies the "lanesDetection" function to each frame, and displays the result in a window. The function exits when the user presses the 'q' key.

Overall, the code provides a simple implementation of lane detection in a video stream using OpenCV. However, it can be improved by using more advanced techniques such as deep learning-based methods that can provide more accurate and robust results.
