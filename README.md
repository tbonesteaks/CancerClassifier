# CancerClassifier
This repository holds a copy of the Binary Cancer Classifier built after the conclusion of the Histopathologic Cancer Detection competition held on Kaggle https://www.kaggle.com/competitions/histopathologic-cancer-detection. The notebook is an exploration of the efficacy of CNNs (Convolutional Neural Networks) ability to properly classify images as either malignant or benign. There is also implementations of transfer learning using the DenseNet models (121, 169, & 201). 

* Original Notebook: notebook.ipynb
  * The models are built in Keras and run in Tensorflow 2.13.
  * This notebook implements a tf.data.dataset architecture to import, augment, and normalize tif images on the fly.
   
* Kaggle Dataset: https://www.kaggle.com/competitions/histopathologic-cancer-detection/data
* Original Dataset: https://github.com/basveeling/pcam

A portion of University of Colorado Masters of Data Science Coursework.
