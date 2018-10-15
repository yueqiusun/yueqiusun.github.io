---
title: "Full Hydrodynamic Simulation Prediction from Dark Matter Simulation"
collection: 'research'
permalink: /research/dark
venue: "Flatiron Institute"
date: 2018-09-10 - present
location: "New York, US"
---

[Porject Proposal ppt](https://drive.google.com/open?id=15F9UssTuPMLMevCMA6Pni_shcFjtT2mf)

The project is one of the most challenging and interesting project in the interface of physics and machine learning. Physicists have spend ages in accumulating "physical intuitions" through their training. Machine Learning has recently be touted to be able to probably learn "science" without the guide of humans or scientists for scientific problems.


One may wonder what would happen if one combines physical intuition and the power of machine learning, in particular deep neural network. What happens if we impose rotational, translational invariance that is inherent in the training set directly instead of letting the system learn it by itself?


There have been a bit of literature on implementing what we think is inherent in the system into the NN, however, there are a lot more to be done.


Cosmology has a lot of physical laws and rules we can implement onto our deep NN that can in principle significantly improve our results in prediction.




This is a riskier project, but probably have a higher return than most projects in physics alone, since it will lead the way in understanding how one can put in intuitions or existing knowledge directly into the network instead of through training sets.


The data will be real and complex numbers as a function of frequency (radio frequency) and time. The data set will be astrophysical in nature, but also has interference from tele-communications, radio, TV.


The size of the dataset can range from a few TB to a few PB (depending on how much we need to generate realistic mock datasets).


Diary
======
October: 
We sliced the data into 32 x 32 x 32 pieces of cube of size 32 x 32 x 32 in which each pixel contained the count(of mass). Built a Unet model(no skip connection for now). I built a training module, and train the model. Weird stuff happened. While training, the test loss didn't change at all and were very small at the beginning. Turns out the target data(the count of mass in hydrodynamic distribution has large propotion of zeros, and some of the target cube is nothing but zeros)

September:
Understood the problem that is to map dark matter distribution to hydrodynamic distribution. 