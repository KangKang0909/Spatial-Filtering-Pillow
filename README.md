# Spatial Filtering with Pillow

This project implements various **Spatial Filtering** techniques using the **Pillow (PIL)** library in Python. It demonstrates image processing concepts by applying mathematical kernels to filter images in the spatial domain.

## 🚀 Overview
The goal of this project is to perform image enhancement and restoration using the Pillow library. Unlike OpenCV, this project focuses on using Python's native imaging tools to handle $3 \times 3$ and $5 \times 5$ filters for noise reduction and edge detection.

## Key Features
* **Built with Pillow:** Uses the `PIL.ImageFilter` and `PIL.Image` modules.
* **Smoothing:** Implementation of **Blur**, **BoxBlur**, and **GaussianBlur** to reduce high-frequency noise.
* **Rank Filters:** Includes **MedianFilter** and **Min/Max** filters, which are highly effective for removing impulse noise.
* **Edge Enhancement:** Features **FIND_EDGES**, **SHARPEN**, and **SMOOTH** presets.
* **Interactive Notebook:** All logic is contained within a Jupyter Notebook for easy visualization.

## 🛠️ Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/KangKang0909/Spatial-Filtering-Pillow
    cd Spatial-Filtering-Pillow
    ```

2.  **Install dependencies:**
    Make sure you have Python and the Pillow library installed:
    ```bash
    pip install Pillow matplotlib
    ```

## 📁 Project Structure
* `Spatial Filtering Pillow.ipynb`: The main Jupyter Notebook containing the code and step-by-step image processing results.
* `barbara.png`, `cameraman.jpeg`, `lenna.png`: Standard test images used for demonstrating filtering effects.
* `.idea/`: Project configuration files for the IDE.
