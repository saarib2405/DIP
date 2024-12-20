# 🖼️ Digital Image Processing with OpenCV

## 🚀 Features

<table>
<tr>
<td width="50%">

### 🎨 Image Enhancement
- **Thresholding Techniques**
  - Multiple thresholding modes
  - Matplotlib visualization
- **Filtering Operations**
  - Box Blur (Mean Filter)
  - Gaussian Blur
  - Median Filter
  - Bilateral Blur

</td>
<td width="50%">

### 🔄 Transformations
- **Morphological Operations**
  - Erosion
  - Dilation
- **Frequency Domain**
  - DFT & Inverse DFT
  - DCT & Inverse DCT

</td>
</tr>
</table>

### 🔍 Edge Detection
- Laplacian Edge Detection
- Comparative Analysis: Laplacian vs Sobel

---

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

## 🎯 Available Implementations

|
 Category 
|
 Techniques 
|
 Visualization 
|
|
----------
|
------------
|
---------------
|
|
 Thresholding 
|
 Different Modes 
|
 Matplotlib 
|
|
 Filtering 
|
 Box, Gaussian, Median, Bilateral 
|
 Matplotlib 
|
|
 Morphology 
|
 Erosion, Dilation 
|
 OpenCV Window 
|
|
 Frequency 
|
 DFT, DCT 
|
 Matplotlib 
|
|
 Edge Detection 
|
 Laplacian, Sobel 
|
 Comparison Plot 
|
