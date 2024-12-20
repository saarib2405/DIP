# Digital Image Processing with OpenCV

A collection of fundamental image processing implementations using OpenCV and Python. This repository contains various image processing techniques from basic filtering to frequency domain transformations.

## 📋 Implementations

### Basic Image Processing
1. *Thresholding Techniques*
   - Different thresholding modes visualization
   - Matplotlib integration for display

2. *Image Filtering*
   - Box Blur (Mean Filter)
   - Gaussian Blur
   - Median Filter
   - Bilateral Blur

### Morphological Operations
3. *Basic Morphology*
   - Erosion
   - Dilation

### Frequency Domain Processing
4. *Fourier Transform*
   - Discrete Fourier Transform (DFT)
   - Inverse DFT

5. *Cosine Transform*
   - Discrete Cosine Transform (DCT)
   - Inverse DCT

### Edge Detection
6. *Edge Detection Techniques*
   - Laplacian Edge Detection
   - Comparative analysis of Laplacian and Sobel operators

## 🔧 Prerequisites

python >= 3.7
opencv-python
numpy
matplotlib


## 💻 Installation

bash
# Clone the repository
git clone https://github.com/saarib2405/Digital_Image_Processing_OpenCV.git

# Navigate to project directory
cd digital-image-processing

# Install required packages
pip install -r requirements.txt


## 🚀 Usage

Each implementation is contained in its own Python script. To run any specific implementation:

bash
python <script_name>.py


Example:
bash
python thresholding.py


## 📁 Project Structure

digital-image-processing/
│
├── filtering/
│   ├── box_blur.py
│   ├── gaussian_blur.py
│   ├── median_filter.py
│   └── bilateral_blur.py
│
├── morphology/
│   ├── erosion.py
│   └── dilation.py
│
├── frequency_domain/
│   ├── dft.py
│   └── dct.py
│
├── edge_detection/
│   ├── laplacian.py
│   └── edge_detection_comparison.py
│
├── thresholding/
│   └── threshold_modes.py
│
├── requirements.txt
└── README.md


## 📌 Features

- Interactive visualization using Matplotlib
- Comprehensive implementation of various image processing techniques
- Well-documented code with explanatory comments
- Easy-to-use interface for each implementation
- Comparative analysis tools for different techniques

## 🖼 Sample Results

Results will be displayed using Matplotlib for better visualization and comparison.
