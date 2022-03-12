1. In the zipped folder "IDL code and sample data for computing accuracy metrics", there are two files:
   (1) an IDL code "optimal_accuracy_metrics.pro" which can compute the four metrics, AD, RMSE, edge, LBP for any fused images. Input the data according to the pop-up window when running the code. The result will be saved as a csv file in the folder of fused image and named as fused image name+_accuracy.csv (e.g.,fused_fine_image_FSDAF.tif_accuracy.csv). The first n rows are accuracies of n bands, and the last row is the average accuracies of multiple bands.
   Please note: the code used some functions from the classic ENVI, so classic ENVI should be open when compiling the code! 
   (2) sample data: a 3-band reference image (green, red, nir) on 25 Nov 2001 in the CIA site; a fused image by FSDAF

2. In the zipped folder "R code and sample data for drawing Taylor like diagram", there are two files:
   (1) a R code "APA_diagram.R" which can draw the all-round performance assessment(APA) diagram, a Taylor-like polar diagram to show the accuracies of different fused images with "fair" and "good" ranges.
   Please set the parameters and input the data file at the beginning of the code based on your own data. The produced diagram will be saved to your working direction with the filename you define (e.g., APA diagram example.png).  
   (2) data_for_APA_diagram.csv: a sample data for testing the code, which includes accuracies of 6 fusion methods for fusing the image on 25 Nov 2001 in the CIA site.

To Cite these codes and dataset in Publications:
Zhu, X., Zhan, W., Zhou, J., Chen, X., Liang, Z., Xu. S., Chen, J. A novel framework to assess all-round performances of spatiotemporal fusion models, Remote Sensing of Environment (forthcoming)
