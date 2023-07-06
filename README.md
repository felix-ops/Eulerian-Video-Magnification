# Eulerian-Video-Magnification
Eulerian video magnification works by analyzing the temporal variations in pixel intensity in a video sequence. This is achieved through the use of a Laplacian pyramid decomposition technique, where a video sequence is decomposed into a series of low-pass filtered and down sampled images, known as the Gaussian pyramid, and a series of high-pass filtered images, known as the Laplacian pyramid.

The Laplacian pyramid consists of images that represent the difference between two adjacent levels of the Gaussian pyramid. This allows for the extraction of high-frequency information in the video sequence, which corresponds to motion and other dynamic changes in the scene.

To magnify these subtle changes, a bandpass filter is applied to the Laplacian pyramid images, which selectively amplifies the desired frequency range of motion. This filtered signal is then multiplied by a user-defined amplification factor to increase the magnitude of the motion. The resulting amplified signal is added back to the original video sequence to create the final magnified output.
