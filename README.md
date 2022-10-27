# Water-Extraction-MFFA-Multi-Level-Feature-Fusion-Technique 

MDIT: is a deep learning- based model trained to segment the multispectral sentinel-2 imagery. Using publicly available satellite imagery data we train a convolutional neural net to predict water occurrences in satellite images. MDIT achieved outmost performance for the prediction of water bodies from sentinel-2 satellite imagery datat.
![fo_1](https://user-images.githubusercontent.com/32522237/122047924-4fd9e780-cdfe-11eb-828b-b0e2a7d4ae65.JPG) 
()
![fs_1](https://user-images.githubusercontent.com/32522237/122047927-510b1480-cdfe-11eb-9b5b-b9220ba93a76.JPG)  ()

The above pictures are the part of our dataset.

# For Source-code Contact
<khyasir2@gmail.com>

# Dependencies 
TensorFlow (tested on TensorFlow 1.12)\\
Numpy\\
Tifffile (for reading geotiff files)\\
OpenCV (for reading and writing images)\\
Docker\\

Dependencies can be installed using the Python Package Installer (pip):

pip install tensorflow==1.12.0 tifffile opencv-python

# Dataset:
We downloaded the sentinel-2 satellite imagery from (https://scihub.copernicus.eu/) before downlioading the data you need to register yourself. 


# Satellite Images

You can download the satellite imagery from the (https://scihub.copernicus.eu/) or USGS Earth Explorer. The following are the entity IDs of the images we used. To find images by their ID first select the right dataset (in our case Sentinel-2) and then go to "Additional criteria". Here are some IDs as an example we used:

S2A_MSIL2A_20191109T054041_N0213_R005_T43SDR_20191109T080759.SAFE
S2A_MSIL2A_20191109T054041_N0213_R005_T43REQ_20191109T080759.SAFE
S2A_MSIL2A_20191020T053841_N0213_R005_T43RFP_20191020T081257.SAFE
S2A_MSIL2A_20190910T053641_N0213_R005_T43RDN_20190910T104452.SAFE

