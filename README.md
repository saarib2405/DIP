# 🖼️ Digital Image Processing with OpenCV

## 📋 Implementations

### Basic Image Processing
1. **Thresholding Techniques**
   - Different thresholding modes visualization
   - Matplotlib integration for display

2. **Image Filtering**
   - Box Blur (Mean Filter)
   - Gaussian Blur
   - Median Filter
   - Bilateral Blur

### Morphological Operations
3. **Basic Morphology**
   - Erosion
   - Dilation

### Frequency Domain Processing
4. **Fourier Transform**
   - Discrete Fourier Transform (DFT)
   - Inverse DFT

5. **Cosine Transform**
   - Discrete Cosine Transform (DCT)
   - Inverse DCT

### Edge Detection
6. **Edge Detection Techniques**
   - Laplacian Edge Detection
   - Comparative analysis of Laplacian and Sobel operators


## ⚙️ Prerequisites

```txt
🐍 Python >= 3.7
📸 OpenCV-Python
🔢 NumPy
📊 Matplotlib
```

## 📦 Installation

```bash
# Clone this repository
git clone https://github.com/saarib2405/Digital_Image_Processing_OpenCV.git

# Navigate to the project
cd digital-image-processing

# Install dependencies
pip install -r requirements.txt
```

## 💻 Usage

Each technique is implemented in a separate script:

```python
# Example: Running thresholding script
python thresholding.py

# Example: Running edge detection comparison
python edge_detection_comparison.py
```

## 📁 Project Structure

<pre>
digital-image-processing/
├── 📂 filtering/
│   ├── 📜 box_blur.py
│   ├── 📜 gaussian_blur.py
│   ├── 📜 median_filter.py
│   └── 📜 bilateral_blur.py
├── 📂 morphology/
│   ├── 📜 erosion.py
│   └── 📜 dilation.py
├── 📂 frequency_domain/
│   ├── 📜 dft.py
│   └── 📜 dct.py
├── 📂 edge_detection/
│   ├── 📜 laplacian.py
│   └── 📜 edge_detection_comparison.py
└── 📂 thresholding/
    └── 📜 threshold_modes.py
</pre>
