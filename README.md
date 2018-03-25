# fashionCNN

This is a project which is basically done to classify clothes among 4 categories (coats&jackets, shirts, t-shirts and sweaters).
Implemented using deep - CNN (keeping VGG-16 as the reference architecture). 
you may need a GPU, for processing images of high resolutions. (I used one).


Code:
data Collection: 
  It is done by web scrapping the images. A smaple image scrapping code is in fashionCNN/deep code/fashionCNN/deep code/.
  Data Can also be collected by following this git link (was pretty useful):
  https://github.com/hardikvasa/google-images-download
  
Data Collected:
data collected for this process can be found in: fashionCNN/deepfashion/ 

CNN Model:
The model built is in fashionCNN/deep code/clothesCNN.ipynb

Two basic Bench marking saved models can be found in : 
fashionCNN/savedModel/

During the Prediction, the model sometimes gets biased between the "shirt" and "Tees&casuals" category which can be ignored by fueling the model with more 
and more appropriate data for each category.

