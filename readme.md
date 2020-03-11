# Face Sketch to Image Generation using GAN

An image generation system using GAN to turn face sketches into realistic photos

## Install requirements
pip install -r requirements.txt

## Keras-contrib installation
- git clone https://www.github.com/keras-team/keras-contrib.git
- cd keras-contrib
- python setup.py install

Or you can refer to this link https://medium.com/@kegui/how-to-install-keras-contrib-7b75334ab742

## Data Augmentation
First of all, you need to do data augmentation using this [notebook](https://github.com/Malikanhar/Sketch-to-Image/blob/master/Data%20Augmentation.ipynb)

## Start Training
Start training GAN model with this [notebook](https://github.com/Malikanhar/Sketch-to-Image/blob/master/ContextualGAN.ipynb)

## Performance Measurement
Calculate SSIM (Structural Similarity Index) and Verification Accuracy (L2-norm) using this [notebook](https://github.com/Malikanhar/Sketch-to-Image/blob/master/Compute%20SSIM%20and%20L2-norm.ipynb)

