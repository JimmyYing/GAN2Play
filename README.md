# GAN2Play

Let you to play with pretrained GAN (SAGAN + SNGAN + D2GAN)

#Requirement:
* old fastai 0.7 (put in the same file)
* python 3.6
* pytorch 0.4
* test on windows 10, cuda 9.0 

# Results

<p align="center"><img width="100%" src="img/0925.2125.png" /></p>

change to your dir of dataset: put your image in **file train**.
It is **ok without any dataset and just play the pretrained GAN**.
<p align="center"><img width="60%" src="img/1.png" /></p>

<p align="center"><img width="80%" src="img/2.png" /></p>



##
Train on Guassian but generate on uniform will make the image looks better,
but the uniform images look more similar.
<p align="center"><img width="80%" src="img/3.jpeg" /></p>


## Continues change on row and colume.
<p align="center"><img width="80%" src="img/4.jpeg" /></p>



# multi_noise display.
show different results in mult std.
small std make image looks more similar,
large std make image looks more difference.
<p align="center"><img width="90%" src="img/5.jpeg" /></p>
