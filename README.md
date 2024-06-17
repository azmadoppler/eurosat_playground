# Simple tutorial(?) for EUROSat dataset


# Step 0: Installation
- Two easy ways to run the Deep Learning on your server (Reference Table below for which you want)
    - Installing using Conda [Japanese]() / [English](/test_program/)
    - Installing using Docker [Japanese]() / [English](/test_program/)
    - __Personal Opinion__ : Conda if you solo-ing the project and have no interest in anything other than Data Science, else Docker for Development experience both as group and individual. 

| Conda                                                                                | Docker                                                                           |
|--------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| Using Virtual Environment style to manage your package            | Run a something like a small PC (container) in your device  |
| Easier to use with simple commands                    | A bit more complex to set up but very powerful once running.                     |
| Good for ensuring the same setup on __your own computer__ .                               | Ensures the exact same setup on __any computer__ with Docker installed.              |
| Perfect for data science and machine learning projects.                             | Perfect for deploying apps and services reliably.                                |
| Lower computer resource usage, sharing system resources.                             | Higher resource usage, but better isolation of apps.                             |
| Less complex, ideal for those needing specific programming tools.         | More complex, ideal for creating isolated, consistent environments.              |
capabilities. |


## Step 1: Prepare the Datasets
- EUROSat datasets can be found in its [Originakl Site](https://github.com/phelber/EuroSAT) 

## [Using Convolutional Neural Network to performs classification on MultiBand dataset](Train_all_multiband_cnn.ipynb)
- Since data need to be proprocess with multiple band style, "Dataset" module for custom dataset is introduced here
- Learn how to use Rasterio to read multiband satelite data
- 


## [Using Vision Transformer to performs classification on RGB dataset](Train_rgb_vit.ipynb)
- Image can be loaded directly using ImageFolder 
- 



# Note 
- B01 - Aerosols 60 443
- B02 - Blue 10 490
- B03 - Green 10 560
- B04 - Red 10 665
- B05 - Red edge 1 20 705
- B06 - Red edge 2 20 740
- B07 - Red edge 3 20 783
- B08 - NIR 10 842
- B08A - Red edge 4 20 865
- B09 - Water vapor 60 945
- B10 - Cirrus 60 1375
- B11 - SWIR 1 20 1610
- B12 - SWIR 2 20 2190