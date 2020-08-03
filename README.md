# Mewrons, pod-139-talented-wrasse
Scientific Question:

How does the brain encode different image features?

Brief scientific background:

Literature has shown that visual cortices respond differently to different aspects of visual stimuli (i.e. V3 is more sensitive to differences in grating contrast than V1 
(Tootell et al. 1998). Here we want to explore whether different features of images affect different visual regions.

Analyses : 

We initially proposed to use GLM (for relation between mean luminance and each visual region), however we proceeded with breaking the images in tiles for mean luminance extraction,
PCA with different number of components and Canny and Horizontal/Vertical Edge detection technique. We even proceeded with a DNN but only for luminance features and finally 
correlation between predicted and true values of voxel response per image.(e.g., if the test image is always very close, but not the closest to the predicted test image,
you would still have a high correlation even if test accuracy is low).

Experience :  

In a nutshell, we did not get good results. Working with this dataset, trying to answer this question we exhausted almost every new topic we learnt at NMA,
and that was very rewarding, under the guidance of an amazing mentor and TA!
