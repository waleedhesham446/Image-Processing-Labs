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
* [lab03 (AVG Filters)](#lab3)
   * [Objectives](#lab3-objectives)
   * [Requirements](#lab3-requirements)
   * [Outputs](#lab3-outputs)
 * [lab04 (Brightness Transformation)](#lab4)
   * [Objectives](#lab4-objectives)
   * [Requirements](#lab4-requirements)
   * [Outputs](#lab4-outputs)

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


## <a name="lab3" />lab03 (AVG Filters)

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


## <a name="lab4" />lab04 (Brightness Transformation)

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
<img src = "lab04 (Brightness Transformation)/output/hist_equalization.png"/>
