# Hiperespectrales

This is an multi-spectral algorithm created in eCognition to detect vegetal mass and classify weeds. 
Input is 4 images from RED, NIR, REG and GRE bands. 
Output is a classified image with 3 classes: soil, sunflower and weed.

In this Github we can find the following items:

- eCognition files: 038.dpr and 038.dps are the eCognition developer project and respective layer setting.

- Example image files for executing the project: 4 images from 4 different bands are presented, 038-GRE.TIF, 038-NIR.TIF, 038-RED.TIF and 038-REG.TIF 

- 'Raw test set' folder contains the 16 original images taken from Sequoia camera with no processing. Every image has 4 files corresponding to GRE, NIR, RED and REG bands.

- 'Undistorted test set' folder contains 16 images processed to correct lens distortion. Every image has 4 files corresponding to GRE, NIR, RED and REG bands.

- 'Rectified test set' folder contains 16 images processed to rectify the image and bring the inner contnt of the frame to the main plane. Every image has 4 files corresponding to GRE, NIR, RED and REG bands. This is the ideal input format for the algorithm.

- 'Test set' folder contains both the ground truths and output images showing the final classification for the 16 test images found in 'Rectified test set'.

These files correspond to a submitted paper called 'Multi-spectral imaging for weed identification in herbicides testing', the abstract of which is given below:

ABSTRACT
Weeds are a relevant problem for crops because they can cause damage in several ways. They compete with crops for space, light, water and nutrients; and  they could host diseases and pests. Herbicides attempt to minimize the occurrence of these weeds. However, an evaluation of the performance of these herbicides on crops must be made before they are marketed. In this paper, a new methodology to help to improve the efficiency in herbicides assessment is explained. It consists of an automatic tool  to quantify the percentage of weeds and plants of interest (sunflower in the case study) that are present in a given area. This tool represents a breakthrough in the automatic  measurement of the effectiveness of herbicides over a sunflower crop. Images of the crop field  taken from a multi-spectral camera (Sequoia) were used to apply the developed methodology. Firstly, the quality of the images of each band (Green, Near Infrared, Red and Red Edge) is improved through  correcting  sensor lenses and perspective distortions and a band-to-band registration. } Later, the resulting  multi-spectral images are classified into several classes  (soil, sunflower and weed) through a novel algorithm implemented in   e-Cognition software. Finally, the  percentage of weed and sunflower plants in the images  is also provided. Obtained results of the proposed classifications have been compared with two  deep learning-based segmentation methods (U-Net and FPN),  showing better results for our approach in terms of the IoU metric for classifying the weed. Thus, the proposed methodology provides a fast and efficient approach to help  measure the effectiveness of newly developed herbicides.

Authors: Luis O. LÓPEZ, Gloria ORTEGA, Francisco AGÜERA-VEGA, Fernando CARVAJAL-RAMÍREZ, Patricio MARTÍNEZ-CARRICONDO2, Ester M. GARZÓN
 
Key words: Multi-spectral images, Herbicide assessment, Multi-spectral classification, Deep
Learning segmentation, e-Cognition
