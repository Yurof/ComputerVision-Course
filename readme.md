# Chapter 9 - Face Recognition
## Face recognition by Eigenfaces method :
- identify a face from a database of faces
- determine whether an image contains a face present in the database
- to decide whether an image represents a face or not <br />

We will be using the [Yale Faces Database.](http://vision.ucsd.edu/content/yale-face-database) <br />
This database contains 120 greyscale images, representing the faces of 15 people. There are 8 images per person.
 <br />
<div style="text-align:center"><img src="readme_asset\chp9-1.png" width="600"></div>
<br />

The method developed by Turk and Pentland defines the eigenfaces as the main axes obtained by carrying out a principal component analysis (PCA) of the vectors associated with the reference faces.  <br />
We will use singular value decomposition (SVD). <br /> <br />



<div style="text-align:center"><img src="readme_asset\chp9-2.png" width="400"><figcaption> example of reconstruction of an image </figcaption></div>

# Chapter 8 - Split & Merge
the split and merge algorithm is used for image segmentation.<br />
it works like this:
- Split the image into equal size regions
- Calculate homogeneity for each region
- If the region is homogeneous, then merge it with neighbors
- The process is repeated until all regions pass the homogeneity test
  
<div style="text-align:center"><img src="readme_asset\chp8-1.png" width="300"></div>

<div style="text-align:center"><img src="readme_asset\chp8-2.png" width="800"></div>

# Chapter 7 - Searches Images By Content

We will compute a measure of similarity between two images from the normalized histogram. This measure of similarity will be used in order to find images that are the most similar to a given image.

<div style="text-align:center"><img src="readme_asset\chp7-1.png" width="600"><figcaption> 20 best matches of image 'Liontigre1.png' </figcaption></div>

# Chapter 6 - Harris Corner Detector

<div style="text-align:center"><img src="readme_asset\chp6-1.png" width="500"></div>

<div style="text-align:center"><img src="readme_asset\chp6-2.png" width="200"></div>

# Chapter 5 - Edge Detection
The goal of this practial work is to experiment various edge detectors.

- comparison between the first and second order detectors
- study of the impact of smoothing
- removing non maxima answers of the detectors
- evaluation in term of robustness and localization
  
<div style="text-align:center">
<img src="readme_asset\chp5-1.png" width="300">
<img src="readme_asset\chp5-2.png" width="307">
</div>
<div style="text-align:center"><img src="readme_asset\chp5-3.png" width="800"></div>


# Chapter 4 - Frequency 
# Chapter 3 - 2D Sampling & Aliasing
# Chapter 2 - Fourier Transform
# Chapter 1 - Introduction & Image Enhancement
