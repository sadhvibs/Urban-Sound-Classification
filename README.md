**URBAN SOUND CLASSIFICATION**

Developed a Python program to classify 10 different classes of urban sound recordings using Artificial Neural Network(ANN). 
The features has been extracted using MFCC (Mel-frequency Cepstral Co-efficient)

**DATSET**

I've used UrbanSound8K dataset which can be found [here] (https://www.kaggle.com/datasets/chrisfilo/urbansound8k).
This dataset contains 8732 sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music.

This sound classification challenge contains 80% of dataset has training samples with labels and 20% of dataset has unlabelled test samples.

**ARTIFICIAL NEURAL NETWORK**

When we read the data using librosa, we get a time series data with the default sampling rate of 22050, which means for every second, we have 22050 data points available. For this dataset, the data was read with the default sampling rate and then each audio sample was made to be of a fixed length of 4 seconds
