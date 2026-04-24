# ARTI404 – Image Processing 🖼️

**University:** Imam Abdulrahman Bin Faisal University (IAU)  
**College:** CCSIT - AI  

## 👤 Student Information
* **Name:** Khalid Waleed Alhilal | **ID:** 223000788 | **Section:** 8ma02

---

## 📂 Labs Overview & Status

| Lab | Topic | Status | Location |
| :--- | :--- | :--- | :--- |
| **Lab 1** | Python & OpenCV Basics | ✅ Completed | [📂 View Lab 1](./Lab1/) |
| **Lab 2** | Image Fundamentals | ✅ Completed | [📂 View Lab 2](./Lab2/) |
| **Lab 3** | Image Manipulations | ✅ Completed | [📂 View Lab 3](./Lab3/) |
| **Lab 4** | Intensity Transformations & Filtering | ✅ Completed | [📂 View Lab 4](./Lab4/) |
| **Lab 5** | Spatial Filtering (Smoothing & Sharpening) | ✅ Completed | [📂 View Lab 5](./Lab5/) |
| **Lab 6** | Frequency Domain Filtering | ✅ Completed | [📂 View Lab 6](./Lab6/) |
| **Lab 7** | Laplacian & Statistical Filters | ✅ Completed | [📂 View Lab 7](./Lab7/) |

---

## 📗 Implementation Details

### ✅ Lab 7: Laplacian & Statistical Filters
* **Part A (Laplacian):** Implemented image sharpening using the Laplacian operator and `cv2.convertScaleAbs` for visual edge enhancement.
* **Part B (Statistical Filters):** Developed custom filters including Midpoint, Alpha-trimmed, and Harmonic mean filters to handle various noise types (Gaussian, Salt & Pepper).

### ✅ Lab 6: Frequency Domain Filtering
* **Task 1 (Sobel via FFT):** Applied Sobel edge detection filters (X and Y) in the frequency domain using Fast Fourier Transform (`np.fft.fft2`). Handled kernel padding, centering, and shifting (`ifftshift`) to prevent spatial displacement, and computed the final gradient magnitude.

### ✅ Lab 5: Spatial Filtering
* **Task 1 (Box Filter):** Applied a 7x7 Box filter for image smoothing and noise reduction.
* **Task 2 (Gaussian Filters):** Compared the effects of 5x5 and 21x21 Gaussian kernels on an image.
* **Task 3 (Laplacian Filter):** Implemented image sharpening by subtracting a 3x3 Laplacian edge map from the original image using unsharp masking.

### ✅ Lab 4: Intensity Transformations & Filtering
* **Task 1 (Contrast Stretching):** Rescaled image intensity values based on the 3rd and 80th percentiles to improve contrast.
* **Task 2 (Histogram Equalization):** Applied global histogram equalization to enhance image details and plotted the flattened histogram.
* **Task 3 (Histogram Matching):** Adjusted the color distribution of a target image (Chelsea) to match a reference image (Rocket) using `scikit-image`.

### ✅ Lab 3: Image Manipulations
* **Task 1 (Geometric):** Applied Scaling (1.5x), Rotation (120°), and Horizontal Shear.
* **Task 2 (Intensity):** Implemented Image Negative, Log Transformation, and Power-Law (Gamma = 2.0).
* **Optimization:** Used a centralized image loading setup for all sub-tasks.

### ✅ Lab 2: Digital Image Fundamentals
* **Resolution:** Studied Spatial Sampling and Gray-level Quantization effects.
* **Operations:** Brightness adjustment (Addition) and Image Subtraction.
* **Logic:** Set operations including Intersection and Symmetric Difference.

### ✅ Lab 1: Basics of Programming
* **Environment:** Setup of OpenCV, NumPy, and Matplotlib.
* **Fundamentals:** Array slicing, BGR to RGB conversion, and Matrix operations.

---

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/KhalidExe/ARTI404-Image-Processing.git](https://github.com/KhalidExe/ARTI404-Image-Processing.git)
   cd "ARTI404-Image-Processing"
   ```
2. **Install the required libraries:**
   ```bash
   ip install -r requirements.txt
   ```
3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
4. **Navigate to the desired Lab folder (e.g., Lab4/) and open the .ipynb file to run the cells.**
    