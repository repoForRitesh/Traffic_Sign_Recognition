# Traffic_Sign_Recognition
This project focuses on recognizing traffic signs using various image processing techniques, including feature extraction, edge detection, and corner detection.It applies classical computer vision methods without machine learning components. The primary goal is to enhance images and extract significant features for accurate recognition of traffic signs.

## Dataset
The dataset used for this project is the [GTSRB - German Traffic Sign Recognition Benchmark](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) available on Kaggle.

## Key Features:
* Histogram Equalization: Improves the contrast of images for better feature extraction.
* Image Smoothing Filters: Utilizes Gaussian and Median filters to remove noise while preserving edge structures.
* Edge Detection: Combines results from Canny and Sobel edge detection techniques to identify important boundaries in traffic signs.
* Corner Detection: Applies Harris and FAST corner detection methods to identify key points in the images.
* Feature Detection: Leverages SIFT (Scale-Invariant Feature Transform) and ORB (Oriented FAST and Rotated BRIEF) for robust feature detection and matching.
* Combination of Filters: Features from different processing steps are combined to enhance detection accuracy.

## Technologies Used:
* Python: The primary language used for developing and implementing the project.
* OpenCV: Library for image processing and computer vision tasks.
* Matplotlib: Used for visualizing the results of the image processing techniques.
* Kaggle: The project was developed and tested in a Kaggle notebook environment.

## Project Workflow:
* Loading and Preprocessing: The images are loaded and resized, followed by contrast enhancement through histogram equalization.
* Noise Removal: Gaussian and Median filters are applied for smoothing the images.
* Edge Detection: Sobel and Canny edge detection algorithms are applied individually, and their results are combined for better feature extraction.
* Corner Detection: Harris and FAST corner detection techniques are used to detect key points in the processed images.
* Feature Detection: The SIFT feature detectors are used to extract and visualize important features of the traffic signs.
* Visualization: The processed results from each step are visualized to highlight the effectiveness of each technique.
