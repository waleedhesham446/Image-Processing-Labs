# Image-Processing-Labs
Small separated projects to apply the image proccessing concepts on real world cases
> “Sidenote.” For Convenience, only a sample of the output images is shown. However, all images can be found in the output folder of each lab.
# Table of Contents

* [Lab1 (Basics)](#lab1)
   * [Objectives](#lab1-objectives)
   * [Requirements](#lab1-requirements)
   * [Outputs](#lab1-outputs)
 * [Lab2 (Convolution & FT)](#lab2)
   * [Objectives](#lab2-objectives)
   * [Requirements](#lab2-requirements)
   * [Outputs](#lab2-outputs)
* [Lab3 (AVG Filters)](#lab3)
   * [Objectives](#lab3-objectives)
   * [Requirements](#lab3-requirements)
   * [Outputs](#lab3-outputs)
 * [Lab4 (Brightness Transformation)](#lab4)
   * [Objectives](#lab4-objectives)
   * [Requirements](#lab4-requirements)
   * [Outputs](#lab4-outputs)
  * [Lab5 (Edge Detection)](#lab5)
   * [Objectives](#lab5-objectives)
   * [Requirements](#lab5-requirements)
   * [Outputs](#lab5-outputs)

## <a name="lab1" />Lab1 (Basics)
### <a name="lab1-objectives" /> Objectives:
 * Reading an image and then plot it.
 * Indexing Numpy matrices.
 * HSV colormap.
 * Gray Scale
 * Understand Noise in Images 

### <a name="lab1-requirements" /> Requirements: 
* Reading and Dispalying an Image
* Converting an Image to Gray Scale
* Indexing an image matrix to get specific portions of it
* Display Hue, Saturation, and Value Channels and commenting on results
* Show Histograms for Different Images
* Add S&P Noise to Images

### <a name="lab1-outputs" /> Outputs:
#### Histogram:
<img src = "lab01 (Basics)/output/hist1.png"  height = "500"/>
<img src = "lab01 (Basics)/output/hist2.png"  height = "500"/>

#### Noise:
<img src = "lab01 (Basics)/output/noise2.png" height = "500"/>

#### HSV:
<img src = "lab01 (Basics)/output/hsv3.png" height = "500"/>


## <a name="lab2" />Lab2 (Convolution & FT)

### <a name="lab2-objectives" /> Objectives:
 * Learn the concept of Convolution in the space domain.
 * Learn the concept of Inverse Fourier Transform.
 * Learn the concept of Multiplication in frequency domain.

### <a name="lab2-requirements" /> Requirements: 
* Get The Inverse Fourier Transform of Images
* A Function that calculates the Fourier Transform of an image, applies Multiplication in Frequency domain, then converts it back to Spatial Domain
* A Function that performs Convolution in Spatial Domain

### <a name="lab2-outputs" /> Outputs:
#### Fourier Transform:
<img src = "lab02 (Convolution & FT)/output/highpass.png"/>

#### Convolution Filters:
<img src = "lab02 (Convolution & FT)/output/edged.png"/>


## <a name="lab3" />Lab3 (AVG Filters)

### <a name="lab3-objectives" /> Objectives:
 * Understand how Averaging Filters are used for Noise Reduction.

### <a name="lab3-requirements" /> Requirements: 
* Implement Median Filter
* Use Both **Gaussian** and **Median** Filters for Noise Reduction and compare the results.

### <a name="lab3-outputs" /> Outputs:
#### Median Filter:
<img src = "lab03 (AVG Filters)/output/custom_median.png"/>

#### Gaussian Filter:
<img src = "lab03 (AVG Filters)/output/mean.png"/>


## <a name="lab4" />Lab4 (Brightness Transformation)

### <a name="lab4-objectives" /> Objectives:
 * Know the effect of Negative transformation.
 * Know the effect of contrast enhancement.
 * Know the effect of gamma correction.
 * Understand and implement Histogram Equalization.


### <a name="lab4-requirements" /> Requirements: 
* Apply **Negative transformation** to an image.
* Apply **Gamma Correction** to an image.
* Implement a function to perform **Contrast Enhancement**.
* Implement a function to perform **Histogram Equalization**.
* Remove a Blue Hue from an Image

### <a name="lab4-outputs" /> Outputs:
#### Blue Hue Removal:
<img src = "lab04 (Brightness Transformation)/output/blue_effect_removal.png"/>

#### Histogram Equalization:
<img src = "lab04 (Brightness Transformation)/output/hist_equalization.png" height="400"/>


## <a name="lab5" />Lab5 (Edge Detection)

### <a name="lab5-objectives" /> Objectives:
 * Apply and notice the differences between edge detection techniques
 * Understand the effect of different parameters used in edge detection techniques.
 * Learn and implement “Sobel operator “and “LoG” edge detection techniques.


### <a name="lab5-requirements" /> Requirements: 
* Apply 4 different Edge Detection Techniques: **Sobel, Prewitt, Roberts,** and **Canny** and comment on results.
* Implement **Sobel** edge detector.
* Implement **LoG** edge detector.

### <a name="lab5-outputs" /> Outputs:
#### Built-in Filters:
<img src = "lab05 (Edge Detection)/output/built-in_filters.png"/>

#### Implemented Sobel:
<img src = "lab05 (Edge Detection)/output/custom_sobel.png"/>

#### Implemented LoG:
<img src = "lab05 (Edge Detection)/output/custom_LoG.png" height = "400"/>
