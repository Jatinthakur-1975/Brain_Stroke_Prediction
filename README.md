# Brain_Stroke_Prediction

#The Brain Stroke CT Image Dataset from Kaggle provides normal and stroke brain Computer 
Tomography (CT) scans. The dataset presents very low activity even though it was uploaded 
more than 2 years ago. It may be probably due to its quite low usability. The challenge is to 
get some interesting results, i.e., to try to perform brain stroke detection, even from this 
low-quality CT scan dataset. 


#The followed approach is based on the usage of a 3D Convolutional Neural Network (CNN) in 
place of a standard 2D one. 2D CNNs are commonly used to process both grayscale (1 
channel) and RGB images (3 channels), while a 3D CNN represents the 3D equivalent since 
it takes as input a 3D volume or a sequence of 2D frames, e.g. slices in a CT scan. 
