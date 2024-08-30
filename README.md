# Gravitational Wave Glitches Classification
-------------------------------------------------------------------------------------

**This project is developed as a part of final internship for the course Astronomical Data Science offered by Spartificial.**

-----------------------------------------------------------------------------------------

# WaveGlitchNet - 

Convolutional Neural Network model that classifies glitches / noise in detected Gravitational Wave Data.

## Features of the Project - 

1. WaveGlitchNet uses the power of Convolutional Neural Networks to classify glitches that occur during Gravitational Waves detection. Glitches in Gravitational Waves can be considered similar to noise.
2. The original dataset is located on Kaggle. It consists of approximately 22000 training images and 4000 images in validation and testing datasets.
3. The whole project from start to end is written in Python. It uses Convolutional Neural Networks to train on the images.
4. The overall performance of WaveGlitchNet can be considered very good as it performs well on all categories.
5. The training dataset had imbalance in the categories hence class weighting was used to help the model give equal importance to all the categories.

*The project is developed in Python using Jupyter Notebooks in Google Colab and Kaggle Notebooks.*

The file *gravity_spy_test.ipynb* is the smaller file that is used to see the performance of WaveGlitchNet on test data. The WaveGlitchNet model file (.h5) and test data folder zipped can be downloaded using
the link below. (The link directs you to Google Drive, it should be accessible to all with the link but if it is still not accessible please ask for permissions)

**The model file and test dataset can be found in the following link**

Link to Kaggle Dataset - https://www.kaggle.com/datasets/tentotheminus9/gravity-spy-gravitational-waves/data

Model file - https://drive.google.com/file/d/1dS-6_ZIfAReRlNra3K7Cjjg3HWcq1w3g/view?usp=drive_link

Test Data - https://drive.google.com/file/d/1j8b6nC4PKgc0ZK9DXvxz5WRqmVb31YAZ/view?usp=drive_link

You can use the notebook on your local machine using Jupyter Notebooks or Visual Studio Code extension. The recommended way is to upload the notebook on Kaggle Notebooks as it offers GPU training and one
can upload larger files which is not possible on Google Colab. Another method is to directly call the files into your notebook using Google Drive Colab API.

-----------------------------------------------------------------------------------------------------------------

## Contributors -
1. *Sarvesh Ramani*
2. *Shivika Lamba*
3. *Yash Dalal*

## Mentor -
*Rohan Shah*
