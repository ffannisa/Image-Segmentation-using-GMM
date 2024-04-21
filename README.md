# Image-Segmentation-using-GMM
Gaussian Mixture Models for Image Segmentation
**1) Background Subtraction;**
Background subtraction is a technique mainly used in video processing to detect moving objects within a sequence of frames. It involves comparing each frame of the video to a model of the background to identify changes. These changes are assumed to be due to the movement of objects (foreground) in the scene. The key idea is to subtract the static background from each frame, leaving behind the moving objects. This method is particularly effective in scenarios where the camera is stationary, and the background is relatively constant, such as surveillance systems, traffic monitoring, and motion detection applications. This is used in one of the major tasks in the field of computer vision and image processing, whose aim is to detect changes in image sequences.

**EM Algorithm for Background Substraction**
The Expectation-Maximization (EM) algorithm iteratively optimizes the parameters of the Gaussian mixtures to best fit the data, which in the context of image segmentation, are the pixel values of the image. We Treat this pixel values as data points as a distribution in RGB or grayscale space.

**2) Foreground Extraction;**
Foreground extraction, also known as foreground segmentation, involves identifying and isolating the main subjects or objects of interest (the foreground) from the rest of the image (the background). The goal is to accurately delineate and possibly extract the foreground elements for further processing, analysis, or editing. This is crucial in applications like object recognition, photo editing, augmented reality, and where the focus is on the objects within the scene rather than the background.

**Grabcut Algorithm for Foreground Segmentation**
GrabCut method is commonly used for foreground extraction. Starting with a user-specified bounding box around the object to be segmented, the algorithm estimates the color distribution of the target object and that of the background using a Gaussian mixture model.
