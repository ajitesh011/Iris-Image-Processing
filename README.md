# Iris-Image-Processing
Image Acquisition-two images are taken as input simultaneously
in which one is the defected image and the oter is the image of
a normal eye.

Pre-processsing-in open cv  a normal image on  being converted direclt
to bgr does not provide an image through which feature can be extracted,
thus it needs to be pre processed i.e   unwanted pixels
 are removed and make the image ready for featute extraction.

Image Segmentation-The goal of segmentation is to simplify and/or 
change the representation of an image into something that is 
more meaningful and easier to analyze.
 Image segmentation is typically used to locate objects and boundaries 
(lines, curves, etc.) in images. Thus various filters are applied and the image 
is being resized so as to extract the region of interest with ease.

Feature Extraction-in this part of code the the mean or the centre of the 
the pupil is calculated so as to extract the region in the 5-6 o'clock of the 
right eye and 6-7 o'clock of the left eye and then again applying 
the spatial filter in the ratio of 0.67,3,1.5 to the extracted region.

region of interest-The  region to be analysed is now extracted mathematical 
ratios 
the region of interest thus extarcted is further worked up and unneccessary 
regions are removed to focus on the importnt parts.

Canny Edge detection-The Canny edge detector is an edge detection operator that 
uses a multi-stage algorithm to detect a wide range of edges in images.
tissues play an important role in determining the defect thus the edges of
the tissues are being noticed.
As it is visible in the above images,there are patches dveloped in the defeced eye 
as compared to the normal eye.
The patches in the extracted image are seen because of Uric acid crystal 
deposition in the iris.

The kidneys remove waste products called urea from the blood through tiny 
filtering units called nephrons. The nephrons filter water, ions, 
nitrogenous wastes, and other materials from the blood.

Inefficient kidney function can cause a water imbalance, leading to 
increased fluid around the eyes. The condition can develop in one or both eyes. 
It is reported in the paper that Urate crystals get deposited in the iris.
Urate crystals can be formed due to high levels of uric acid in your blood.
The conditions that lead to chronic kidney disease may also have an 
adverse effect on the eyes and vision.
  
