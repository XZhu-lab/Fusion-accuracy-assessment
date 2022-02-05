1. In the zipped folder "IDL code and sample data for computing accuracy metrics", there are two files:
   (1) an IDL code "optimal_accuracy_metrics.pro" which can compute the four metrics, AD, RMSE, edge, LBP for any fused images. Input the data according to the pop-up window when running the code. The result will be saved as a csv file in the folder of fused image and named as fused image name+_accuracy.csv (e.g.,fused_fine_image_FSDAF.tif_accuracy.csv). The first n rows are accuracies of n bands, and the last row is the average accuracies of multiple bands.
   Please note: the code used some functions from the classic ENVI, so the classic ENVI software should be open when compiling the code! 
   (2) sample data: a 3-band reference image (green, red, nir) on 25 Nov 2001 in CIA site; a fused image by FSDAF

2. In the zipped folder "R code and sample data for drawing Taylor like diagram", there are two files:
   (1) a R code "Taylor_ACCURACY.R" which can draw the Taylor-like diagram to show the accuracies of different fused images with "fair" and "good" ranges.
   Please set the parameters in the code based on your own data 
   (2) data_for_Taylor.csv: a sample data for testing the code, which includes accuracies of 6 fusion methods for fusing the image on 25 Nov 2001 in CIA site.

To Cite these codes and dataset in Publications:
1.Zhu, X., Zhan, W., Zhou, J., Chen, X., Liang, Z., Xu. S., Chen, J. Optimal accuracy metrics and a diagram to assess the performance of spatiotemporal fusion models from multiple aspects, Remote Sensing of Environment (under review)
2.Zhu, X. repositories:Fusion-accuracy-assessment, https://github.com/XZhu-lab/Fusion-accuracy-assessment
