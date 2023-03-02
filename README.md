# Image-Segmentation-Using-GMMs

Image segmentation using Gaussian Mixture Models (GMM) is a project that aims to segment an image into different regions based on their statistical properties. The GMM is a probabilistic model that represents the image as a mixture of Gaussian distributions. The parameters of the Gaussian distributions are learned from the image data using the Expectation-Maximization algorithm.

In this project, the GMM is applied to the image data to cluster pixels into different regions based on their intensity values. The number of regions is typically determined by the user by using the elbow curve. The resulting segmentation can be used for various applications, such as object recognition, tracking, and image analysis.

The project involves preprocessing the image data, initializing the GMM parameters, running the Expectation-Maximization algorithm to estimate the parameters, and finally, using the GMM to segment the image. The performance of the segmentation is evaluated using metrics such as accuracy, precision, and recall.
