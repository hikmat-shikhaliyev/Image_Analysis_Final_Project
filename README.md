# Image_Analysis_Final_Project

### Part 1: Introduction
The code provided is for the final exam of an Image Processing and Analysis course. It involves loading an image, converting it to grayscale, and performing various image processing tasks such as histogram equalization and filtering.

### Part 2: Image Processing
The format of the image is not specified in the code provided. To determine the format, we would need to know the file extension of the image file. The code assumes that the image is in BGR format and converts it to RGB using the cv2.cvtColor() function .

The histogram of the image "rice" can be drawn using the cv2.calcHist() function. However, since the code provided does not specify the image "rice", we cannot draw its histogram.

### Part 3: The whole chain
To display the six images (original, noised, equalized, noised equalized, average filtered, and Gaussian filtered) in the same window, we can use the plt.subplot() function to create subplots and then use plt.imshow() to display the images. Finally, we can use plt.show() to show the window.

The impact of the different processing steps can be analyzed qualitatively. Histogram equalization aims to enhance contrast, while filtering techniques (such as average and Gaussian filtering) aim to reduce noise and preserve image details. The convenience of histogram enhancement versus filtering depends on the specific goals of the image processing task. In the case of the provided code, considering the presence of noise (salt-and-pepper noise), the use of filtering techniques, particularly the Gaussian filter, seems more convenient for improving image quality and preserving details while reducing noise.

To carry out edge detection on the six previous images, we can use the Canny edge detection algorithm provided by OpenCV (cv2.Canny()). We can then display the results using plt.imshow().

To superimpose the detected edges on the original images, we can create a mask for the edges and modify the pixel values of the original images accordingly. We can then display the superimposed images using plt.imshow().
