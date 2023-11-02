# Mini-DDSM-Mass-Classification-over-4-model
This project aims to evaluate and select the most suitable model from a pool including VGG16, ResNet50, MobileNet, and EfficientNet.  
The target is find the lightweight model withouth comprised accuracy.  
The 'model.ipynb' notebook encompasses both preprocessing steps and model fitting procedures.  
The Mini-DDSM data set is available at  
https://www.kaggle.com/datasets/cheddad/miniddsm2?select=MINI-DDSM-Complete-JPEG-8  
All training computations were conducted on Google Colab, utilizing a dataset that has been compiled and subsequently uploaded to Google Drive.  
To expedite the image loading process, the dataset was compressed and then extracted.  
It is worth noting that various hyperparameter adjustments were made throughout the training process, although these modifications may not be explicitly documented in the file.  
For example, the EfficientNet was trained for over 20 epochs, with manual adjustments to the learning rate made every 10 epochs.
