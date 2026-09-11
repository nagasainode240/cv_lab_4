# Edge Detection — Computer Vision Lab 4

A Python notebook demonstrating three classical edge-detection techniques on grayscale images using **OpenCV** and **Matplotlib**.

## Techniques Implemented

| Method | Description |
|--------|-------------|
| **Sobel** | Computes gradient magnitude using first-order Sobel kernels in both X and Y directions. |
| **Prewitt** | Applies Prewitt convolution kernels via `cv2.filter2D` for horizontal and vertical gradients. |
| **Canny** | Multi-stage edge detector (Gaussian smoothing → gradient → non-max suppression → hysteresis thresholding). |

## Output

The notebook generates a 2×2 comparison plot showing:

1. Original Grayscale Image
2. Sobel Edge Detection
3. Prewitt Edge Detection
4. Canny Edge Detection

A sample output is saved as `output.png`.

## Requirements

- Python 3.x
- [OpenCV](https://pypi.org/project/opencv-python/) (`cv2`)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

Install dependencies:

```bash
pip install opencv-python numpy matplotlib
```

## Usage

1. Place your input image as `img.jpg` in the project root.
2. Open and run the notebook:

```bash
jupyter notebook cv4.ipynb
```

## Project Structure

```
cv4/
├── cv4.ipynb     # Main notebook with edge-detection code
├── output.png    # Sample comparison output
└── README.md     # This file
```

## License

This project is for educational / academic purposes.
