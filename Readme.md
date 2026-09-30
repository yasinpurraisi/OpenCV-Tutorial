
# OpenCV Tutorial

A collection of Python tutorials for [OpenCV](https://opencv.org/) image processing and computer vision. The material is split into focused notebooks for easier reading and practice.

## Notebooks

- [Image Basics](ImageBasics.ipynb): Image input and display, pixels, color channels, grayscale, transparency, masks, and basic image operations.
- [Drawing and Interaction](DrawingAndInteraction.ipynb): Drawing shapes and text, mouse callbacks, annotation, and trackbars.
- [Video Processing](VideoProcessing.ipynb): Webcam, online streams, screen recording, video files, and writing video output.
- [Binary Images and Morphology](BinaryImagesAndMorphology.ipynb): Thresholding, binary images, morphology, line extraction, and connected components.
- [Contours and Shape Analysis](ContoursAndShapeAnalysis.ipynb): Contours, hulls, bounding shapes, moments, approximation, and text boxes.
- [Color Processing](ColorProcessing.ipynb): HSV and LAB, color filtering, green-screen removal, K-means colors, and hue histograms.
- [Image Enhancement](ImageEnhancement.ipynb): Arithmetic and intensity transforms, histograms, equalization, denoising, sharpening, and edge detection.
- [Geometric Transforms and Features](GeometricTransformsAndFeatures.ipynb): Hough transforms, affine and perspective transforms, corner detection, and SIFT/ORB matching.
- [Machine Learning](MachineLearning.ipynb): K-nearest-neighbor classification with the HODA handwritten-digit dataset.
- [Motion Tracking](MotionTracking.ipynb): Sparse and dense optical flow, background subtraction, and CAMShift.

## Requirements

Install the core dependencies before running the notebooks:

```sh
pip install opencv-python numpy matplotlib pillow
```

The machine-learning notebook also uses SciPy and scikit-learn:

```sh
pip install scipy scikit-learn
```

The screen-recording example requires `mss`:

```sh
pip install mss
```

Run notebooks from the project directory so paths such as `images/Cat.jpg`, `videos/snufkin.mp4`, and `Datasets/Data_hoda_full.mat` resolve correctly. Interactive windows, webcam access, and screen recording depend on local hardware and desktop support.

## Author

- GitHub: [yasinpurraisi](https://github.com/yasinpurraisi)
- Email: yasinpourraisi@gmail.com
- Telegram: [yasinprsy](https://t.me/yasinprsy)

## Acknowledgments

This tutorial was written from scratch by me, with the following resources used for learning and inspiration:
- [Official OpenCV Documentation](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)
- Various OpenCV tutorials

