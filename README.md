# Wilt

### About
Detecting diseased trees in QuickBird imagery

In this implementation the Wilt dataset can been considered to classify multispectal remote sensing images into diseased tree and other land form images. 

### Dataset
This implementation uses he wilt dataset from the UCI Machine Learning Repository. It consists of 4339 image segments for training and 500 image segments for testing. 

Attributes
* class: 'w' (diseased trees), 'n' (all other land cover) 
* GLCM_Pan: GLCM mean texture (Pan band) 
* Mean_G: Mean green value
* Mean_R: Mean red value
* Mean_NIR: Mean NIR value 
* SD_Pan: Standard deviation (Pan band) 

The dataset can be found in [here](http://archive.ics.uci.edu/ml/datasets/wilt)
