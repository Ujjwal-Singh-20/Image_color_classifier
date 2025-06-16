Dominant Color Extractor in Images
==================================

This script extracts and visualizes the dominant colors in an image using K-Means clustering. It uses OpenCV, SciPy, scikit-learn, and matplotlib to process and display image data.

Features:
---------
- Resizes the input image while maintaining the original aspect ratio
- Applies KMeans clustering to identify dominant color clusters
- Displays original, resized image, and the extracted dominant colors

Requirements:
-------------
Make sure the following Python libraries are installed:
- numpy
- pandas
- matplotlib
- seaborn
- opencv-python
- scikit-learn

Installation:
-------------
Use pip to install dependencies:

`
pip install numpy pandas matplotlib seaborn opencv-python scikit-learn
`

Usage:
------
1. Replace the file path in the script with your own image path:
       img1 = img.imread("./cat.jpg")
2. Run the script cell by cell, or use “Run All” in a Jupyter notebook.
3. The notebook will output:
   - Image shape before and after resizing
   - Dominant colors extracted using KMeans

Output:
-------
- Side-by-side view of original and resized image

Note:
-----
- You can adjust the number of dominant colors by modifying the 'num_colors' variable.
- Try using different images for varied results. Some sample filenames:
     - flower.jpg
     - sitting.jpg

