# GAN2Play

Let you to play with pretrained GAN (SAGAN + SNGAN + D2GAN)

# Requirement:
* old fastai 0.7 (put in the same file)
* python 3.6
* pytorch 0.4
* test on windows 10, cuda 9.0 
* dataset: CelebA (img_align_celeba_png)

# Results
Train on one 1080ti 8 hours, 37 epoch of 202,599 images
<p align="center"><img width="100%" src="img/0925.2125.png" /></p>


# change to your dir of dataset: 
put your image in **file train**.
It is **ok without any dataset and just play the pretrained GAN**.
<p align="center"><img width="50%" src="img/1.png" /></p>

<p align="center"><img width="70%" src="img/2.png" /></p>



##
Train on Guassian but generate on uniform will make the image looks better,
but the uniform images look more similar.
<p align="center"><img width="70%" src="img/3.jpeg" /></p>


## Continues change on row and colume.
<p align="center"><img width="80%" src="img/4.jpeg" /></p>



## multi_noise display.
show different results in mult std.
small std make image looks more similar,
large std make image looks more difference.
<p align="center"><img width="70%" src="img/5.jpeg" /></p>


# ref
SAGAN: https://github.com/heykeetae/Self-Attention-GAN \
D2GAN: https://github.com/search?q=D2GAN

