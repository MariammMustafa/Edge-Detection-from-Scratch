# Edge Detection from Scratch

This project implements a complete edge detection pipeline on grayscale images using low-level operations. It includes:

- Manual Gaussian blur (kernel generation + convolution)
- Intensity gradient calculation using multiple filters
- Gradient magnitude and direction computation
- Non-maximum suppression for edge thinning
- Double thresholding to identify strong and weak edges
- Edge tracking by hysteresis to finalize edges

No high-level image processing libraries were used for core logic — all steps are implemented manually to reinforce foundational understanding.

## Dependencies
- Python 3.x
- NumPy
- Matplotlib (for visualization)
- OpenCV (only for reading images, optional)

## Run
```bash
python edge_detection.ipynb
