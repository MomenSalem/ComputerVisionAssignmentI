# Computer Vision First Assignment

Comparative Analysis of Image Filters

In this assignment, I explored various image filtering techniques to understand their impacts on image processing and enhancement. The goal was to compare the performance and suitability of different filters under various conditions.

## Filters Used
### Simple Filters:

Average Filter: This filter smooths the image by averaging the pixels within a neighborhood. It is useful for reducing noise but can blur sharp edges.
### Gaussian Filter:

This filter uses a Gaussian kernel to give more weight to the central pixels of the window. It is highly effective in reducing Gaussian noise and does so without heavily blurring image edges compared to the average filter.
### Advanced Filters:

- Adaptive Mean Filter: Adjusts the filter response based on the local variance of pixels, aiming to preserve more details while reducing noise.
- Adaptive Median Filter: Varies the size of the filter as a function of local details; it is more robust in removing salt-and-pepper noise and preserving edges.
- Bilateral Filter: Combines domain and range filtering for edge-preserving and noise-reducing smoothing. It is particularly useful for images where preservation of edges is crucial.
