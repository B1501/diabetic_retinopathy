# Diabetic retinopathy
Projects related to the diabetic retinopathy data set. 

### Project 1
#### [Diabetic retinopathy: image processing via CLAHE](https://github.com/Meena-Mani/diabetic_retinopathy/blob/master/image_processing/DR_clahe_rgb.ipynb)
For deep learning systems built to automate the identification of diabetic retinopathy, preprocessing entails cropping, resizing, normalizing the images 
and enhancing the image contrast to better identify distinguishing features. For this last, CLAHE, which stands for
Contrast Limited Adaptive Histogram Equalization, is applied. Fundus images are RGB images so the treatment is a little 
different than for grayscale X-Ray, MRI or CT images one usually deals with in medical imaging.

In this exercise we will apply an OpenCV implementation of CLAHE to retinal fundus images, 
vary two of the paramters (clip limit and tile size) and compare the results with the original image. 
