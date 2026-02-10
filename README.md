# ARTI404 – Image Processing 🖼️

**University:** Imam Abdulrahman Bin Faisal University (IAU)  
**College:** CCSIT - Computer Science & AI  

## 👤 Student Information
* **Name:** Khalid Waleed Alhilal
* **Student ID:** 223000788
* **Class/Section:** 8ma02

---

## 📂 Labs Structure & Status

| Lab | Topic | Status | Location | Notes |
| :--- | :--- | :--- | :--- | :--- |
| **Lab 1** | Basics of Programming | ✅ Completed | [Root Directory](./Lab1tutorial.ipynb) | *Kept in root to maintain submission link validity* |
| **Lab 2** | Digital Image Fundamentals | ✅ Completed | [Lab2 Folder](./Lab2/Lab2.ipynb) | Image Sampling, Quantization & Operations |

---

## 📘 Repository Contents

### ✅ Lab 1: Basics of Programming with Python
This folder contains the practical implementation for Lab 1, focusing on digital image representation and manipulation using Python.

#### 📝 Implemented Tasks:
1.  **Image Loading & Visualization:**
    * Loaded images using **OpenCV** (handled BGR to RGB conversion).
    * Loaded images using **PIL** (Python Imaging Library).
    * Displayed images side-by-side using `matplotlib`.
2.  **Image Storing:**
    * Saved processed images to the disk using both OpenCV and PIL methods.
3.  **Image Representation (Arrays):**
    * Inspected image properties (Shape, Data Type).
    * Converted PIL images to NumPy arrays to understand pixel structure.
4.  **NumPy Assessment & Operations:**
    * **Array Creation:** Generated arrays of Zeros, Ones, and specific ranges.
    * **Matrix Operations:** Created 3x3 matrices, Identity matrices, and performed reshaping.
    * **Indexing & Slicing:** Performed advanced array extraction.

### ✅ Lab 2: Digital Image Fundamentals
This lab focuses on understanding image resolution (Spatial & Gray-level) and performing arithmetic/logical operations on images.

#### 📝 Implemented Tasks:
1.  **Sampling & Quantization:**
    * Implemented `sample_image` function to observe the effects of reducing spatial resolution (Pixelation).
    * Implemented `quantize_image` function to observe the effects of reducing gray-level resolution (False Contouring).
    * Visualized the degradation effects using `matplotlib`.
2.  **Arithmetic Operations:**
    * **Subtraction:** Subtracted two images to find differences.
    * **Addition:** Added a constant value (175) to an image to adjust brightness.
3.  **Logical & Set Operations:**
    * **Set Difference:** Calculated elements in Image A but not in Image B.
    * **Symmetric Difference:** Calculated elements in A or B but not both (XOR).
    * **Intersection:** Calculated common elements between two images (AND).

---

## 🛠️ Requirements
To run the notebooks, ensure the following libraries are installed:

```bash
pip install numpy opencv-python matplotlib pillow
```

## 🚀 How to Run
* 1- Clone the repository.

* 2- Navigate to the project folder.

* 3- Launch Jupyter Notebook:

For Lab 1:

```Bash
jupyter notebook Lab1tutorial.ipynb
```

For Lab 2:

```Bash
jupyter notebook Lab2/Lab2.ipynb
```
