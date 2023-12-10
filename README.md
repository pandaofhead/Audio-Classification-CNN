# Audio-Classification-CNN
This is a course project@**Cornell Tech CS5785 23fall**

In this project, CNN models including **Conv1D, Conv2D and LSTM** are used to classify audio files(musical instrument/type), and reaching a high accuracy ranging from **97% - 99%!**
![ThreeModels](image/ThreeModels.png)

## Data Downloading

Data Downloading Link:
https://zenodo.org/records/3685331 

Please download two files(TinySOL_metadata.csv, TinySOL.tar.gz). In this project, audio files are directly computed. However, using the file path included in TinySOL_metadata.csv to refer to the audio files is suggested as it is common practice.

## Data Preprocessing
### clean.ipynb
*For simplicity and easy computing, the audio folder is suggested to be construcuted in only one layer:     instrument_folder -> class_folder -> audio.wav*


## Model Training
### train.ipynb
### Conv1D Layers
![Conv1DLayer](image/conv1d_layer.png)
### Conv2D Layers
![Conv2DLayer](image/conv2d_layer.png)
### LSTM Layers
![LSTMLayer](image/lstm_layer.png)
## Model Prediction & Plot
### predict.ipynb & plot.ipynb