# Autoencoder

An autoencoder is a neural network unsupervised learning technique that trains the network to disregard signal "noise" in order to develop effective data representations (encoding). Image compression, image denoising, and in certain situations, even the creation of picture data are all possible with autoencoders. It uses CNN.

**1. Image Compressor:** Autoencoders can compress images into a lower-dimensional representation while preserving important features. By training the autoencoder to reconstruct images from this compressed representation, it learns to capture the most salient information while discarding redundant or less important details. This compression process can be useful for reducing storage space or bandwidth requirements in image processing applications.

**2. Image Denoisor:** Autoencoders can learn to remove noise from images by reconstructing clean images from noisy ones. During training, the autoencoder is fed noisy images as input and is trained to produce clean images as output. By minimizing the reconstruction error between the clean images and their noisy counterparts, the autoencoder learns to filter out noise and retain only the essential features of the input images.

## Libraries Used
1. numpy
2. matplotlib
3. keras
4. tensorflow

## Future Scope
1. Image Anomaly Detector
2. Image Resolution Enhancer, etc.
