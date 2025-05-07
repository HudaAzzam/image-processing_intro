# project1: 🖼️ Edge Detection: Sobel vs. Canny

## 📌 Overview
This repository explores **edge detection** using two widely used techniques: **Sobel** and **Canny**. The goal is to compare their performance and understand their differences.

- **Sobel**: A simple gradient-based method for detecting edges.
- **Canny**: A more advanced algorithm that includes noise reduction, edge thinning, and thresholding.

This project is part of my **learning journey** in image processing.

---
# Project 2: Gaussian Noise Removal – Filtering Comparison
This mini-project explores and compares different image filtering techniques for removing Gaussian noise from grayscale images. The workflow includes:

🖼️ Images Used
cameraman.pgm – classic grayscale test image.

einstein.pgm – grayscale portrait image.
(Both from public domain academic sources.)

🔧 Steps Performed
Added Gaussian Noise (σ = 20) to both images.

Applied the following filters:

🟦 Average (Mean) Filter – standard 5×5 kernel.

⚪ Morphological Opening – removes bright noise.

⚫ Morphological Closing – removes dark noise.

🔄 Opening → Closing

🔄 Closing → Opening

📊 Results
Average filter: Best for general noise suppression but causes blurring.

Morphological opening: Preserves structure and removes bright specks effectively.

Opening → Closing: Balanced cleaning of both light and dark noise.

Closing alone: Minor improvements for dark noise only.

🧠 Takeaways
Cameraman: Morphological opening gave the best result – clear, low-noise image with preserved edges.

Einstein: Opening then Closing and Opening alone provided optimal balance between denoising and detail preservation.

📁 Notebook File
Gaussian_Noise_Filtering.ipynb: Contains full Colab-ready code, explanations, and side-by-side visualizations.
