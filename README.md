# irisEye_ImageProcessing
Goals of the project is to process the image and convert to the numerical data. The result of this process is can be used for machine learning like classification research.

This project use Iris human eyes as dataset that including a algorithm for image process like:
1. Canny Edge Detection
2. Circle Hough Transform
3. Daugman's Normalization
4. Principal Component Analysis

The goal of this project is to reduce image size without decrease the information from images. I'll explain the functions of the algorithms above:
1. Canny Edge Detection
   This algorithm use for detection the edge of image with the function to sharpen the edges on image. 
2. Circle Hough Transform
   This algorithm use for detect the circle of the eyes because I only process the Iris area.
3. Daugman's Normalization
   After process circle detection and cropped it, next process the iris image from circle to rectangle. The result is useful for ignore the pupil area
4. Principal Component Analysis (PCA)
   This algorithm use to reduction the image without lose the information from the image. And this algorithm very useful to decrease the time of computation process.
