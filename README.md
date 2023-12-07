# Machine Learning II Project - UrbanSound8K dataset

## Description

This project was developed for the Machine Learning II course of the Bachelor's degree in Artificial Intelligence and Data Science at Faculty of Sciences of University of Porto. The main goal of this project is to develop a model that can classify sounds from the UrbanSound8K dataset. The dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren and street_music. The classes are drawn from the urban sound taxonomy. For more information about the dataset, please visit: https://urbansounddataset.weebly.com/urbansound8k.html

## Python version
Python 3.10.0 installed.

## Requirements Lib 

-- tensorflow 2.10.0

-- librosa 0.9.2

-- numpy 1.19.5

-- pandas 1.1.5

-- soundfile 0.12.1

-- matplotlib 3.3.4

-- pickle 4.0

-- pydub 0.25.1

-- seaborn 0.11.2

-- scikit-learn 0.24.2

-- keras 2.6.0

## How to run

The first part of the project is the data analysis and data preprocessing. All the code is in the file `data-analysis-preprocessing.ipynb`. 

This file will generate the files `dataset_cnn.pkl`, `dataset_mlp_ids.pkl`.

The second part of the project is the MLP model. All the code is in the file `mlp.ipynb`.

And the last part of the project is the CNN model. All the code is in the file `cnn.ipynb`.




#### Work done by: Ana Pinto (202105085) |  Miguel Santos (202105289) | Tomás Rodrigues (202107937)
