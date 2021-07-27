##Covid-detection-using-cough

This repository contains the ipynb file where the model to predict whether a person is having covid or not is predicted using his cough,vowel,breathing sounds. The data was taken from 
Coswara Dataset (https://github.com/iiscleap/Coswara-Data) which is developed by IISc. The data contains recordings of breathing, coughing, saying vowels etc. I use this data and the librosa
library to extract the feautures from the recordings. I then feed these features to the Neural Network model which I have created using ANNs. The max accuracy I get is of 70%.
